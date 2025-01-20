## Rechenschritt Type

`object` ([Rechenschritt](rechenschritt.md))

# Rechenschritt Properties

| Property                                                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :-------------------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [rechenschrittBestandteilId](#rechenschrittbestandteilid)       | `integer` | Optional | cannot be null | [Rechenschritt](rechenschritt-properties-rechenschrittbestandteilid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/rechenschrittBestandteilId")       |
| [referenzRechenschrittId](#referenzrechenschrittid)             | `integer` | Optional | cannot be null | [Rechenschritt](rechenschritt-properties-referenzrechenschrittid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/referenzRechenschrittId")             |
| [operation](#operation)                                         | `string`  | Optional | cannot be null | [Rechenschritt](arithmetischeoperation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArithmetischeOperation.schema.json#/properties/operation")                                           |
| [verlustfaktorTrafo](#verlustfaktortrafo)                       | `number`  | Optional | cannot be null | [Rechenschritt](rechenschritt-properties-verlustfaktortrafo.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/verlustfaktorTrafo")                       |
| [verlustfaktorLeitung](#verlustfaktorleitung)                   | `number`  | Optional | cannot be null | [Rechenschritt](rechenschritt-properties-verlustfaktorleitung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/verlustfaktorLeitung")                   |
| [aufteilungsfaktorEnergiemenge](#aufteilungsfaktorenergiemenge) | `number`  | Optional | cannot be null | [Rechenschritt](rechenschritt-properties-aufteilungsfaktorenergiemenge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/aufteilungsfaktorEnergiemenge") |
| [messlokationsId](#messlokationsid)                             | `string`  | Optional | cannot be null | [Rechenschritt](rechenschritt-properties-messlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/messlokationsId")                             |
| [energieflussrichtung](#energieflussrichtung)                   | `string`  | Optional | cannot be null | [Rechenschritt](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energieflussrichtung")                                              |

## rechenschrittBestandteilId

rechenschrittBestandteilId

`rechenschrittBestandteilId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Rechenschritt](rechenschritt-properties-rechenschrittbestandteilid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/rechenschrittBestandteilId")

### rechenschrittBestandteilId Type

`integer`

## referenzRechenschrittId

referenzRechenschrittId

`referenzRechenschrittId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Rechenschritt](rechenschritt-properties-referenzrechenschrittid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/referenzRechenschrittId")

### referenzRechenschrittId Type

`integer`

## operation

Mit dieser Aufzählung können arithmetische Operationen festgelegt werden

`operation`

*   is optional

*   Type: `string` ([ArithmetischeOperation](arithmetischeoperation.md))

*   cannot be null

*   defined in: [Rechenschritt](arithmetischeoperation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArithmetischeOperation.schema.json#/properties/operation")

### operation Type

`string` ([ArithmetischeOperation](arithmetischeoperation.md))

### operation Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"ADDITION"`       |             |
| `"SUBTRAKTION"`    |             |
| `"DIVISION"`       |             |
| `"DIVIDEND"`       |             |
| `"MULTIPLIKATION"` |             |
| `"POSITIVWERT"`    |             |

## verlustfaktorTrafo

verlustfaktorTrafo

`verlustfaktorTrafo`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Rechenschritt](rechenschritt-properties-verlustfaktortrafo.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/verlustfaktorTrafo")

### verlustfaktorTrafo Type

`number`

### verlustfaktorTrafo Constraints

**unknown format**: the value of this string must follow the format: `float`

## verlustfaktorLeitung

verlustfaktorLeitung

`verlustfaktorLeitung`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Rechenschritt](rechenschritt-properties-verlustfaktorleitung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/verlustfaktorLeitung")

### verlustfaktorLeitung Type

`number`

### verlustfaktorLeitung Constraints

**unknown format**: the value of this string must follow the format: `float`

## aufteilungsfaktorEnergiemenge

aufteilungsfaktorEnergiemenge

`aufteilungsfaktorEnergiemenge`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Rechenschritt](rechenschritt-properties-aufteilungsfaktorenergiemenge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/aufteilungsfaktorEnergiemenge")

### aufteilungsfaktorEnergiemenge Type

`number`

### aufteilungsfaktorEnergiemenge Constraints

**unknown format**: the value of this string must follow the format: `float`

## messlokationsId

messlokationsId

`messlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechenschritt](rechenschritt-properties-messlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/messlokationsId")

### messlokationsId Type

`string`

## energieflussrichtung

Spezifiziert die Energierichtung einer Markt- und/oder Messlokation

`energieflussrichtung`

*   is optional

*   Type: `string` ([Energierichtung](energierichtung.md))

*   cannot be null

*   defined in: [Rechenschritt](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energieflussrichtung")

### energieflussrichtung Type

`string` ([Energierichtung](energierichtung.md))

### energieflussrichtung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"AUSSP"` |             |
| `"EINSP"` |             |
