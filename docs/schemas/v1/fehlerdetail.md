## FehlerDetail Type

`object` ([FehlerDetail](fehlerdetail.md))

# FehlerDetail Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                          |
| :---------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [code](#code)                 | `string` | Optional | cannot be null | [FehlerDetail](fehlercode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/FehlerCode.schema.json#/properties/code")            |
| [ursache](#ursache)           | `object` | Optional | cannot be null | [FehlerDetail](fehlerursache.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/FehlerUrsache.schema.json#/properties/ursache")    |
| [beschreibung](#beschreibung) | `object` | Optional | cannot be null | [FehlerDetail](beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Beschreibung.schema.json#/properties/beschreibung") |

## code

FehlerCode

`code`

*   is optional

*   Type: `string` ([FehlerCode](fehlercode.md))

*   cannot be null

*   defined in: [FehlerDetail](fehlercode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/FehlerCode.schema.json#/properties/code")

### code Type

`string` ([FehlerCode](fehlercode.md))

### code Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                        | Explanation |
| :--------------------------------------------------------------------------- | :---------- |
| `"ID_UNBEKANNT"`                                                             |             |
| `"ABSENDER_NICHT_ZUGEORDNET"`                                                |             |
| `"EMPFAENGER_NICHT_ZUGEORDNET"`                                              |             |
| `"GERAET_UNBEKANNT"`                                                         |             |
| `"OBIS_UNBEKANNT"`                                                           |             |
| `"REFERENZIERUNG_FEHLERHAFT"`                                                |             |
| `"TUPEL_UNBEKANNT"`                                                          |             |
| `"ABSENDER_TUPEL_NICHT_ZUGEORDNET"`                                          |             |
| `"EMPFAENGER_TUPEL_NICHT_ZUGEORDNET"`                                        |             |
| `"VORKOMMA_ZU_VIELE_STELLEN"`                                                |             |
| `"ZEITREIHE_UNVOLLSTAENDIG"`                                                 |             |
| `"REFERENZIERTES_TUPEL_UNBEKANNT"`                                           |             |
| `"MARKTLOKATION_UNBEKANNT"`                                                  |             |
| `"MESSLOKATION_UNBEKANNT"`                                                   |             |
| `"MELDEPUNKT_NICHT_MEHR_IM_NETZ"`                                            |             |
| `"ERFORDERLICHE_ANGABE_FEHLT"`                                               |             |
| `"GESCHAEFTSVORFALL_ZURUECKGEWIESEN"`                                        |             |
| `"ZEITINTERVALL_NEGATIV"`                                                    |             |
| `"FORMAT_NICHT_EINGEHALTEN"`                                                 |             |
| `"GESCHAEFTSVORFALL_ABSENDER"`                                               |             |
| `"KONFIGURATIONSID_UNBEKANNT"`                                               |             |
| `"SEGMENTWIEDERHOLUNG_UEBERSCHRITTEN"`                                       |             |
| `"ANZAHLCODES_UEBERSCHRITTEN"`                                               |             |
| `"ZEITANGABE_UNPLAUSIBEL"`                                                   |             |
| `"CODE_NICHT_ERLAUBT"`                                                       |             |
| `"OBJEKT_NICHT_GEFUNDEN"`                                                    |             |
| `"OBJEKT_NICHT_EINDEUTIG"`                                                   |             |
| `"GESCHAEFTSVORFALL_OBJEKT_EIGENSCHAFT_NICHT_ERLAUBT"`                       |             |
| `"EIGENSCHAFT_OBJEKT_WEICHT_VON_GESCHAEFTSVORFALL_CODIERTEN_EIGENSCHAFT_AB"` |             |

## ursache



`ursache`

*   is optional

*   Type: `object` ([FehlerUrsache](fehlerursache.md))

*   cannot be null

*   defined in: [FehlerDetail](fehlerursache.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/FehlerUrsache.schema.json#/properties/ursache")

### ursache Type

`object` ([FehlerUrsache](fehlerursache.md))

## beschreibung



`beschreibung`

*   is optional

*   Type: `object` ([Beschreibung](beschreibung.md))

*   cannot be null

*   defined in: [FehlerDetail](beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Beschreibung.schema.json#/properties/beschreibung")

### beschreibung Type

`object` ([Beschreibung](beschreibung.md))
