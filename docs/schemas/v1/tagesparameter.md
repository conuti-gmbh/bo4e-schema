## Tagesparameter Type

`object` ([Tagesparameter](tagesparameter.md))

# Tagesparameter Properties

| Property                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                        |
| :-------------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [klimazone](#klimazone)                       | `string` | Optional | cannot be null | [Tagesparameter](tagesparameter-properties-klimazone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/klimazone")                       |
| [temperaturmessstelle](#temperaturmessstelle) | `string` | Optional | cannot be null | [Tagesparameter](tagesparameter-properties-temperaturmessstelle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/temperaturmessstelle") |
| [dienstanbieter](#dienstanbieter)             | `string` | Optional | cannot be null | [Tagesparameter](tagesparameter-properties-dienstanbieter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/dienstanbieter")             |
| [herausgeber](#herausgeber)                   | `string` | Optional | cannot be null | [Tagesparameter](herausgeber.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Herausgeber.schema.json#/properties/herausgeber")                                               |

## klimazone

klimazone

`klimazone`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tagesparameter](tagesparameter-properties-klimazone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/klimazone")

### klimazone Type

`string`

## temperaturmessstelle

temperaturmessstelle

`temperaturmessstelle`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tagesparameter](tagesparameter-properties-temperaturmessstelle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/temperaturmessstelle")

### temperaturmessstelle Type

`string`

## dienstanbieter

dienstanbieter

`dienstanbieter`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tagesparameter](tagesparameter-properties-dienstanbieter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/dienstanbieter")

### dienstanbieter Type

`string`

## herausgeber

Herausgeber

`herausgeber`

*   is optional

*   Type: `string` ([Herausgeber](herausgeber.md))

*   cannot be null

*   defined in: [Tagesparameter](herausgeber.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Herausgeber.schema.json#/properties/herausgeber")

### herausgeber Type

`string` ([Herausgeber](herausgeber.md))

### herausgeber Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"NB"`   |             |
| `"BDEW"` |             |
| `"TUM"`  |             |
