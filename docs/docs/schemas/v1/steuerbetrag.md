## Steuerbetrag Type

`object` ([Steuerbetrag](steuerbetrag.md))

# Steuerbetrag Properties

| Property                                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                          |
| :---------------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [steuerkennzeichen](#steuerkennzeichen)               | `string` | Optional | cannot be null | [Steuerbetrag](steuerbetrag-properties-steuerkennzeichen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/steuerkennzeichen")               |
| [basiswert](#basiswert)                               | `number` | Optional | cannot be null | [Steuerbetrag](steuerbetrag-properties-basiswert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/basiswert")                               |
| [steuerwert](#steuerwert)                             | `number` | Optional | cannot be null | [Steuerbetrag](steuerbetrag-properties-steuerwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/steuerwert")                             |
| [waehrung](#waehrung)                                 | `string` | Optional | cannot be null | [Steuerbetrag](steuerbetrag-properties-waehrung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/waehrung")                                 |
| [basiswertVorausbezahlt](#basiswertvorausbezahlt)     | `number` | Optional | cannot be null | [Steuerbetrag](steuerbetrag-properties-basiswertvorausbezahlt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/basiswertVorausbezahlt")     |
| [steuerwertVorausbezahhlt](#steuerwertvorausbezahhlt) | `number` | Optional | cannot be null | [Steuerbetrag](steuerbetrag-properties-steuerwertvorausbezahhlt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/steuerwertVorausbezahhlt") |

## steuerkennzeichen

Kennzeichnung des Steuersatzes, bzw. Verfahrens. Details Steuerkennzeichen

`steuerkennzeichen`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Steuerbetrag](steuerbetrag-properties-steuerkennzeichen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/steuerkennzeichen")

### steuerkennzeichen Type

`string`

## basiswert

Nettobetrag für den die Steuer berechnet wurde. Z.B. 200

`basiswert`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Steuerbetrag](steuerbetrag-properties-basiswert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/basiswert")

### basiswert Type

`number`

### basiswert Constraints

**unknown format**: the value of this string must follow the format: `float`

## steuerwert

Aus dem Basiswert berechnete Steuer. Z.B. 38 (bei UST\_19), falls Basiswert 200 ist.

`steuerwert`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Steuerbetrag](steuerbetrag-properties-steuerwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/steuerwert")

### steuerwert Type

`number`

### steuerwert Constraints

**unknown format**: the value of this string must follow the format: `float`

## waehrung

Währung. Z.B. Euro.

`waehrung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Steuerbetrag](steuerbetrag-properties-waehrung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/waehrung")

### waehrung Type

`string`

## basiswertVorausbezahlt

basiswertVorausbezahlt

`basiswertVorausbezahlt`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Steuerbetrag](steuerbetrag-properties-basiswertvorausbezahlt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/basiswertVorausbezahlt")

### basiswertVorausbezahlt Type

`number`

### basiswertVorausbezahlt Constraints

**unknown format**: the value of this string must follow the format: `float`

## steuerwertVorausbezahhlt

steuerwertVorausbezahhlt

`steuerwertVorausbezahhlt`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Steuerbetrag](steuerbetrag-properties-steuerwertvorausbezahhlt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/steuerwertVorausbezahhlt")

### steuerwertVorausbezahhlt Type

`number`

### steuerwertVorausbezahhlt Constraints

**unknown format**: the value of this string must follow the format: `float`
