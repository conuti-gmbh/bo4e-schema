## Bilanzierung Type

`object` ([Bilanzierung](bilanzierung.md))

# Bilanzierung Properties

| Property                                                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                               |
| :-------------------------------------------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                             | `string` | Required | cannot be null | [Bilanzierung](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                          |
| [versionStruktur](#versionstruktur)                                         | `string` | Required | cannot be null | [Bilanzierung](bilanzierung-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/versionStruktur")                                         |
| [marktlokationsId](#marktlokationsid)                                       | `string` | Optional | cannot be null | [Bilanzierung](bilanzierung-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/marktlokationsId")                                       |
| [aggregationsverantwortung](#aggregationsverantwortung)                     | `string` | Optional | cannot be null | [Bilanzierung](aggregationsverantwortung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Aggregationsverantwortung.schema.json#/properties/aggregationsverantwortung")                              |
| [zeitreihentyp](#zeitreihentyp)                                             | `string` | Optional | cannot be null | [Bilanzierung](bilanzierung-properties-zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/zeitreihentyp")                                             |
| [prognosegrundlage](#prognosegrundlage)                                     | `string` | Optional | cannot be null | [Bilanzierung](prognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Prognosegrundlage.schema.json#/properties/prognosegrundlage")                                                      |
| [bilanzierungsbeginn](#bilanzierungsbeginn)                                 | `string` | Optional | cannot be null | [Bilanzierung](bilanzierung-properties-bilanzierungsbeginn.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzierungsbeginn")                                 |
| [bilanzierungsende](#bilanzierungsende)                                     | `string` | Optional | cannot be null | [Bilanzierung](bilanzierung-properties-bilanzierungsende.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzierungsende")                                     |
| [bilanzkreis](#bilanzkreis)                                                 | `string` | Optional | cannot be null | [Bilanzierung](bilanzierung-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzkreis")                                                 |
| [fallgruppenzuordnung](#fallgruppenzuordnung)                               | `string` | Optional | cannot be null | [Bilanzierung](fallgruppenzuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fallgruppenzuordnung.schema.json#/properties/fallgruppenzuordnung")                                             |
| [temperaturarbeit](#temperaturarbeit)                                       | `object` | Optional | cannot be null | [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/temperaturarbeit")                                                                                |
| [jahresverbrauchsprognose](#jahresverbrauchsprognose)                       | `object` | Optional | cannot be null | [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/jahresverbrauchsprognose")                                                                        |
| [kundenwert](#kundenwert)                                                   | `object` | Optional | cannot be null | [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/kundenwert")                                                                                      |
| [verbrauchsaufteilung](#verbrauchsaufteilung)                               | `object` | Optional | cannot be null | [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/verbrauchsaufteilung")                                                                            |
| [wahlrechtPrognosegrundlage](#wahlrechtprognosegrundlage)                   | `string` | Optional | cannot be null | [Bilanzierung](wahlrechtprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WahlrechtPrognosegrundlage.schema.json#/properties/wahlrechtPrognosegrundlage")                           |
| [grundWahlrechtPrognosegrundlage](#grundwahlrechtprognosegrundlage)         | `string` | Optional | cannot be null | [Bilanzierung](wahlrechtprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WahlrechtPrognosegrundlage.schema.json#/properties/grundWahlrechtPrognosegrundlage")                      |
| [abwicklungsmodell](#abwicklungsmodell)                                     | `string` | Optional | cannot be null | [Bilanzierung](abwicklungsmodell.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Abwicklungsmodell.schema.json#/properties/abwicklungsmodell")                                                      |
| [vorjahresverbrauch](#vorjahresverbrauch)                                   | `object` | Optional | cannot be null | [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/vorjahresverbrauch")                                                                              |
| [datenqualitaet](#datenqualitaet)                                           | `string` | Optional | cannot be null | [Bilanzierung](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                                               |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum)                               | `object` | Optional | cannot be null | [Bilanzierung](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                                                      |
| [lastprofile](#lastprofile)                                                 | `array`  | Optional | can be null    | [Bilanzierung](bilanzierung-properties-lastprofile.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/lastprofile")                                                 |
| [lastprofileBilanzierungsbeteiligter](#lastprofilebilanzierungsbeteiligter) | `array`  | Optional | can be null    | [Bilanzierung](bilanzierung-properties-lastprofilebilanzierungsbeteiligter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/lastprofileBilanzierungsbeteiligter") |
| [detailsPrognosegrundlage](#detailsprognosegrundlage)                       | `array`  | Optional | can be null    | [Bilanzierung](bilanzierung-properties-detailsprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/detailsPrognosegrundlage")                       |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Bilanzierung](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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

### boTyp Default Value

The default value is:

```json
"BILANZIERUNG"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Bilanzierung](bilanzierung-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## marktlokationsId

Für welche Marktlokation gelten diese Bilanzierungsdaten

`marktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bilanzierung](bilanzierung-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/marktlokationsId")

### marktlokationsId Type

`string`

## aggregationsverantwortung

Aggregationsverantwortung

`aggregationsverantwortung`

*   is optional

*   Type: `string` ([Aggregationsverantwortung](aggregationsverantwortung.md))

*   cannot be null

*   defined in: [Bilanzierung](aggregationsverantwortung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Aggregationsverantwortung.schema.json#/properties/aggregationsverantwortung")

### aggregationsverantwortung Type

`string` ([Aggregationsverantwortung](aggregationsverantwortung.md))

### aggregationsverantwortung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"UENB"` |             |
| `"VNB"`  |             |

## zeitreihentyp

Zeitreihentyp

`zeitreihentyp`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bilanzierung](bilanzierung-properties-zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/zeitreihentyp")

### zeitreihentyp Type

`string`

## prognosegrundlage

Prognosegrundlage

`prognosegrundlage`

*   is optional

*   Type: `string` ([Prognosegrundlage](prognosegrundlage.md))

*   cannot be null

*   defined in: [Bilanzierung](prognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Prognosegrundlage.schema.json#/properties/prognosegrundlage")

### prognosegrundlage Type

`string` ([Prognosegrundlage](prognosegrundlage.md))

### prognosegrundlage Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"WERTE"`   |             |
| `"PROFILE"` |             |

## bilanzierungsbeginn

Inklusiver Start der Bilanzierung

`bilanzierungsbeginn`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bilanzierung](bilanzierung-properties-bilanzierungsbeginn.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzierungsbeginn")

### bilanzierungsbeginn Type

`string`

### bilanzierungsbeginn Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## bilanzierungsende

Exklusives Ende der Bilanzierung

`bilanzierungsende`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bilanzierung](bilanzierung-properties-bilanzierungsende.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzierungsende")

### bilanzierungsende Type

`string`

### bilanzierungsende Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## bilanzkreis

Bilanzkreis

`bilanzkreis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Bilanzierung](bilanzierung-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzkreis")

### bilanzkreis Type

`string`

## fallgruppenzuordnung

Fallgruppenzuordnung

`fallgruppenzuordnung`

*   is optional

*   Type: `string` ([Fallgruppenzuordnung](fallgruppenzuordnung.md))

*   cannot be null

*   defined in: [Bilanzierung](fallgruppenzuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fallgruppenzuordnung.schema.json#/properties/fallgruppenzuordnung")

### fallgruppenzuordnung Type

`string` ([Fallgruppenzuordnung](fallgruppenzuordnung.md))

### fallgruppenzuordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"GABI_RLMmT"`  |             |
| `"GABI_RLMoT"`  |             |
| `"GABI_RLMNEV"` |             |

## temperaturarbeit

Kundenwert TLP

`temperaturarbeit`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/temperaturarbeit")

### temperaturarbeit Type

`object` ([Menge](menge.md))

## jahresverbrauchsprognose

Jahresverbrauchsprognose

`jahresverbrauchsprognose`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/jahresverbrauchsprognose")

### jahresverbrauchsprognose Type

`object` ([Menge](menge.md))

## kundenwert

Kundenwert

`kundenwert`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/kundenwert")

### kundenwert Type

`object` ([Menge](menge.md))

## verbrauchsaufteilung

Verbrauchsaufteilung

`verbrauchsaufteilung`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/verbrauchsaufteilung")

### verbrauchsaufteilung Type

`object` ([Menge](menge.md))

## wahlrechtPrognosegrundlage

WahlrechtPrognosegrundlage

`wahlrechtPrognosegrundlage`

*   is optional

*   Type: `string` ([WahlrechtPrognosegrundlage](wahlrechtprognosegrundlage.md))

*   cannot be null

*   defined in: [Bilanzierung](wahlrechtprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WahlrechtPrognosegrundlage.schema.json#/properties/wahlrechtPrognosegrundlage")

### wahlrechtPrognosegrundlage Type

`string` ([WahlrechtPrognosegrundlage](wahlrechtprognosegrundlage.md))

### wahlrechtPrognosegrundlage Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                              | Explanation |
| :--------------------------------- | :---------- |
| `"DURCH_LF"`                       |             |
| `"DURCH_LF_NICHT_GEGEBEN"`         |             |
| `"NICHT_WEGEN_GROSSEN_VERBRAUCHS"` |             |
| `"NICHT_WEGEN_EIGENVERBRAUCH"`     |             |
| `"NICHT_WEGEN_TAGES_VERBRAUCH"`    |             |
| `"NICHT_WEGEN_ENWG"`               |             |

## grundWahlrechtPrognosegrundlage

WahlrechtPrognosegrundlage

`grundWahlrechtPrognosegrundlage`

*   is optional

*   Type: `string` ([WahlrechtPrognosegrundlage](wahlrechtprognosegrundlage.md))

*   cannot be null

*   defined in: [Bilanzierung](wahlrechtprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WahlrechtPrognosegrundlage.schema.json#/properties/grundWahlrechtPrognosegrundlage")

### grundWahlrechtPrognosegrundlage Type

`string` ([WahlrechtPrognosegrundlage](wahlrechtprognosegrundlage.md))

### grundWahlrechtPrognosegrundlage Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                              | Explanation |
| :--------------------------------- | :---------- |
| `"DURCH_LF"`                       |             |
| `"DURCH_LF_NICHT_GEGEBEN"`         |             |
| `"NICHT_WEGEN_GROSSEN_VERBRAUCHS"` |             |
| `"NICHT_WEGEN_EIGENVERBRAUCH"`     |             |
| `"NICHT_WEGEN_TAGES_VERBRAUCH"`    |             |
| `"NICHT_WEGEN_ENWG"`               |             |

## abwicklungsmodell

Abwicklungsmodell

`abwicklungsmodell`

*   is optional

*   Type: `string` ([Abwicklungsmodell](abwicklungsmodell.md))

*   cannot be null

*   defined in: [Bilanzierung](abwicklungsmodell.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Abwicklungsmodell.schema.json#/properties/abwicklungsmodell")

### abwicklungsmodell Type

`string` ([Abwicklungsmodell](abwicklungsmodell.md))

### abwicklungsmodell Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                            | Explanation |
| :----------------------------------------------- | :---------- |
| `"MODELL_1_BILANZIERUNG_AN_MARKTLOKATION"`       |             |
| `"MODELL_2_BILANZIERUNG_IM_BILANZIERUNGSGEBIET"` |             |

## vorjahresverbrauch

Vorjahresverbrauch

`vorjahresverbrauch`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Bilanzierung](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/vorjahresverbrauch")

### vorjahresverbrauch Type

`object` ([Menge](menge.md))

## datenqualitaet

Datenqualitaet

`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Bilanzierung](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

### datenqualitaet Type

`string` ([Datenqualitaet](datenqualitaet.md))

### datenqualitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                    | Explanation |
| :--------------------------------------- | :---------- |
| `"ERWARTETE_DATEN"`                      |             |
| `"IM_SYSTEM_VORHANDENE_DATEN"`           |             |
| `"INFORMATIVE_DATEN"`                    |             |
| `"GUELTIGE_DATEN"`                       |             |
| `"KEINE_DATEN"`                          |             |
| `"IM_SYSTEM_KEINE_DATEN_VORHANDEN"`      |             |
| `"KEINE_DATEN_ERWARTET"`                 |             |
| `"DIFFERENZ_DATEN"`                      |             |
| `"DIFFERENZ_ERWARTETE_DATEN"`            |             |
| `"DIFFERENZ_IM_SYSTEM_VORHANDENE_DATEN"` |             |

## gueltigkeitszeitraum

Gültigkeitszeitraum

`gueltigkeitszeitraum`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Bilanzierung](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))

## lastprofile

Eine Liste der verwendeten Lastprofile (SLP, SLP/TLP, ALP etc.)

`lastprofile`

*   is optional

*   Type: `object[]` ([Lastprofil](lastprofil.md))

*   can be null

*   defined in: [Bilanzierung](bilanzierung-properties-lastprofile.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/lastprofile")

### lastprofile Type

`object[]` ([Lastprofil](lastprofil.md))

## lastprofileBilanzierungsbeteiligter

Lastprofile des Bilanzierungsbeteiligten

`lastprofileBilanzierungsbeteiligter`

*   is optional

*   Type: `object[]` ([Lastprofil](lastprofil.md))

*   can be null

*   defined in: [Bilanzierung](bilanzierung-properties-lastprofilebilanzierungsbeteiligter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/lastprofileBilanzierungsbeteiligter")

### lastprofileBilanzierungsbeteiligter Type

`object[]` ([Lastprofil](lastprofil.md))

## detailsPrognosegrundlage

Prognosegrundlage - Besteht der Bedarf ein tagesparameteräbhängiges Lastprofil mit gemeinsamer Messung anzugeben, so ist dies über die 2 -malige Wiederholung des CAV Segments mit der Angabe der Codes E02 und E14 möglich.

`detailsPrognosegrundlage`

*   is optional

*   Type: `string[]` ([Profiltyp](profiltyp.md))

*   can be null

*   defined in: [Bilanzierung](bilanzierung-properties-detailsprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/detailsPrognosegrundlage")

### detailsPrognosegrundlage Type

`string[]` ([Profiltyp](profiltyp.md))
