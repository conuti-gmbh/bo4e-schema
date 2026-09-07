## Summenzeitreihe Type

`object` ([Summenzeitreihe](summenzeitreihe.md))

# Summenzeitreihe Properties

| Property                                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                        |
| :------------------------------------------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                         | `string` | Required | cannot be null | [Summenzeitreihe](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                |
| [versionStruktur](#versionstruktur)                     | `string` | Required | cannot be null | [Summenzeitreihe](summenzeitreihe-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/versionStruktur")         |
| [zaehlpunktId](#zaehlpunktid)                           | `string` | Optional | cannot be null | [Summenzeitreihe](summenzeitreihe-properties-zaehlpunktid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/zaehlpunktId")               |
| [versionZeitreihe](#versionzeitreihe)                   | `string` | Optional | cannot be null | [Summenzeitreihe](summenzeitreihe-properties-versionzeitreihe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/versionZeitreihe")       |
| [bilanzkreis](#bilanzkreis)                             | `string` | Optional | cannot be null | [Summenzeitreihe](summenzeitreihe-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/bilanzkreis")                 |
| [bilanzkreisAn](#bilanzkreisan)                         | `string` | Optional | cannot be null | [Summenzeitreihe](summenzeitreihe-properties-bilanzkreisan.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/bilanzkreisAn")             |
| [bilanzkreisVon](#bilanzkreisvon)                       | `string` | Optional | cannot be null | [Summenzeitreihe](summenzeitreihe-properties-bilanzkreisvon.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/bilanzkreisVon")           |
| [bilanzierteEnergiemenge](#bilanzierteenergiemenge)     | `object` | Optional | cannot be null | [Summenzeitreihe](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/bilanzierteEnergiemenge")                                               |
| [bilanzierteAusfallmenge](#bilanzierteausfallmenge)     | `object` | Optional | cannot be null | [Summenzeitreihe](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/bilanzierteAusfallmenge")                                               |
| [bilanzierungsgebiet](#bilanzierungsgebiet)             | `array`  | Optional | can be null    | [Summenzeitreihe](summenzeitreihe-properties-bilanzierungsgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/bilanzierungsgebiet") |
| [bezeichnung](#bezeichnung)                             | `string` | Optional | cannot be null | [Summenzeitreihe](bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bezeichnung.schema.json#/properties/bezeichnung")                                              |
| [verantwortlicheMarktrolle](#verantwortlichemarktrolle) | `string` | Optional | cannot be null | [Summenzeitreihe](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/verantwortlicheMarktrolle")                                  |
| [regelzone](#regelzone)                                 | `string` | Optional | cannot be null | [Summenzeitreihe](summenzeitreihe-properties-regelzone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/regelzone")                     |
| [zeitreihentyp](#zeitreihentyp)                         | `string` | Optional | cannot be null | [Summenzeitreihe](zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeitreihentyp.schema.json#/properties/zeitreihentyp")                                        |
| [bezugszeitraum](#bezugszeitraum)                       | `string` | Optional | cannot be null | [Summenzeitreihe](bezugszeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bezugszeitraum.schema.json#/properties/bezugszeitraum")                                     |
| [netzebene](#netzebene)                                 | `string` | Optional | cannot be null | [Summenzeitreihe](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/netzebene")                                                    |
| [umspannung](#umspannung)                               | `string` | Optional | cannot be null | [Summenzeitreihe](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/umspannung")                                                   |
| [datenstatusZeitreihe](#datenstatuszeitreihe)           | `string` | Optional | cannot be null | [Summenzeitreihe](datenstatuszeitreihe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DatenstatusZeitreihe.schema.json#/properties/datenstatusZeitreihe")                   |
| [zuordnungsregel](#zuordnungsregel)                     | `string` | Optional | cannot be null | [Summenzeitreihe](zuordnungsregel.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zuordnungsregel.schema.json#/properties/zuordnungsregel")                                  |
| [zeitreihenprodukt](#zeitreihenprodukt)                 | `array`  | Optional | can be null    | [Summenzeitreihe](summenzeitreihe-properties-zeitreihenprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/zeitreihenprodukt")     |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Summenzeitreihe](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

### boTyp Type

`string` ([BOTyp](botyp.md))

### boTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                           | Explanation |
| :------------------------------ | :---------- |
| `"ANSPRECHPARTNER"`             |             |
| `"AVIS"`                        |             |
| `"ENERGIEMENGE"`                |             |
| `"GESCHAEFTSOBJEKT"`            |             |
| `"GESCHAEFTSPARTNER"`           |             |
| `"MARKTLOKATION"`               |             |
| `"MARKTTEILNEHMER"`             |             |
| `"MESSLOKATION"`                |             |
| `"ZAEHLER"`                     |             |
| `"KOSTEN"`                      |             |
| `"TARIF"`                       |             |
| `"PREISBLATT"`                  |             |
| `"PREISBLATTNETZNUTZUNG"`       |             |
| `"PREISBLATTMESSUNG"`           |             |
| `"PREISBLATTUMLAGEN"`           |             |
| `"PREISBLATTDIENSTLEISTUNG"`    |             |
| `"PREISBLATTKONZESSIONSABGABE"` |             |
| `"ZEITREIHE"`                   |             |
| `"LASTGANG"`                    |             |
| `"HANDELSUNSTIMMIGKEIT"`        |             |
| `"ANFRAGE"`                     |             |
| `"AUFTRAG"`                     |             |
| `"STATUSMITTEILUNG"`            |             |
| `"BERECHNUNGSFORMEL"`           |             |
| `"RECHNUNG"`                    |             |
| `"BILANZIERUNG"`                |             |
| `"NETZNUTZUNGSVERTRAG"`         |             |
| `"MESSSTELLENBETRIEBSVERTRAG"`  |             |
| `"ENERGIELIEFERVERTRAG"`        |             |
| `"SPERRAUFTRAG"`                |             |
| `"ANGEBOT"`                     |             |
| `"TRANCHE"`                     |             |
| `"KOMMUNIKATIONSDATEN"`         |             |
| `"ZAEHLZEITDEFINITION"`         |             |
| `"SCHALTZEITDEFINITION"`        |             |
| `"LEISTUNGSKURVENDEFINITION"`   |             |
| `"NETZLOKATION"`                |             |
| `"STEUERBARE_RESSOURCE"`        |             |
| `"TECHNISCHE_RESSOURCE"`        |             |
| `"AD_HOC_STEUERKANAL"`          |             |
| `"LOKATIONSBUENDEL"`            |             |
| `"WERTE_NACH_TYP2"`             |             |
| `"REKLAMATION"`                 |             |
| `"STATUSBERICHT"`               |             |
| `"VERTRAG"`                     |             |
| `"BILANZKREIS"`                 |             |
| `"VERWENDUNGSZEITRAUM"`         |             |
| `"TARIFINFO"`                   |             |
| `"SUMMENZEITREIHE"`             |             |

### boTyp Default Value

The default value is:

```json
"SUMMENZEITREIHE"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## zaehlpunktId

ID des Zaehlpunkts

`zaehlpunktId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-zaehlpunktid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/zaehlpunktId")

### zaehlpunktId Type

`string`

## versionZeitreihe

Version der Zeitreihe

`versionZeitreihe`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-versionzeitreihe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/versionZeitreihe")

### versionZeitreihe Type

`string`

## bilanzkreis

Bilanzkreis

`bilanzkreis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/bilanzkreis")

### bilanzkreis Type

`string`

## bilanzkreisAn

BilanzkreisAn

`bilanzkreisAn`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-bilanzkreisan.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/bilanzkreisAn")

### bilanzkreisAn Type

`string`

## bilanzkreisVon

BilanzkreisVon

`bilanzkreisVon`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-bilanzkreisvon.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/bilanzkreisVon")

### bilanzkreisVon Type

`string`

## bilanzierteEnergiemenge

Bilanzierte Energiemenge

`bilanzierteEnergiemenge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Summenzeitreihe](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/bilanzierteEnergiemenge")

### bilanzierteEnergiemenge Type

`object` ([Menge](menge.md))

## bilanzierteAusfallmenge

Bilanzierte Ausfallmenge

`bilanzierteAusfallmenge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Summenzeitreihe](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/bilanzierteAusfallmenge")

### bilanzierteAusfallmenge Type

`object` ([Menge](menge.md))

## bilanzierungsgebiet

Bilanzierungsgebiet(e)

`bilanzierungsgebiet`

*   is optional

*   Type: `string[]`

*   can be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-bilanzierungsgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/bilanzierungsgebiet")

### bilanzierungsgebiet Type

`string[]`

## bezeichnung

Bezeichnung

`bezeichnung`

*   is optional

*   Type: `string` ([Bezeichnung](bezeichnung.md))

*   cannot be null

*   defined in: [Summenzeitreihe](bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bezeichnung.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string` ([Bezeichnung](bezeichnung.md))

### bezeichnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"BG_SZR_B"`     |             |
| `"BG_SZR_C"`     |             |
| `"BK_SZR_A"`     |             |
| `"BK_SZR_B_RZ"`  |             |
| `"BK_SZR_B_BG"`  |             |
| `"BK_SZR_C"`     |             |
| `"LF_SZR_A"`     |             |
| `"LF_SZR_B_RZ"`  |             |
| `"LF_SZR_B_BG"`  |             |
| `"DZUE"`         |             |
| `"NZR"`          |             |
| `"ASZR"`         |             |
| `"NGZ"`          |             |
| `"BK_SZR_EMBOB"` |             |

## verantwortlicheMarktrolle

Diese Rollen kann ein Marktteilnehmer einnehmen

`verantwortlicheMarktrolle`

*   is optional

*   Type: `string` ([Marktrolle](marktrolle.md))

*   cannot be null

*   defined in: [Summenzeitreihe](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/verantwortlicheMarktrolle")

### verantwortlicheMarktrolle Type

`string` ([Marktrolle](marktrolle.md))

### verantwortlicheMarktrolle Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"NB"`              |             |
| `"LF"`              |             |
| `"MSB"`             |             |
| `"MSBA"`            |             |
| `"GMSB"`            |             |
| `"MDL"`             |             |
| `"DL"`              |             |
| `"BKV"`             |             |
| `"UENB"`            |             |
| `"KUNDE-SELBST-NN"` |             |
| `"MGV"`             |             |
| `"EIV"`             |             |
| `"RB"`              |             |
| `"KUNDE"`           |             |
| `"INTERESSENT"`     |             |
| `"KN"`              |             |
| `"UBA"`             |             |
| `"BIKO"`            |             |
| `"ESA"`             |             |

## regelzone

Regelzone

`regelzone`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-regelzone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/regelzone")

### regelzone Type

`string`

## zeitreihentyp

Zeitreihentyp

`zeitreihentyp`

*   is optional

*   Type: `string` ([Zeitreihentyp](zeitreihentyp.md))

*   cannot be null

*   defined in: [Summenzeitreihe](zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeitreihentyp.schema.json#/properties/zeitreihentyp")

### zeitreihentyp Type

`string` ([Zeitreihentyp](zeitreihentyp.md))

### zeitreihentyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                                   | Explanation |
| :-------------------------------------------------------------------------------------- | :---------- |
| `"EGS"`                                                                                 |             |
| `"LGS"`                                                                                 |             |
| `"NZR"`                                                                                 |             |
| `"SES"`                                                                                 |             |
| `"SLS"`                                                                                 |             |
| `"TES"`                                                                                 |             |
| `"TLS"`                                                                                 |             |
| `"SLS_TLS"`                                                                             |             |
| `"SES_TES"`                                                                             |             |
| `"AUS"`                                                                                 |             |
| `"BAS"`                                                                                 |             |
| `"DBA"`                                                                                 |             |
| `"DZR"`                                                                                 |             |
| `"DZÜ"`                                                                                 |             |
| `"FPE"`                                                                                 |             |
| `"FPI"`                                                                                 |             |
| `"SRE"`                                                                                 |             |
| `"SRI"`                                                                                 |             |
| `"VZR"`                                                                                 |             |
| `"BIL"`                                                                                 |             |
| `"BIP"`                                                                                 |             |
| `"BIT"`                                                                                 |             |
| `"GAL"`                                                                                 |             |
| `"GAP"`                                                                                 |             |
| `"GAT"`                                                                                 |             |
| `"GEL"`                                                                                 |             |
| `"GEP"`                                                                                 |             |
| `"GET"`                                                                                 |             |
| `"SOL"`                                                                                 |             |
| `"SOP"`                                                                                 |             |
| `"SOT"`                                                                                 |             |
| `"WFL"`                                                                                 |             |
| `"WFP"`                                                                                 |             |
| `"WNL"`                                                                                 |             |
| `"WNP"`                                                                                 |             |
| `"WNT"`                                                                                 |             |
| `"WAL"`                                                                                 |             |
| `"WAP"`                                                                                 |             |
| `"WAT"`                                                                                 |             |
| `"AU1"`                                                                                 |             |
| `"BI1"`                                                                                 |             |
| `"BI2"`                                                                                 |             |
| `"BI3"`                                                                                 |             |
| `"GAA"`                                                                                 |             |
| `"GAB"`                                                                                 |             |
| `"GAC"`                                                                                 |             |
| `"GE1"`                                                                                 |             |
| `"GE2"`                                                                                 |             |
| `"GE3"`                                                                                 |             |
| `"SO1"`                                                                                 |             |
| `"SO2"`                                                                                 |             |
| `"SO3"`                                                                                 |             |
| `"WF1"`                                                                                 |             |
| `"WF2"`                                                                                 |             |
| `"WF3"`                                                                                 |             |
| `"WN1"`                                                                                 |             |
| `"WN2"`                                                                                 |             |
| `"WN3"`                                                                                 |             |
| `"WAA"`                                                                                 |             |
| `"WAB"`                                                                                 |             |
| `"WAC"`                                                                                 |             |
| `"AUSFALLARBEITSSUMME"`                                                                 |             |
| `"BILANZKREISABWEICHUNGSSALDO"`                                                         |             |
| `"DIFFERENZZEITREIHE"`                                                                  |             |
| `"DELTAZEITREIHE"`                                                                      |             |
| `"DELTAZEITREIHENUEBERTRAG"`                                                            |             |
| `"FAHRPLANENTNAHMESUMME"`                                                               |             |
| `"FAHRPLANEINSPEISESUMME"`                                                              |             |
| `"UEBERFUEHRUNGSZEITREIHE_SEKUNDAERREGELLEISTUNG_EXPORT"`                               |             |
| `"UEBERFUEHRUNGSZEITREIHE_SEKUNDAERREGELLEISTUNG_IMPORT"`                               |             |
| `"VERLUSTZEITREIHE"`                                                                    |             |
| `"EE_EINSPEISESUMME_BIOMASSE_BIOGAS_GEMESSEN"`                                          |             |
| `"EE_EINSPEISESUMME_BIOMASSE_BIOGAS_EINSPEISEPROFIL"`                                   |             |
| `"EE_EINSPEISESUMME_BIOMASSE_BIOGAS_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`         |             |
| `"EE_EINSPEISESUMME_DEPONIE_KLAER_GRUBENGAS_GEMESSEN"`                                  |             |
| `"EE_EINSPEISESUMME_DEPONIE_KLAER_GRUBENGAS_EINSPEISEPROFIL"`                           |             |
| `"EE_EINSPEISESUMME_DEPONIE_KLAER_GRUBENGAS_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"` |             |
| `"EE_EINSPEISESUMME_GEOTHERMIE_GEMESSEN"`                                               |             |
| `"EE_EINSPEISESUMME_GEOTHERMIE_EINSPEISEPROFIL"`                                        |             |
| `"EE_EINSPEISESUMME_GEOTHERMIE_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`              |             |
| `"EE_EINSPEISESUMME_SOLAR_GEMESSEN"`                                                    |             |
| `"EE_EINSPEISESUMME_SOLAR_EINSPEISEPROFIL"`                                             |             |
| `"EE_EINSPEISESUMME_SOLAR_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`                   |             |
| `"EE_EINSPEISESUMME_WIND_OFFSHORE_GEMESSEN"`                                            |             |
| `"EE_EINSPEISESUMME_WIND_OFFSHORE_EINSPEISEPROFIL"`                                     |             |
| `"EE_EINSPEISESUMME_WIND_OFFSHORE_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`           |             |
| `"EE_EINSPEISESUMME_WIND_ONSHORE_GEMESSEN"`                                             |             |
| `"EE_EINSPEISESUMME_WIND_ONSHORE_EINSPEISEPROFIL"`                                      |             |
| `"EE_EINSPEISESUMME_WIND_ONSHORE_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`            |             |
| `"EE_EINSPEISESUMME_WASSERKRAFT_GEMESSEN"`                                              |             |
| `"EE_EINSPEISESUMME_WASSERKRAFT_EINSPEISEPROFIL"`                                       |             |
| `"EE_EINSPEISESUMME_WASSERKRAFT_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`             |             |
| `"EEG_UEBERFUEHRUNG_AUSFALLARBEIT"`                                                     |             |
| `"EEG_UEBERFUEHRUNG_BIOMASSE_BIOGAS_WERTE"`                                             |             |
| `"EEG_UEBERFUEHRUNG_BIOMASSE_BIOGAS_STANDARDEINSPEISEPROFIL"`                           |             |
| `"EEG_UEBERFUEHRUNG_BIOMASSE_BIOGAS_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`         |             |
| `"EEG_UEBERFUEHRUNG_DEPONIE_KLAER_GRUBENGAS_WERTE"`                                     |             |
| `"EEG_UEBERFUEHRUNG_DEPONIE_KLAER_GRUBENGAS_STANDARDEINSPEISEPROFIL"`                   |             |
| `"EEG_UEBERFUEHRUNG_DEPONIE_KLAER_GRUBENGAS_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"` |             |
| `"EEG_UEBERFUEHRUNG_GEOTHERMIE_WERTE"`                                                  |             |
| `"EEG_UEBERFUEHRUNG_GEOTHERMIE_STANDARDEINSPEISEPROFIL"`                                |             |
| `"EEG_UEBERFUEHRUNG_GEOTHERMIE_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`              |             |
| `"EEG_UEBERFUEHRUNG_SOLAR_WERTE"`                                                       |             |
| `"EEG_UEBERFUEHRUNG_SOLAR_STANDARDEINSPEISEPROFIL"`                                     |             |
| `"EEG_UEBERFUEHRUNG_SOLAR_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`                   |             |
| `"EEG_UEBERFUEHRUNG_WIND_OFFSHORE_WERTE"`                                               |             |
| `"EEG_UEBERFUEHRUNG_WIND_OFFSHORE_STANDARDEINSPEISEPROFIL"`                             |             |
| `"EEG_UEBERFUEHRUNG_WIND_OFFSHORE_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`           |             |
| `"EEG_UEBERFUEHRUNG_WIND_ONSHORE_WERTE"`                                                |             |
| `"EEG_UEBERFUEHRUNG_WIND_ONSHORE_STANDARDEINSPEISEPROFIL"`                              |             |
| `"EEG_UEBERFUEHRUNG_WIND_ONSHORE_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`            |             |
| `"EEG_UEBERFUEHRUNG_WASSERKRAFT_WERTE"`                                                 |             |
| `"EEG_UEBERFUEHRUNG_WASSERKRAFT_STANDARDEINSPEISEPROFIL"`                               |             |
| `"EEG_UEBERFUEHRUNG_WASSERKRAFT_TAGESPARAMETERABHAENGIGES_EINSPEISEPROFIL"`             |             |

## bezugszeitraum

Bezugszeitraum einer Zeitreihe

`bezugszeitraum`

*   is optional

*   Type: `string` ([Bezugszeitraum](bezugszeitraum.md))

*   cannot be null

*   defined in: [Summenzeitreihe](bezugszeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bezugszeitraum.schema.json#/properties/bezugszeitraum")

### bezugszeitraum Type

`string` ([Bezugszeitraum](bezugszeitraum.md))

### bezugszeitraum Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"TAG"`   |             |
| `"MONAT"` |             |

## netzebene

Netzebene

`netzebene`

*   is optional

*   Type: `string` ([Netzebene](netzebene.md))

*   cannot be null

*   defined in: [Summenzeitreihe](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/netzebene")

### netzebene Type

`string` ([Netzebene](netzebene.md))

### netzebene Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"NSP"`          |             |
| `"MSP"`          |             |
| `"HSP"`          |             |
| `"HSS"`          |             |
| `"MSP_NSP_UMSP"` |             |
| `"HSP_MSP_UMSP"` |             |
| `"HSS_HSP_UMSP"` |             |
| `"HD"`           |             |
| `"MD"`           |             |
| `"ND"`           |             |

## umspannung

Netzebene

`umspannung`

*   is optional

*   Type: `string` ([Netzebene](netzebene.md))

*   cannot be null

*   defined in: [Summenzeitreihe](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/umspannung")

### umspannung Type

`string` ([Netzebene](netzebene.md))

### umspannung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"NSP"`          |             |
| `"MSP"`          |             |
| `"HSP"`          |             |
| `"HSS"`          |             |
| `"MSP_NSP_UMSP"` |             |
| `"HSP_MSP_UMSP"` |             |
| `"HSS_HSP_UMSP"` |             |
| `"HD"`           |             |
| `"MD"`           |             |
| `"ND"`           |             |

## datenstatusZeitreihe

Datenstatus einer Zeitreihe

`datenstatusZeitreihe`

*   is optional

*   Type: `string` ([DatenstatusZeitreihe](datenstatuszeitreihe.md))

*   cannot be null

*   defined in: [Summenzeitreihe](datenstatuszeitreihe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DatenstatusZeitreihe.schema.json#/properties/datenstatusZeitreihe")

### datenstatusZeitreihe Type

`string` ([DatenstatusZeitreihe](datenstatuszeitreihe.md))

### datenstatusZeitreihe Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                | Explanation |
| :----------------------------------- | :---------- |
| `"ABRECHNUNGSDATEN"`                 |             |
| `"ABGERECHNETE_DATEN"`               |             |
| `"ABRECHNUNGSDATEN_KORREKTUR_BKA"`   |             |
| `"ABGERECHNETE_DATEN_KORREKTUR_BKA"` |             |

## zuordnungsregel

Zuordnungsregel einer Summenzeitreihe

`zuordnungsregel`

*   is optional

*   Type: `string` ([Zuordnungsregel](zuordnungsregel.md))

*   cannot be null

*   defined in: [Summenzeitreihe](zuordnungsregel.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zuordnungsregel.schema.json#/properties/zuordnungsregel")

### zuordnungsregel Type

`string` ([Zuordnungsregel](zuordnungsregel.md))

### zuordnungsregel Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                               | Explanation |
| :---------------------------------- | :---------- |
| `"SELBE_LIEFERRICHTUNG"`            |             |
| `"ENTGEGENGESETZTE_LIEFERRICHTUNG"` |             |

## zeitreihenprodukt

Liste der Zeitreihenprodukte

`zeitreihenprodukt`

*   is optional

*   Type: `object[]` ([Zeitreihenprodukt](zeitreihenprodukt.md))

*   can be null

*   defined in: [Summenzeitreihe](summenzeitreihe-properties-zeitreihenprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Summenzeitreihe.schema.json#/properties/zeitreihenprodukt")

### zeitreihenprodukt Type

`object[]` ([Zeitreihenprodukt](zeitreihenprodukt.md))
