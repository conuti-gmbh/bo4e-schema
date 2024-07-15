## Priorisierung Type

`object` ([Priorisierung](priorisierung.md))

# Priorisierung Properties

| Property                                                                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                             |
| :---------------------------------------------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [notwendigkeitProduktpaket](#notwendigkeitproduktpaket)                             | `string` | Optional | cannot be null | [Priorisierung](notwendigkeitproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/NotwendigkeitProduktpaket.schema.json#/properties/notwendigkeitProduktpaket")                                           |
| [priorisierungErforderlichesProduktpaket](#priorisierungerforderlichesproduktpaket) | `string` | Optional | cannot be null | [Priorisierung](priorisierungerforderlichesproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/PriorisierungErforderlichesProduktpaket.schema.json#/properties/priorisierungErforderlichesProduktpaket") |

## notwendigkeitProduktpaket



`notwendigkeitProduktpaket`

*   is optional

*   Type: `string` ([NotwendigkeitProduktpaket](notwendigkeitproduktpaket.md))

*   cannot be null

*   defined in: [Priorisierung](notwendigkeitproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/NotwendigkeitProduktpaket.schema.json#/properties/notwendigkeitProduktpaket")

### notwendigkeitProduktpaket Type

`string` ([NotwendigkeitProduktpaket](notwendigkeitproduktpaket.md))

### notwendigkeitProduktpaket Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                | Explanation |
| :--------------------------------------------------- | :---------- |
| `"ZUORDNUNG_NUR_WENN_PRODUKTPAKET_UMSETZBAR"`        |             |
| `"ZUORDNUNG_AUCH_WENN_PRODUKTPAKET_NICHT_UMSETZBAR"` |             |

## priorisierungErforderlichesProduktpaket



`priorisierungErforderlichesProduktpaket`

*   is optional

*   Type: `string` ([PriorisierungErforderlichesProduktpaket](priorisierungerforderlichesproduktpaket.md))

*   cannot be null

*   defined in: [Priorisierung](priorisierungerforderlichesproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/PriorisierungErforderlichesProduktpaket.schema.json#/properties/priorisierungErforderlichesProduktpaket")

### priorisierungErforderlichesProduktpaket Type

`string` ([PriorisierungErforderlichesProduktpaket](priorisierungerforderlichesproduktpaket.md))

### priorisierungErforderlichesProduktpaket Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"PRIORITAET1"` |             |
| `"PRIORITAET2"` |             |
| `"PRIORITAET3"` |             |
| `"PRIORITAET4"` |             |
| `"PRIORITAET5"` |             |
