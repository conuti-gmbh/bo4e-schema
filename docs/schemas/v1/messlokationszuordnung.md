## Messlokationszuordnung Type

`object` ([Messlokationszuordnung](messlokationszuordnung.md))

# Messlokationszuordnung Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                      |
| :---------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [messlokationsId](#messlokationsid) | `string` | Optional | cannot be null | [Messlokationszuordnung](messlokationszuordnung-properties-messlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messlokationszuordnung.schema.json#/properties/messlokationsId") |
| [arithmetik](#arithmetik)           | `string` | Optional | cannot be null | [Messlokationszuordnung](arithmetischeoperation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArithmetischeOperation.schema.json#/properties/arithmetik")                                |
| [gueltigSeit](#gueltigseit)         | `string` | Optional | cannot be null | [Messlokationszuordnung](messlokationszuordnung-properties-gueltigseit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messlokationszuordnung.schema.json#/properties/gueltigSeit")         |
| [gueltigBis](#gueltigbis)           | `string` | Optional | cannot be null | [Messlokationszuordnung](messlokationszuordnung-properties-gueltigbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messlokationszuordnung.schema.json#/properties/gueltigBis")           |

## messlokationsId

MesslokationsId

`messlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Messlokationszuordnung](messlokationszuordnung-properties-messlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messlokationszuordnung.schema.json#/properties/messlokationsId")

### messlokationsId Type

`string`

## arithmetik

Mit dieser Aufzählung können arithmetische Operationen festgelegt werden

`arithmetik`

*   is optional

*   Type: `string` ([ArithmetischeOperation](arithmetischeoperation.md))

*   cannot be null

*   defined in: [Messlokationszuordnung](arithmetischeoperation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArithmetischeOperation.schema.json#/properties/arithmetik")

### arithmetik Type

`string` ([ArithmetischeOperation](arithmetischeoperation.md))

### arithmetik Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"ADDITION"`       |             |
| `"SUBTRAKTION"`    |             |
| `"DIVISION"`       |             |
| `"DIVIDEND"`       |             |
| `"MULTIPLIKATION"` |             |
| `"POSITIVWERT"`    |             |

## gueltigSeit

Zuordnung gültig ab

`gueltigSeit`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Messlokationszuordnung](messlokationszuordnung-properties-gueltigseit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messlokationszuordnung.schema.json#/properties/gueltigSeit")

### gueltigSeit Type

`string`

### gueltigSeit Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## gueltigBis

Zuordnung gültig bis

`gueltigBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Messlokationszuordnung](messlokationszuordnung-properties-gueltigbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messlokationszuordnung.schema.json#/properties/gueltigBis")

### gueltigBis Type

`string`

### gueltigBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
