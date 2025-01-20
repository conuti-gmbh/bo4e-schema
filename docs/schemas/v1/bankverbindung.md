## Bankverbindung Type

`object` ([Bankverbindung](bankverbindung.md))

# Bankverbindung Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                     |
| :------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [verwendungszweck](#verwendungszweck) | `string` | Optional | cannot be null | [Bankverbindung](bankverbindungverwendungszweck.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BankverbindungVerwendungszweck.schema.json#/properties/verwendungszweck") |
| [iban](#iban)                         | `string` | Optional | cannot be null | [Bankverbindung](bankverbindung-properties-iban.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Bankverbindung.schema.json#/properties/iban")                              |
| [kontoinhaber](#kontoinhaber)         | `string` | Optional | cannot be null | [Bankverbindung](bankverbindung-properties-kontoinhaber.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Bankverbindung.schema.json#/properties/kontoinhaber")              |
| [bic](#bic)                           | `string` | Optional | cannot be null | [Bankverbindung](bankverbindung-properties-bic.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Bankverbindung.schema.json#/properties/bic")                                |
| [kreditinstitut](#kreditinstitut)     | `string` | Optional | cannot be null | [Bankverbindung](bankverbindung-properties-kreditinstitut.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Bankverbindung.schema.json#/properties/kreditinstitut")          |

## verwendungszweck

BankverbindungVerwendungszweck

`verwendungszweck`

*   is optional

*   Type: `string` ([BankverbindungVerwendungszweck](bankverbindungverwendungszweck.md))

*   cannot be null

*   defined in: [Bankverbindung](bankverbindungverwendungszweck.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BankverbindungVerwendungszweck.schema.json#/properties/verwendungszweck")

### verwendungszweck Type

`string` ([BankverbindungVerwendungszweck](bankverbindungverwendungszweck.md))

### verwendungszweck Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                 | Explanation |
| :------------------------------------ | :---------- |
| `"BV_ZAHLUNG_NNA"`                    |             |
| `"BV_ZAHLUNG_MMMA"`                   |             |
| `"BV_ZAHLUNG_MSB_ABRECHNNUNG"`        |             |
| `"BV_ZAHLUNG_ENT_SPERREN_ABRECHNUNG"` |             |
| `"BV_SONSTIGE"`                       |             |

## iban

IBAN

`iban`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bankverbindung](bankverbindung-properties-iban.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Bankverbindung.schema.json#/properties/iban")

### iban Type

`string`

## kontoinhaber

Der Kontoinhaber

`kontoinhaber`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bankverbindung](bankverbindung-properties-kontoinhaber.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Bankverbindung.schema.json#/properties/kontoinhaber")

### kontoinhaber Type

`string`

## bic

BIC Code

`bic`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bankverbindung](bankverbindung-properties-bic.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Bankverbindung.schema.json#/properties/bic")

### bic Type

`string`

## kreditinstitut

Name des Kreditinstitut

`kreditinstitut`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bankverbindung](bankverbindung-properties-kreditinstitut.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Bankverbindung.schema.json#/properties/kreditinstitut")

### kreditinstitut Type

`string`
