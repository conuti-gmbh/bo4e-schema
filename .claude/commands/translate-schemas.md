---
description: Scan the current feature branch diff for new BO4E schema identifiers that are missing from translation/v1/ YAML files, propose domain-aware translations, get user approval, and write the approved entries to the files.
allowed-tools: Bash(git *) Read Write Grep Glob
---

You are updating the BO4E schema translation files in `translation/v1/`. Work through the following steps in order. Do not skip steps or combine them.

---

## Step 1 — Establish the diff baseline

Run:
```
git merge-base HEAD origin/master
```
to find the common ancestor. Then get all schema files that were added or modified on this branch:
```
git diff <merge-base>...HEAD --name-status -- 'schemas/v1/**/*.json'
```
Record two lists:
- **Added files** (`A` status): full path
- **Modified files** (`M` status): full path

If there are no changed schema files, tell the user and stop.

---

## Step 2 — Extract new German identifiers

For each **added file**: read the complete file and collect:
1. **File stem** — the schema name without path or extension (e.g. `schemas/v1/bo/NeueBO.schema.json` → `NeueBO`)
2. **Schema title** — value of the root `"title"` field (usually identical to the file stem, but always include it if it differs)
3. **Property names** — every key under `"properties"` (for object schemas)
4. **Enum values** — every string in the root `"enum"` array (for string-enum schemas)

For each **modified file**: run `git diff <merge-base>...HEAD -- <file>` and extract identifiers **only from added lines** (lines starting with `+`, excluding `+++`). Apply the same four categories above but only for newly introduced keys/values — not existing ones.

Deduplicate across all files. The result is the **candidate set**.

---

## Step 3 — Load existing translations and detect gaps

Read every file matching `translation/v1/DE_to_*.yaml`. For each file:
- Parse it as YAML (it is valid YAML; the named sections are cosmetic — the application merges all into one flat map)
- Build two lookup structures:
  - `keys`: set of all German keys already translated
  - `values`: set of all target-language values already used (for bijectivity check)
- Identify the **target language code** from the filename (e.g. `DE_to_EN.yaml` → `EN`)

From the candidate set, remove any identifier already present as a key in **any** of the translation files. The remaining identifiers are the **missing set**.

If the missing set is empty, tell the user everything is already covered and stop.

---

## Step 4 — Propose translations

For each translation file and each identifier in the missing set, propose a translation in the target language. Apply these rules:

**Domain context — German energy market / BDEW:**
- Use the standard English terminology from BDEW, ENTSO-E, and EDI@Energy publications.
- Prefer concise PascalCase or camelCase identifiers (matching the style already in the file).
- Common roots: Markt→Market, Lokation→Location, Netz→Grid/Network, Strom→Electricity/Power, Gas→Gas, Wärme→Heat, Menge→Quantity/Amount, Preis→Price, Zeit→Time, Zeitraum→Period, Vertrag→Contract, Rechnung→Invoice, Auftrag→Order, Zähler→Meter, Messung→Measurement, Speicher→Storage, Erzeuger→Generator, Verbraucher→Consumer, Lieferant→Supplier, Netzbetreiber→GridOperator, Bilanzkreis→BalancingGroup, Aggregationsebene→AggregationLevel.
- For abbreviations and codes that are BDEW/EDI@Energy standard (e.g. `GPKE`, `MaBiS`, `UTILMD`, `MSCONS`), keep them as-is.
- Enum values that are already abbreviations or codes (e.g. `KAS`, `SA`, `INBOUND`) should be kept as-is unless there is a clear and universally recognised English equivalent.

**Bijectivity constraint:** A proposed value must not already appear in the `values` set for that language file. If your first proposal conflicts, try an unambiguous synonym. Mark it as needing review if no clean option exists.

---

## Step 5 — Present proposals for user review

Display the findings in a structured format, grouped by translation file. For each file use a table:

```
### DE_to_EN.yaml  (N new entries)

| German identifier        | Category        | Proposed EN                | Notes              |
|--------------------------|-----------------|----------------------------|--------------------|
| NeueBO                   | file/class name | NewBO                      |                    |
| neueEigenschaft          | property        | newProperty                |                    |
| NEUER_ENUM_WERT          | enum value      | NEW_ENUM_VALUE             |                    |
| KomplexerBegriff         | class name      | ComplexTerm                | review recommended |
```

Categories: `file/class name`, `property`, `enum value`.

After each table, ask:

> "Please review these proposals. You can:
> - Type **accept** to approve all entries as-is.
> - Type **adjust** followed by a list of corrections in the form `GermanKey: NewValue`.
> - Type **reject** to skip this file entirely."

Wait for the user's response before proceeding.

---

## Step 6 — Apply adjustments and confirm

If the user types **adjust**, update the relevant rows with their corrections. Re-check that no corrected value conflicts with existing values in that file. If a conflict exists, flag it and ask the user to pick a different value. Then show the final table again and ask for final confirmation.

If the user types **accept** (or confirms after adjustments), proceed to Step 7. If the user types **reject**, skip writing that file and move to the next language.

---

## Step 7 — Write entries to the translation files

For each approved translation file:
1. Read the current file content.
2. Determine the correct section to append to — choose the section whose name best matches the schema category (`bo`, `com`, `enum`, `cdoc`). If no suitable section exists, append a new one at the end.
3. Append the new entries as `GermanKey: TargetValue` lines within that section.
4. Write the updated file.

After writing all files, report a summary: how many entries were added to each file.

---

## Important rules throughout

- Never modify entries that already exist in the translation files.
- Never add a value that is already used as a target-language value in the same file (bijectivity must be preserved).
- Preserve the existing formatting and comment style of the YAML files.
- Sections are cosmetic — append to the most relevant existing section rather than creating redundant ones.
- If you are uncertain about a translation, mark the row `review recommended` in the Notes column and proceed rather than blocking.
