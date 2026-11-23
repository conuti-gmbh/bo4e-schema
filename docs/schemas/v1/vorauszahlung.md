## Vorauszahlung Type

`object` ([Vorauszahlung](vorauszahlung.md))

# Vorauszahlung Properties

| Property                                                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                 |
| :-------------------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [wert](#wert)                                             | `number` | Optional | cannot be null | [Vorauszahlung](vorauszahlung-properties-wert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vorauszahlung.schema.json#/properties/wert")                                             |
| [waehrung](#waehrung)                                     | `string` | Optional | cannot be null | [Vorauszahlung](waehrungseinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waehrungseinheit.schema.json#/properties/waehrung")                                                  |
| [referenzVorgaengerrechnung](#referenzvorgaengerrechnung) | `string` | Optional | cannot be null | [Vorauszahlung](vorauszahlung-properties-referenzvorgaengerrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vorauszahlung.schema.json#/properties/referenzVorgaengerrechnung") |
| [datumVorgaengerrechnung](#datumvorgaengerrechnung)       | `string` | Optional | cannot be null | [Vorauszahlung](vorauszahlung-properties-datumvorgaengerrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vorauszahlung.schema.json#/properties/datumVorgaengerrechnung")       |

## wert

Gibt den Betrag der Vorauszahlung an.

`wert`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Vorauszahlung](vorauszahlung-properties-wert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vorauszahlung.schema.json#/properties/wert")

### wert Type

`number`

### wert Constraints

**unknown format**: the value of this string must follow the format: `float`

## waehrung

Waehrungseinheit

`waehrung`

*   is optional

*   Type: `string` ([Waehrungseinheit](waehrungseinheit.md))

*   cannot be null

*   defined in: [Vorauszahlung](waehrungseinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waehrungseinheit.schema.json#/properties/waehrung")

### waehrung Type

`string` ([Waehrungseinheit](waehrungseinheit.md))

### waehrung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"EUR"` |             |
| `"CT"`  |             |

## referenzVorgaengerrechnung

Referenz auf die Vorgängerrechnung der Vorauszahlung

`referenzVorgaengerrechnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vorauszahlung](vorauszahlung-properties-referenzvorgaengerrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vorauszahlung.schema.json#/properties/referenzVorgaengerrechnung")

### referenzVorgaengerrechnung Type

`string`

## datumVorgaengerrechnung

Datum der Vorgängerrechnung der Vorauszahlung

`datumVorgaengerrechnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vorauszahlung](vorauszahlung-properties-datumvorgaengerrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vorauszahlung.schema.json#/properties/datumVorgaengerrechnung")

### datumVorgaengerrechnung Type

`string`

### datumVorgaengerrechnung Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
