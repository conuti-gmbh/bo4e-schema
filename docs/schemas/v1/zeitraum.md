## Zeitraum Type

`object` ([Zeitraum](zeitraum.md))

# Zeitraum Properties

| Property                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                    |
| :------------------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [zeiteinheit](#zeiteinheit)                 | `string`  | Optional | cannot be null | [Zeitraum](zeiteinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeiteinheit.schema.json#/properties/zeiteinheit")                                 |
| [dauer](#dauer)                             | `integer` | Optional | cannot be null | [Zeitraum](zeitraum-properties-dauer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/dauer")                             |
| [startdatum](#startdatum)                   | `string`  | Optional | cannot be null | [Zeitraum](zeitraum-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/startdatum")                   |
| [enddatum](#enddatum)                       | `string`  | Optional | cannot be null | [Zeitraum](zeitraum-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/enddatum")                       |
| [einheit](#einheit)                         | `string`  | Optional | cannot be null | [Zeitraum](zeiteinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeiteinheit.schema.json#/properties/einheit")                                     |
| [ableseZeitraum](#ablesezeitraum)           | `string`  | Optional | cannot be null | [Zeitraum](zeitraum-properties-ablesezeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/ableseZeitraum")           |
| [abrechnungsZeitraum](#abrechnungszeitraum) | `string`  | Optional | cannot be null | [Zeitraum](zeitraum-properties-abrechnungszeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/abrechnungsZeitraum") |
| [zeitraumText](#zeitraumtext)               | `string`  | Optional | cannot be null | [Zeitraum](zeitraum-properties-zeitraumtext.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitraumText")               |
| [zeitraumId](#zeitraumid)                   | `integer` | Optional | cannot be null | [Zeitraum](zeitraum-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitraumId")                   |

## zeiteinheit



`zeiteinheit`

*   is optional

*   Type: `string` ([Zeiteinheit](zeiteinheit.md))

*   cannot be null

*   defined in: [Zeitraum](zeiteinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeiteinheit.schema.json#/properties/zeiteinheit")

### zeiteinheit Type

`string` ([Zeiteinheit](zeiteinheit.md))

### zeiteinheit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"SEKUNDE"`        |             |
| `"MINUTE"`         |             |
| `"STUNDE"`         |             |
| `"VIERTEL_STUNDE"` |             |
| `"TAG"`            |             |
| `"WOCHE"`          |             |
| `"MONAT"`          |             |
| `"QUARTAL"`        |             |
| `"HALBJAHR"`       |             |
| `"JAHR"`           |             |

## dauer



`dauer`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Zeitraum](zeitraum-properties-dauer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/dauer")

### dauer Type

`integer`

## startdatum



`startdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zeitraum](zeitraum-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/startdatum")

### startdatum Type

`string`

### startdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## enddatum



`enddatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zeitraum](zeitraum-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/enddatum")

### enddatum Type

`string`

### enddatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## einheit



`einheit`

*   is optional

*   Type: `string` ([Zeiteinheit](zeiteinheit.md))

*   cannot be null

*   defined in: [Zeitraum](zeiteinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeiteinheit.schema.json#/properties/einheit")

### einheit Type

`string` ([Zeiteinheit](zeiteinheit.md))

### einheit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"SEKUNDE"`        |             |
| `"MINUTE"`         |             |
| `"STUNDE"`         |             |
| `"VIERTEL_STUNDE"` |             |
| `"TAG"`            |             |
| `"WOCHE"`          |             |
| `"MONAT"`          |             |
| `"QUARTAL"`        |             |
| `"HALBJAHR"`       |             |
| `"JAHR"`           |             |

## ableseZeitraum



`ableseZeitraum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zeitraum](zeitraum-properties-ablesezeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/ableseZeitraum")

### ableseZeitraum Type

`string`

## abrechnungsZeitraum



`abrechnungsZeitraum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zeitraum](zeitraum-properties-abrechnungszeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/abrechnungsZeitraum")

### abrechnungsZeitraum Type

`string`

## zeitraumText



`zeitraumText`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zeitraum](zeitraum-properties-zeitraumtext.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitraumText")

### zeitraumText Type

`string`

## zeitraumId



`zeitraumId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Zeitraum](zeitraum-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitraumId")

### zeitraumId Type

`integer`
