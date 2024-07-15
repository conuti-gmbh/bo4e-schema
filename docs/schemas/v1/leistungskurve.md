## Leistungskurve Type

`object` ([Leistungskurve](leistungskurve.md))

# Leistungskurve Properties

| Property                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                           |
| :---------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [code](#code)                                   | `string` | Optional | cannot be null | [Leistungskurve](leistungskurve-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/code")                                    |
| [aenderungszeitpunkt](#aenderungszeitpunkt)     | `string` | Optional | cannot be null | [Leistungskurve](leistungskurve-properties-aenderungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/aenderungszeitpunkt")      |
| [haeufigkeit](#haeufigkeit)                     | `string` | Optional | cannot be null | [Leistungskurve](haeufigkeitleistungskurve.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/HaeufigkeitLeistungskurve.schema.json#/properties/haeufigkeit")                      |
| [uebermittelbarkeit](#uebermittelbarkeit)       | `string` | Optional | cannot be null | [Leistungskurve](uebermittelbarkeitleistungskurve.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/UebermittelbarkeitLeistungskurve.schema.json#/properties/uebermittelbarkeit") |
| [schwellwert](#schwellwert)                     | `object` | Optional | cannot be null | [Leistungskurve](schwellwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Schwellwert.schema.json#/properties/schwellwert")                                                   |
| [konfigurationsprodukt](#konfigurationsprodukt) | `string` | Optional | cannot be null | [Leistungskurve](leistungskurve-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/konfigurationsprodukt")  |

## code



`code`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Leistungskurve](leistungskurve-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/code")

### code Type

`string`

## aenderungszeitpunkt



`aenderungszeitpunkt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Leistungskurve](leistungskurve-properties-aenderungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/aenderungszeitpunkt")

### aenderungszeitpunkt Type

`string`

### aenderungszeitpunkt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## haeufigkeit



`haeufigkeit`

*   is optional

*   Type: `string` ([HaeufigkeitLeistungskurve](haeufigkeitleistungskurve.md))

*   cannot be null

*   defined in: [Leistungskurve](haeufigkeitleistungskurve.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/HaeufigkeitLeistungskurve.schema.json#/properties/haeufigkeit")

### haeufigkeit Type

`string` ([HaeufigkeitLeistungskurve](haeufigkeitleistungskurve.md))

### haeufigkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"EINMALIG"`  |             |
| `"JAEHRLICH"` |             |

## uebermittelbarkeit



`uebermittelbarkeit`

*   is optional

*   Type: `string` ([UebermittelbarkeitLeistungskurve](uebermittelbarkeitleistungskurve.md))

*   cannot be null

*   defined in: [Leistungskurve](uebermittelbarkeitleistungskurve.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/UebermittelbarkeitLeistungskurve.schema.json#/properties/uebermittelbarkeit")

### uebermittelbarkeit Type

`string` ([UebermittelbarkeitLeistungskurve](uebermittelbarkeitleistungskurve.md))

### uebermittelbarkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                  | Explanation |
| :--------------------- | :---------- |
| `"ELEKTRONISCH"`       |             |
| `"NICHT_ELEKTRONISCH"` |             |

## schwellwert



`schwellwert`

*   is optional

*   Type: `object` ([Schwellwert](schwellwert.md))

*   cannot be null

*   defined in: [Leistungskurve](schwellwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Schwellwert.schema.json#/properties/schwellwert")

### schwellwert Type

`object` ([Schwellwert](schwellwert.md))

## konfigurationsprodukt



`konfigurationsprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Leistungskurve](leistungskurve-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Leistungskurve.schema.json#/properties/konfigurationsprodukt")

### konfigurationsprodukt Type

`string`
