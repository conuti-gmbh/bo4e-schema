## MarktlokationsReferenz Type

`object` ([MarktlokationsReferenz](marktlokationsreferenz.md))

# MarktlokationsReferenz Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :------------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [marktlokationsId](#marktlokationsid) | `string` | Optional | cannot be null | [MarktlokationsReferenz](marktlokationsreferenz-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/MarktlokationsReferenz.schema.json#/properties/marktlokationsId") |
| [typ](#typ)                           | `string` | Optional | cannot be null | [MarktlokationsReferenz](marktlokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MarktlokationsTyp.schema.json#/properties/typ")                                                   |

## marktlokationsId

Identifikationsnummer einer Marktlokation

`marktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [MarktlokationsReferenz](marktlokationsreferenz-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/MarktlokationsReferenz.schema.json#/properties/marktlokationsId")

### marktlokationsId Type

`string`

## typ

MarktlokationsTyp

`typ`

*   is optional

*   Type: `string` ([MarktlokationsTyp](marktlokationstyp.md))

*   cannot be null

*   defined in: [MarktlokationsReferenz](marktlokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MarktlokationsTyp.schema.json#/properties/typ")

### typ Type

`string` ([MarktlokationsTyp](marktlokationstyp.md))

### typ Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"STANDARD_MARKTLOKATION"` |             |
| `"RUHENDE_MARKTLOKATION"`  |             |
| `"KUNDENANLAGE"`           |             |
