## Untitled object in undefined Type

`object` ([Details](fehlerdetail.md))

# Untitled object in undefined Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                             |
| :---------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [code](#code)                 | `string` | Optional | cannot be null | [Untitled schema](fehlercode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/FehlerCode.schema.json#/properties/code")            |
| [ursache](#ursache)           | `object` | Optional | cannot be null | [Untitled schema](fehlerursache.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/FehlerUrsache.schema.json#/properties/ursache")    |
| [beschreibung](#beschreibung) | `object` | Optional | cannot be null | [Untitled schema](beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Beschreibung.schema.json#/properties/beschreibung") |

## code



`code`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](fehlercode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/FehlerCode.schema.json#/properties/code")

### code Type

`string`

### code Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                  | Explanation |
| :------------------------------------- | :---------- |
| `"ID_UNBEKANNT"`                       |             |
| `"ABSENDER_NICHT_ZUGEORDNET"`          |             |
| `"EMPFAENGER_NICHT_ZUGEORDNET"`        |             |
| `"GERAET_UNBEKANNT"`                   |             |
| `"OBIS_UNBEKANNT"`                     |             |
| `"REFERENZIERUNG_FEHLERHAFT"`          |             |
| `"TUPEL_UNBEKANNT"`                    |             |
| `"ABSENDER_TUPEL_NICHT_ZUGEORDNET"`    |             |
| `"EMPFAENGER_TUPEL_NICHT_ZUGEORDNET"`  |             |
| `"VORKOMMA_ZU_VIELE_STELLEN"`          |             |
| `"ZEITREIHE_UNVOLLSTAENDIG"`           |             |
| `"REFERENZIERTES_TUPEL_UNBEKANNT"`     |             |
| `"MARKTLOKATION_UNBEKANNT"`            |             |
| `"MESSLOKATION_UNBEKANNT"`             |             |
| `"MELDEPUNKT_NICHT_MEHR_IM_NETZ"`      |             |
| `"ERFORDERLICHE_ANGABE_FEHLT"`         |             |
| `"GESCHAEFTSVORFALL_ZURUECKGEWIESEN"`  |             |
| `"ZEITINTERVALL_NEGATIV"`              |             |
| `"FORMAT_NICHT_EINGEHALTEN"`           |             |
| `"GESCHAEFTSVORFALL_ABSENDER"`         |             |
| `"KONFIGURATIONSID_UNBEKANNT"`         |             |
| `"SEGMENTWIEDERHOLUNG_UEBERSCHRITTEN"` |             |
| `"ANZAHLCODES_UEBERSCHRITTEN"`         |             |
| `"ZEITANGABE_UNPLAUSIBEL"`             |             |
| `"CODE_NICHT_ERLAUBT"`                 |             |
| `"OBJEKT_NICHT_GEFUNDEN"`              |             |
| `"OBJEKT_NICHT_EINDEUTIG"`             |             |

## ursache



`ursache`

*   is optional

*   Type: `object` ([Details](fehlerursache.md))

*   cannot be null

*   defined in: [Untitled schema](fehlerursache.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/FehlerUrsache.schema.json#/properties/ursache")

### ursache Type

`object` ([Details](fehlerursache.md))

## beschreibung



`beschreibung`

*   is optional

*   Type: `object` ([Details](beschreibung.md))

*   cannot be null

*   defined in: [Untitled schema](beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Beschreibung.schema.json#/properties/beschreibung")

### beschreibung Type

`object` ([Details](beschreibung.md))
