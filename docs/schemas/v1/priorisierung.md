## Untitled object in undefined Type

`object` ([Details](priorisierung.md))

# Untitled object in undefined Properties

| Property                                                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                               |
| :---------------------------------------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [produktpaketID](#produktpaketid)                                                   | `integer` | Optional | cannot be null | [Untitled schema](priorisierung-properties-produktpaketid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Priorisierung.schema.json#/properties/produktpaketID")                                                     |
| [notwendigkeitProduktpaket](#notwendigkeitproduktpaket)                             | `string`  | Optional | cannot be null | [Untitled schema](notwendigkeitproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/NotwendigkeitProduktpaket.schema.json#/properties/notwendigkeitProduktpaket")                                           |
| [priorisierungErforderlichesProduktpaket](#priorisierungerforderlichesproduktpaket) | `string`  | Optional | cannot be null | [Untitled schema](priorisierungerforderlichesproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/PriorisierungErforderlichesProduktpaket.schema.json#/properties/priorisierungErforderlichesProduktpaket") |

## produktpaketID



`produktpaketID`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Untitled schema](priorisierung-properties-produktpaketid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Priorisierung.schema.json#/properties/produktpaketID")

### produktpaketID Type

`integer`

## notwendigkeitProduktpaket



`notwendigkeitProduktpaket`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](notwendigkeitproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/NotwendigkeitProduktpaket.schema.json#/properties/notwendigkeitProduktpaket")

### notwendigkeitProduktpaket Type

`string`

### notwendigkeitProduktpaket Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                | Explanation |
| :--------------------------------------------------- | :---------- |
| `"ZUORDNUNG_NUR_WENN_PRODUKTPAKET_UMSETZBAR"`        |             |
| `"ZUORDNUNG_AUCH_WENN_PRODUKTPAKET_NICHT_UMSETZBAR"` |             |

## priorisierungErforderlichesProduktpaket



`priorisierungErforderlichesProduktpaket`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](priorisierungerforderlichesproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/PriorisierungErforderlichesProduktpaket.schema.json#/properties/priorisierungErforderlichesProduktpaket")

### priorisierungErforderlichesProduktpaket Type

`string`

### priorisierungErforderlichesProduktpaket Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"PRIORITAET1"` |             |
| `"PRIORITAET2"` |             |
| `"PRIORITAET3"` |             |
| `"PRIORITAET4"` |             |
| `"PRIORITAET5"` |             |
