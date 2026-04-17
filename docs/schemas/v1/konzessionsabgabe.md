## Konzessionsabgabe Type

`object` ([Konzessionsabgabe](konzessionsabgabe.md))

# Konzessionsabgabe Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                           |
| :---------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [satz](#satz)           | `string` | Optional | cannot be null | [Konzessionsabgabe](abgabeart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AbgabeArt.schema.json#/properties/satz")                                          |
| [kosten](#kosten)       | `number` | Optional | cannot be null | [Konzessionsabgabe](konzessionsabgabe-properties-kosten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Konzessionsabgabe.schema.json#/properties/kosten")       |
| [kategorie](#kategorie) | `string` | Optional | cannot be null | [Konzessionsabgabe](konzessionsabgabe-properties-kategorie.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Konzessionsabgabe.schema.json#/properties/kategorie") |

## satz

Art der Konzessionsabgabe

`satz`

*   is optional

*   Type: `string` ([AbgabeArt](abgabeart.md))

*   cannot be null

*   defined in: [Konzessionsabgabe](abgabeart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AbgabeArt.schema.json#/properties/satz")

### satz Type

`string` ([AbgabeArt](abgabeart.md))

### satz Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"KAS"` |             |
| `"SA"`  |             |
| `"SAS"` |             |
| `"TA"`  |             |
| `"TAS"` |             |
| `"TK"`  |             |
| `"TKS"` |             |
| `"TS"`  |             |
| `"TSS"` |             |

## kosten

Kosten

`kosten`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Konzessionsabgabe](konzessionsabgabe-properties-kosten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Konzessionsabgabe.schema.json#/properties/kosten")

### kosten Type

`number`

### kosten Constraints

**unknown format**: the value of this string must follow the format: `float`

## kategorie

Kategorie

`kategorie`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Konzessionsabgabe](konzessionsabgabe-properties-kategorie.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Konzessionsabgabe.schema.json#/properties/kategorie")

### kategorie Type

`string`
