## ZeitintervallMenge Type

`object` ([ZeitintervallMenge](zeitintervallmenge.md))

# ZeitintervallMenge Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [verwendungAb](#verwendungab)   | `string` | Optional | cannot be null | [ZeitintervallMenge](zeitintervallmenge-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZeitintervallMenge.schema.json#/properties/verwendungAb")   |
| [verwendungBis](#verwendungbis) | `string` | Optional | cannot be null | [ZeitintervallMenge](zeitintervallmenge-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZeitintervallMenge.schema.json#/properties/verwendungBis") |
| [menge](#menge)                 | `object` | Optional | cannot be null | [ZeitintervallMenge](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/menge")                                                            |

## verwendungAb

verwendungAb

`verwendungAb`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [ZeitintervallMenge](zeitintervallmenge-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZeitintervallMenge.schema.json#/properties/verwendungAb")

### verwendungAb Type

`string`

### verwendungAb Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## verwendungBis

verwendungBis

`verwendungBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [ZeitintervallMenge](zeitintervallmenge-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZeitintervallMenge.schema.json#/properties/verwendungBis")

### verwendungBis Type

`string`

### verwendungBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## menge



`menge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [ZeitintervallMenge](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/menge")

### menge Type

`object` ([Menge](menge.md))
