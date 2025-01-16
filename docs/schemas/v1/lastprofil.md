## Lastprofil Type

`object` ([Lastprofil](lastprofil.md))

# Lastprofil Properties

| Property                                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :------------------------------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bezeichnung](#bezeichnung)                             | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/bezeichnung")                             |
| [verfahren](#verfahren)                                 | `string`  | Optional | cannot be null | [Lastprofil](profilverfahren.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profilverfahren.schema.json#/properties/verfahren")                                           |
| [profilart](#profilart)                                 | `string`  | Optional | cannot be null | [Lastprofil](profilart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profilart.schema.json#/properties/profilart")                                                       |
| [profilschar](#profilschar)                             | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-profilschar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/profilschar")                             |
| [einspeisung](#einspeisung)                             | `boolean` | Optional | cannot be null | [Lastprofil](lastprofil-properties-einspeisung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/einspeisung")                             |
| [herausgeber](#herausgeber)                             | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-herausgeber.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/herausgeber")                             |
| [tagesparameter](#tagesparameter)                       | `object`  | Optional | cannot be null | [Lastprofil](tagesparameter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/tagesparameter")                                         |
| [referenzprofilbezeichnung](#referenzprofilbezeichnung) | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-referenzprofilbezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/referenzprofilbezeichnung") |

## bezeichnung

bezeichnung

`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`

## verfahren

Profilverfahren

`verfahren`

*   is optional

*   Type: `string` ([Profilverfahren](profilverfahren.md))

*   cannot be null

*   defined in: [Lastprofil](profilverfahren.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profilverfahren.schema.json#/properties/verfahren")

### verfahren Type

`string` ([Profilverfahren](profilverfahren.md))

### verfahren Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"SYNTHETISCH"` |             |
| `"ANALYTISCH"`  |             |

## profilart

Profilart

`profilart`

*   is optional

*   Type: `string` ([Profilart](profilart.md))

*   cannot be null

*   defined in: [Lastprofil](profilart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profilart.schema.json#/properties/profilart")

### profilart Type

`string` ([Profilart](profilart.md))

### profilart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                        | Explanation |
| :------------------------------------------- | :---------- |
| `"ART_STANDARDLASTPROFIL"`                   |             |
| `"ART_TAGESPARAMETERABHAENGIGES_LASTPROFIL"` |             |
| `"ART_LASTPROFIL"`                           |             |

## profilschar

profilschar

`profilschar`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-profilschar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/profilschar")

### profilschar Type

`string`

## einspeisung

einspeisung

`einspeisung`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-einspeisung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/einspeisung")

### einspeisung Type

`boolean`

## herausgeber

herausgeber

`herausgeber`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-herausgeber.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/herausgeber")

### herausgeber Type

`string`

## tagesparameter



`tagesparameter`

*   is optional

*   Type: `object` ([Tagesparameter](tagesparameter.md))

*   cannot be null

*   defined in: [Lastprofil](tagesparameter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/tagesparameter")

### tagesparameter Type

`object` ([Tagesparameter](tagesparameter.md))

## referenzprofilbezeichnung

referenzprofilbezeichnung

`referenzprofilbezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-referenzprofilbezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/referenzprofilbezeichnung")

### referenzprofilbezeichnung Type

`string`
