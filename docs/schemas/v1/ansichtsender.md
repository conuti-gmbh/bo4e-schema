## AnsichtSender Type

`object` ([AnsichtSender](ansichtsender.md))

# AnsichtSender Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                             |
| :------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [verwendungAb](#verwendungab)         | `string` | Optional | cannot be null | [AnsichtSender](ansichtsender-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AnsichtSender.schema.json#/properties/verwendungAb")         |
| [verwendungBis](#verwendungbis)       | `string` | Optional | cannot be null | [AnsichtSender](ansichtsender-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AnsichtSender.schema.json#/properties/verwendungBis")       |
| [leistungsperiode](#leistungsperiode) | `string` | Optional | cannot be null | [AnsichtSender](ansichtsender-properties-leistungsperiode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AnsichtSender.schema.json#/properties/leistungsperiode") |
| [menge](#menge)                       | `object` | Optional | cannot be null | [AnsichtSender](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/menge")                                                        |
| [tarifstufe](#tarifstufe)             | `string` | Optional | cannot be null | [AnsichtSender](tarifstufe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tarifstufe.schema.json#/properties/tarifstufe")                                        |

## verwendungAb

verwendungAb

`verwendungAb`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AnsichtSender](ansichtsender-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AnsichtSender.schema.json#/properties/verwendungAb")

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

*   defined in: [AnsichtSender](ansichtsender-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AnsichtSender.schema.json#/properties/verwendungBis")

### verwendungBis Type

`string`

### verwendungBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## leistungsperiode

leistungsperiode

`leistungsperiode`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AnsichtSender](ansichtsender-properties-leistungsperiode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AnsichtSender.schema.json#/properties/leistungsperiode")

### leistungsperiode Type

`string`

## menge



`menge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [AnsichtSender](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/menge")

### menge Type

`object` ([Menge](menge.md))

## tarifstufe

Tarifstufe

`tarifstufe`

*   is optional

*   Type: `string` ([Tarifstufe](tarifstufe.md))

*   cannot be null

*   defined in: [AnsichtSender](tarifstufe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tarifstufe.schema.json#/properties/tarifstufe")

### tarifstufe Type

`string` ([Tarifstufe](tarifstufe.md))

### tarifstufe Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"TARIFSTUFE_0"` |             |
| `"TARIFSTUFE_1"` |             |
| `"TARIFSTUFE_2"` |             |
| `"TARIFSTUFE_3"` |             |
| `"TARIFSTUFE_4"` |             |
| `"TARIFSTUFE_5"` |             |
| `"TARIFSTUFE_6"` |             |
| `"TARIFSTUFE_7"` |             |
| `"TARIFSTUFE_8"` |             |
| `"TARIFSTUFE_9"` |             |
