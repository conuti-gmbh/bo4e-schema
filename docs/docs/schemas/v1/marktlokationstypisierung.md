## MarktlokationsTypisierung Type

`object` ([MarktlokationsTypisierung](marktlokationstypisierung.md))

# MarktlokationsTypisierung Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                     |
| :------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [typ](#typ)               | `string` | Optional | cannot be null | [MarktlokationsTypisierung](marktlokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MarktlokationsTyp.schema.json#/properties/typ")                                             |
| [gueltigAb](#gueltigab)   | `string` | Optional | cannot be null | [MarktlokationsTypisierung](marktlokationstypisierung-properties-gueltigab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/MarktlokationsTypisierung.schema.json#/properties/gueltigAb")   |
| [gueltigBis](#gueltigbis) | `string` | Optional | cannot be null | [MarktlokationsTypisierung](marktlokationstypisierung-properties-gueltigbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/MarktlokationsTypisierung.schema.json#/properties/gueltigBis") |

## typ

AbgabeArt

`typ`

*   is optional

*   Type: `string` ([AbgabeArt](marktlokationstyp.md))

*   cannot be null

*   defined in: [MarktlokationsTypisierung](marktlokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MarktlokationsTyp.schema.json#/properties/typ")

### typ Type

`string` ([AbgabeArt](marktlokationstyp.md))

### typ Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"STANDARD_MARKTLOKATION"` |             |
| `"RUHENDE_MARKTLOKATION"`  |             |
| `"KUNDENANLAGE"`           |             |

## gueltigAb

Startdatum der Typisierung der Marktlokation

`gueltigAb`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [MarktlokationsTypisierung](marktlokationstypisierung-properties-gueltigab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/MarktlokationsTypisierung.schema.json#/properties/gueltigAb")

### gueltigAb Type

`string`

### gueltigAb Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## gueltigBis

Enddatum der Typisierung der Marktlokation

`gueltigBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [MarktlokationsTypisierung](marktlokationstypisierung-properties-gueltigbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/MarktlokationsTypisierung.schema.json#/properties/gueltigBis")

### gueltigBis Type

`string`

### gueltigBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
