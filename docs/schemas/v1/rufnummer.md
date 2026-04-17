## Rufnummer Type

`object` ([Rufnummer](rufnummer.md))

# Rufnummer Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                   |
| :------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [nummerntyp](#nummerntyp) | `string` | Optional | cannot be null | [Rufnummer](rufnummernart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Rufnummernart.schema.json#/properties/nummerntyp")            |
| [rufnummer](#rufnummer)   | `string` | Optional | cannot be null | [Rufnummer](rufnummer-properties-rufnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rufnummer.schema.json#/properties/rufnummer") |

## nummerntyp

Rufnummernart

`nummerntyp`

*   is optional

*   Type: `string` ([Rufnummernart](rufnummernart.md))

*   cannot be null

*   defined in: [Rufnummer](rufnummernart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Rufnummernart.schema.json#/properties/nummerntyp")

### nummerntyp Type

`string` ([Rufnummernart](rufnummernart.md))

### nummerntyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"RUF_ZENTRALE"`  |             |
| `"FAX_ZENTRALE"`  |             |
| `"SAMMELRUF"`     |             |
| `"SAMMELFAX"`     |             |
| `"ABTEILUNGRUF"`  |             |
| `"ABTEILUNGFAX"`  |             |
| `"RUF_DURCHWAHL"` |             |
| `"FAX_DURCHWAHL"` |             |
| `"MOBIL_NUMMER"`  |             |

## rufnummer

rufnummer

`rufnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rufnummer](rufnummer-properties-rufnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rufnummer.schema.json#/properties/rufnummer")

### rufnummer Type

`string`
