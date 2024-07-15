## Schaltzeit Type

`object` ([Schaltzeit](schaltzeit.md))

# Schaltzeit Properties

| Property                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                  |
| :---------------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [code](#code)                                   | `string` | Optional | cannot be null | [Schaltzeit](schaltzeit-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/code")                                   |
| [aenderungszeitpunkt](#aenderungszeitpunkt)     | `string` | Optional | cannot be null | [Schaltzeit](schaltzeit-properties-aenderungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/aenderungszeitpunkt")     |
| [haeufigkeit](#haeufigkeit)                     | `string` | Optional | cannot be null | [Schaltzeit](haeufigkeitschaltzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/HaeufigkeitSchaltzeit.schema.json#/properties/haeufigkeit")                         |
| [uebermittelbarkeit](#uebermittelbarkeit)       | `string` | Optional | cannot be null | [Schaltzeit](uebermittelbarkeitschaltzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/UebermittelbarkeitSchaltzeit.schema.json#/properties/uebermittelbarkeit")    |
| [schalthandlung](#schalthandlung)               | `string` | Optional | cannot be null | [Schaltzeit](schalthandlung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Schalthandlung.schema.json#/properties/schalthandlung")                                    |
| [konfigurationsprodukt](#konfigurationsprodukt) | `string` | Optional | cannot be null | [Schaltzeit](schaltzeit-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/konfigurationsprodukt") |

## code



`code`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Schaltzeit](schaltzeit-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/code")

### code Type

`string`

## aenderungszeitpunkt



`aenderungszeitpunkt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Schaltzeit](schaltzeit-properties-aenderungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/aenderungszeitpunkt")

### aenderungszeitpunkt Type

`string`

### aenderungszeitpunkt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## haeufigkeit



`haeufigkeit`

*   is optional

*   Type: `string` ([HaeufigkeitSchaltzeit](haeufigkeitschaltzeit.md))

*   cannot be null

*   defined in: [Schaltzeit](haeufigkeitschaltzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/HaeufigkeitSchaltzeit.schema.json#/properties/haeufigkeit")

### haeufigkeit Type

`string` ([HaeufigkeitSchaltzeit](haeufigkeitschaltzeit.md))

### haeufigkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"EINMALIG"`  |             |
| `"JAEHRLICH"` |             |

## uebermittelbarkeit



`uebermittelbarkeit`

*   is optional

*   Type: `string` ([UebermittelbarkeitSchaltzeit](uebermittelbarkeitschaltzeit.md))

*   cannot be null

*   defined in: [Schaltzeit](uebermittelbarkeitschaltzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/UebermittelbarkeitSchaltzeit.schema.json#/properties/uebermittelbarkeit")

### uebermittelbarkeit Type

`string` ([UebermittelbarkeitSchaltzeit](uebermittelbarkeitschaltzeit.md))

### uebermittelbarkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                  | Explanation |
| :--------------------- | :---------- |
| `"ELEKTRONISCH"`       |             |
| `"NICHT_ELEKTRONISCH"` |             |

## schalthandlung



`schalthandlung`

*   is optional

*   Type: `string` ([Schalthandlung](schalthandlung.md))

*   cannot be null

*   defined in: [Schaltzeit](schalthandlung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Schalthandlung.schema.json#/properties/schalthandlung")

### schalthandlung Type

`string` ([Schalthandlung](schalthandlung.md))

### schalthandlung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"LEISTUNG_AN"`  |             |
| `"LEISTUNG_AUS"` |             |

## konfigurationsprodukt



`konfigurationsprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Schaltzeit](schaltzeit-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/konfigurationsprodukt")

### konfigurationsprodukt Type

`string`
