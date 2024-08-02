## Preis Type

`object` ([Preis](preis.md))

# Preis Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                       |
| :------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [wert](#wert)             | `number` | Optional | cannot be null | [Preis](preis-properties-wert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/wert")           |
| [einheit](#einheit)       | `string` | Optional | cannot be null | [Preis](waehrungseinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waehrungseinheit.schema.json#/properties/einheit") |
| [bezugswert](#bezugswert) | `string` | Optional | cannot be null | [Preis](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/bezugswert")    |
| [status](#status)         | `string` | Optional | cannot be null | [Preis](preisstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Preisstatus.schema.json#/properties/status")            |

## wert



`wert`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Preis](preis-properties-wert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/wert")

### wert Type

`number`

### wert Constraints

**unknown format**: the value of this string must follow the format: `float`

## einheit



`einheit`

*   is optional

*   Type: `string` ([Waehrungseinheit](waehrungseinheit.md))

*   cannot be null

*   defined in: [Preis](waehrungseinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waehrungseinheit.schema.json#/properties/einheit")

### einheit Type

`string` ([Waehrungseinheit](waehrungseinheit.md))

### einheit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"EUR"` |             |
| `"CT"`  |             |

## bezugswert



`bezugswert`

*   is optional

*   Type: `string` ([Mengeneinheit](mengeneinheit.md))

*   cannot be null

*   defined in: [Preis](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/bezugswert")

### bezugswert Type

`string` ([Mengeneinheit](mengeneinheit.md))

### bezugswert Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"W"`          |             |
| `"WH"`         |             |
| `"KW"`         |             |
| `"KWH"`        |             |
| `"KVARH"`      |             |
| `"MW"`         |             |
| `"MWH"`        |             |
| `"STUECK"`     |             |
| `"KUBIKMETER"` |             |
| `"STUNDE"`     |             |
| `"TAG"`        |             |
| `"MONAT"`      |             |
| `"JAHR"`       |             |
| `"PROZENT"`    |             |
| `"ANZAHL"`     |             |
| `"VAR"`        |             |
| `"KVAR"`       |             |
| `"VARH"`       |             |
| `"KWHK"`       |             |
| `"Z16"`        |             |
| `"KWT"`        |             |

## status



`status`

*   is optional

*   Type: `string` ([Preisstatus](preisstatus.md))

*   cannot be null

*   defined in: [Preis](preisstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Preisstatus.schema.json#/properties/status")

### status Type

`string` ([Preisstatus](preisstatus.md))

### status Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"VORLAEUFIG"` |             |
| `"ENDGUELTIG"` |             |
