## Erreichbarkeit Type

`object` ([Erreichbarkeit](erreichbarkeit.md))

# Erreichbarkeit Properties

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                        |
| :-------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [verfuegbarkeit](#verfuegbarkeit) | `string` | Optional | cannot be null | [Erreichbarkeit](verfuegbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verfuegbarkeit.schema.json#/properties/verfuegbarkeit")      |
| [zeit](#zeit)                     | `string` | Optional | cannot be null | [Erreichbarkeit](erreichbarkeit-properties-zeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Erreichbarkeit.schema.json#/properties/zeit") |

## verfuegbarkeit

Verfuegbarkeit

`verfuegbarkeit`

*   is optional

*   Type: `string` ([Verfuegbarkeit](verfuegbarkeit.md))

*   cannot be null

*   defined in: [Erreichbarkeit](verfuegbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verfuegbarkeit.schema.json#/properties/verfuegbarkeit")

### verfuegbarkeit Type

`string` ([Verfuegbarkeit](verfuegbarkeit.md))

### verfuegbarkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"MONTAG"`     |             |
| `"DIENSTAG"`   |             |
| `"MITTWOCH"`   |             |
| `"DONNERSTAG"` |             |
| `"FREITAG"`    |             |
| `"PAUSE"`      |             |

## zeit

zeit

`zeit`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Erreichbarkeit](erreichbarkeit-properties-zeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Erreichbarkeit.schema.json#/properties/zeit")

### zeit Type

`string`
