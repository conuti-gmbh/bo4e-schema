## Verbrauch Type

`object` ([Verbrauch](verbrauch.md))

# Verbrauch Properties

| Property                                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                   |
| :------------------------------------------------------ | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [startdatum](#startdatum)                               | `string`  | Optional | cannot be null | [Verbrauch](verbrauch-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/startdatum")                               |
| [enddatum](#enddatum)                                   | `string`  | Optional | cannot be null | [Verbrauch](verbrauch-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/enddatum")                                   |
| [wertermittlungsverfahren](#wertermittlungsverfahren)   | `string`  | Optional | cannot be null | [Verbrauch](wertermittlungsverfahren.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Wertermittlungsverfahren.schema.json#/properties/wertermittlungsverfahren")        |
| [messwertstatus](#messwertstatus)                       | `string`  | Optional | cannot be null | [Verbrauch](messwertstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Messwertstatus.schema.json#/properties/messwertstatus")                                      |
| [obiskennzahl](#obiskennzahl)                           | `string`  | Optional | cannot be null | [Verbrauch](verbrauch-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/obiskennzahl")                           |
| [wert](#wert)                                           | `number`  | Optional | cannot be null | [Verbrauch](verbrauch-properties-wert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/wert")                                           |
| [einheit](#einheit)                                     | `string`  | Optional | cannot be null | [Verbrauch](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/einheit")                                               |
| [type](#type)                                           | `string`  | Optional | cannot be null | [Verbrauch](verbrauchsmengetyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsmengetyp.schema.json#/properties/type")                                        |
| [tarifstufe](#tarifstufe)                               | `string`  | Optional | cannot be null | [Verbrauch](tarifstufe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tarifstufe.schema.json#/properties/tarifstufe")                                                  |
| [nutzungszeitpunkt](#nutzungszeitpunkt)                 | `string`  | Optional | cannot be null | [Verbrauch](verbrauch-properties-nutzungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/nutzungszeitpunkt")                 |
| [ausfuehrungszeitpunkt](#ausfuehrungszeitpunkt)         | `string`  | Optional | cannot be null | [Verbrauch](verbrauch-properties-ausfuehrungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/ausfuehrungszeitpunkt")         |
| [position](#position)                                   | `integer` | Optional | cannot be null | [Verbrauch](verbrauch-properties-position.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/position")                                   |
| [ablesedatum](#ablesedatum)                             | `string`  | Optional | cannot be null | [Verbrauch](verbrauch-properties-ablesedatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/ablesedatum")                             |
| [leistungsperiode](#leistungsperiode)                   | `string`  | Optional | cannot be null | [Verbrauch](verbrauch-properties-leistungsperiode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/leistungsperiode")                   |
| [statuszusatzinformationen](#statuszusatzinformationen) | `array`   | Optional | can be null    | [Verbrauch](verbrauch-properties-statuszusatzinformationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/statuszusatzinformationen") |

## startdatum

startdatum

`startdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/startdatum")

### startdatum Type

`string`

### startdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## enddatum

enddatum

`enddatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/enddatum")

### enddatum Type

`string`

### enddatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## wertermittlungsverfahren

Wertermittlungsverfahren

`wertermittlungsverfahren`

*   is optional

*   Type: `string` ([Wertermittlungsverfahren](wertermittlungsverfahren.md))

*   cannot be null

*   defined in: [Verbrauch](wertermittlungsverfahren.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Wertermittlungsverfahren.schema.json#/properties/wertermittlungsverfahren")

### wertermittlungsverfahren Type

`string` ([Wertermittlungsverfahren](wertermittlungsverfahren.md))

### wertermittlungsverfahren Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"PROGNOSE"` |             |
| `"MESSUNG"`  |             |

## messwertstatus

Der Status eines Zählerstandes

`messwertstatus`

*   is optional

*   Type: `string` ([Messwertstatus](messwertstatus.md))

*   cannot be null

*   defined in: [Verbrauch](messwertstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Messwertstatus.schema.json#/properties/messwertstatus")

### messwertstatus Type

`string` ([Messwertstatus](messwertstatus.md))

### messwertstatus Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                        | Explanation |
| :--------------------------- | :---------- |
| `"ABGELESEN"`                |             |
| `"ERSATZWERT"`               |             |
| `"VORSCHLAGSWERT"`           |             |
| `"NICHT_VERWENDBAR"`         |             |
| `"PROGNOSEWERT"`             |             |
| `"ENERGIEMENGESUMMIERT"`     |             |
| `"VOLAEUFIGERWERT"`          |             |
| `"FEHLT"`                    |             |
| `"ANGABE_FUER_LIEFERSCHEIN"` |             |
| `"GRUNDLAGE_POG_ERMITTLUNG"` |             |

## obiskennzahl

obiskennzahl

`obiskennzahl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/obiskennzahl")

### obiskennzahl Type

`string`

## wert

wert

`wert`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-wert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/wert")

### wert Type

`number`

### wert Constraints

**unknown format**: the value of this string must follow the format: `float`

## einheit

Einheit: Messgrößen, die per Messung oder Vorgabe ermittelt werden können

`einheit`

*   is optional

*   Type: `string` ([Mengeneinheit](mengeneinheit.md))

*   cannot be null

*   defined in: [Verbrauch](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/einheit")

### einheit Type

`string` ([Mengeneinheit](mengeneinheit.md))

### einheit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"W"`          |             |
| `"WH"`         |             |
| `"KW"`         |             |
| `"KWH"`        |             |
| `"KVARH"`      |             |
| `"MW"`         |             |
| `"MWH"`        |             |
| `"STUECK"`     |             |
| `"KUBIKMETER"` |             |
| `"STUNDE"`     |             |
| `"TAG"`        |             |
| `"MONAT"`      |             |
| `"JAHR"`       |             |
| `"PROZENT"`    |             |
| `"ANZAHL"`     |             |
| `"VAR"`        |             |
| `"KVAR"`       |             |
| `"VARH"`       |             |
| `"KWHK"`       |             |
| `"Z16"`        |             |
| `"KWT"`        |             |

## type

Verbrauchsmengetyp

`type`

*   is optional

*   Type: `string` ([Verbrauchsmengetyp](verbrauchsmengetyp.md))

*   cannot be null

*   defined in: [Verbrauch](verbrauchsmengetyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsmengetyp.schema.json#/properties/type")

### type Type

`string` ([Verbrauchsmengetyp](verbrauchsmengetyp.md))

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                   | Explanation |
| :-------------------------------------- | :---------- |
| `"ARBEITLEISTUNGTAGESPARAMETERABHMALO"` |             |
| `"VERANSCHLAGTEJAHRESMENGE"`            |             |
| `"TUMKUNDENWERT"`                       |             |

## tarifstufe

Tarifstufe

`tarifstufe`

*   is optional

*   Type: `string` ([Tarifstufe](tarifstufe.md))

*   cannot be null

*   defined in: [Verbrauch](tarifstufe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tarifstufe.schema.json#/properties/tarifstufe")

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

## nutzungszeitpunkt

nutzungszeitpunkt

`nutzungszeitpunkt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-nutzungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/nutzungszeitpunkt")

### nutzungszeitpunkt Type

`string`

### nutzungszeitpunkt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## ausfuehrungszeitpunkt

ausfuehrungszeitpunkt

`ausfuehrungszeitpunkt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-ausfuehrungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/ausfuehrungszeitpunkt")

### ausfuehrungszeitpunkt Type

`string`

### ausfuehrungszeitpunkt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## position

position

`position`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-position.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/position")

### position Type

`integer`

## ablesedatum

ablesedatum

`ablesedatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-ablesedatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/ablesedatum")

### ablesedatum Type

`string`

### ablesedatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## leistungsperiode

leistungsperiode

`leistungsperiode`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verbrauch](verbrauch-properties-leistungsperiode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/leistungsperiode")

### leistungsperiode Type

`string`

## statuszusatzinformationen

statuszusatzinformationen

`statuszusatzinformationen`

*   is optional

*   Type: `object[]` ([StatusZusatzInformation](statuszusatzinformation.md))

*   can be null

*   defined in: [Verbrauch](verbrauch-properties-statuszusatzinformationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/statuszusatzinformationen")

### statuszusatzinformationen Type

`object[]` ([StatusZusatzInformation](statuszusatzinformation.md))
