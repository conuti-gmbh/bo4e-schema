# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repository Is

This is a **schema-only repository** maintained by CONUTI GmbH. It contains BO4E (Business Object 4 Energy) JSON schemas and auto-generated documentation for the German energy market domain. It is a Composer library (`conuti/bo4e-schema`), not an application.

Content is largely **auto-generated** by an external `bo4e-generator` tool and synced via automated commits. Manual edits to generated files (markdown docs, OpenAPI spec) will be overwritten on the next sync.

## Repository Structure

```
schemas/v1/          # JSON Schema files (source of truth)
  bo/                # Business Objects (35 files) — core domain entities
  com/               # Common/composite objects (83 files)
  enum/              # Enumerations (152 files)
  cdoc/              # Change Document objects (8 files)
  object.meta.schema.json  # Custom meta-schema extending Draft 2020-12

docs/
  schemas/v1/        # Auto-generated markdown documentation (1374 files)
  openapi-model/     # Model definitions (bo/, com/, enum/, cdoc/, fields/)
  openapi.yaml       # Auto-generated OpenAPI 3.0.0 spec
  examples/bo/       # Example JSON files for BO objects

translation/v1/
  DE_to_EN.yaml      # German-to-English identifier mapping (~133KB)
```

## Schema Architecture

**JSON Schema standard**: Draft 2020-12 with a custom `x-descriptions` extension defined in `object.meta.schema.json`. This extension supports multilingual descriptions — German names are the primary identifiers; `x-descriptions` carries English translations and additional metadata.

**Schema categories:**
- **BO** (Business Objects): Core domain entities — transactions (Anfrage, Angebot, Rechnung), locations (Marktlokation, Messlokation), pricing (Preisblatt), contracts (Vertrag), etc.
- **COM** (Common): Shared composite structures — addresses, prices, contacts, metering data, etc.
- **ENUM**: 152 standardized enumeration types for statuses, roles, directions, etc.
- **CDOC**: Change/process document objects (Message, Process, Stammdaten, etc.)

Schemas use `$ref` for composition. Properties include `faker` hints for test data generation.

## Translation Files (`translation/v1/`)

Contains flat key-value YAML maps consumed by a translation-generating application to produce translated versions of all BO4E schemas, examples, and OpenAPI models.

**Naming convention**: `DE_to_<LANG>.yaml` (e.g. `DE_to_EN.yaml`). Adding a new file for a new language is sufficient to trigger generation for that language.

**Structure**: Named YAML sections (one per schema or enum) for human readability, each containing a flat map of `GermanIdentifier: TargetLanguageIdentifier`. At pipeline runtime all sections are merged into a single lookup table — section names are ignored by the application.

**What gets translated**: Every identifier in the schemas — class names, property names, enum values, `$ref` path segments, and file/folder names are all rewritten using the same map.

**Editing rules**: Add a new entry whenever a new German identifier is introduced in the schemas. Matching is exact and case-sensitive; a missing entry causes the German identifier to pass through untranslated into the output.

## What Can Be Manually Edited

- `schemas/v1/**/*.json` — JSON schema files are the source of truth; changes here are valid
- `translation/v1/DE_to_EN.yaml` — translation mappings
- `composer.json` — library metadata

**Do not manually edit** generated files: `docs/schemas/`, `docs/openapi.yaml`, `docs/openapi-model/` — these are regenerated automatically.

## No Build or Test Commands

This repository has no build scripts, test suite, linting configuration, or CI/CD workflows. Validation is handled by the external `bo4e-generator` tool that generates the docs from these schemas.
