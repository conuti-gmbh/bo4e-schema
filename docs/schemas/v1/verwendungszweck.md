## Verwendungszweck Type

`object` ([Verwendungszweck](verwendungszweck.md))

# Verwendungszweck Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                |
| :------------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [marktrolle](#marktrolle) | `string` | Optional | cannot be null | [Verwendungszweck](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/marktrolle")                        |
| [zweck](#zweck)           | `array`  | Optional | can be null    | [Verwendungszweck](verwendungszweck-properties-zweck.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verwendungszweck.schema.json#/properties/zweck") |

## marktrolle

Diese Rollen kann ein Marktteilnehmer einnehmen

`marktrolle`

*   is optional

*   Type: `string` ([Marktrolle](marktrolle.md))

*   cannot be null

*   defined in: [Verwendungszweck](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/marktrolle")

### marktrolle Type

`string` ([Marktrolle](marktrolle.md))

### marktrolle Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"NB"`              |             |
| `"LF"`              |             |
| `"MSB"`             |             |
| `"MSBA"`            |             |
| `"GMSB"`            |             |
| `"MDL"`             |             |
| `"DL"`              |             |
| `"BKV"`             |             |
| `"BKO"`             |             |
| `"UENB"`            |             |
| `"KUNDE-SELBST-NN"` |             |
| `"MGV"`             |             |
| `"EIV"`             |             |
| `"RB"`              |             |
| `"KUNDE"`           |             |
| `"INTERESSENT"`     |             |
| `"KN"`              |             |
| `"UBA"`             |             |
| `"BIKO"`            |             |
| `"ESA"`             |             |

## zweck

zweck

`zweck`

*   is optional

*   Type: `string[]` ([VerwendungszweckValue](verwendungszweckvalue.md))

*   can be null

*   defined in: [Verwendungszweck](verwendungszweck-properties-zweck.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verwendungszweck.schema.json#/properties/zweck")

### zweck Type

`string[]` ([VerwendungszweckValue](verwendungszweckvalue.md))
