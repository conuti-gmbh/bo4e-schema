## Produktpaket Type

`object` ([Produktpaket](produktpaket.md))

# Produktpaket Properties

| Property                                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                      |
| :---------------------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [produktpaketId](#produktpaketid)               | `integer` | Optional | cannot be null | [Produktpaket](produktpaket-properties-produktpaketid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Produktpaket.schema.json#/properties/produktpaketId") |
| [produkt](#produkt)                             | `array`   | Optional | cannot be null | [Produktpaket](produktpaket-properties-produkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Produktpaket.schema.json#/properties/produkt")               |
| [umsetzungsgradvorgabe](#umsetzungsgradvorgabe) | `string`  | Optional | cannot be null | [Produktpaket](umsetzungsgradvorgabe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Umsetzungsgradvorgabe.schema.json#/properties/umsetzungsgradvorgabe") |
| [priorisierung](#priorisierung)                 | `string`  | Optional | cannot be null | [Produktpaket](priorisierung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Priorisierung.schema.json#/properties/priorisierung")                         |

## produktpaketId



`produktpaketId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Produktpaket](produktpaket-properties-produktpaketid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Produktpaket.schema.json#/properties/produktpaketId")

### produktpaketId Type

`integer`

## produkt



`produkt`

*   is optional

*   Type: `object[]` ([Produkt](produkt.md))

*   cannot be null

*   defined in: [Produktpaket](produktpaket-properties-produkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Produktpaket.schema.json#/properties/produkt")

### produkt Type

`object[]` ([Produkt](produkt.md))

## umsetzungsgradvorgabe



`umsetzungsgradvorgabe`

*   is optional

*   Type: `string` ([Umsetzungsgradvorgabe](umsetzungsgradvorgabe.md))

*   cannot be null

*   defined in: [Produktpaket](umsetzungsgradvorgabe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Umsetzungsgradvorgabe.schema.json#/properties/umsetzungsgradvorgabe")

### umsetzungsgradvorgabe Type

`string` ([Umsetzungsgradvorgabe](umsetzungsgradvorgabe.md))

### umsetzungsgradvorgabe Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                | Explanation |
| :--------------------------------------------------- | :---------- |
| `"ZUORDNUNG_NUR_WENN_PRODUKTPAKET_UMSETZBAR"`        |             |
| `"ZUORDNUNG_AUCH_WENN_PRODUKTPAKET_NICHT_UMSETZBAR"` |             |

## priorisierung



`priorisierung`

*   is optional

*   Type: `string` ([Priorisierung](priorisierung.md))

*   cannot be null

*   defined in: [Produktpaket](priorisierung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Priorisierung.schema.json#/properties/priorisierung")

### priorisierung Type

`string` ([Priorisierung](priorisierung.md))

### priorisierung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"PRIORITAET1"` |             |
| `"PRIORITAET2"` |             |
| `"PRIORITAET3"` |             |
| `"PRIORITAET4"` |             |
| `"PRIORITAET5"` |             |
