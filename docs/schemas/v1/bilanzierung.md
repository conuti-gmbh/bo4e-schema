## Untitled object in undefined Type

`object` ([Details](bilanzierung.md))

# Untitled object in undefined Properties

| Property                                                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                  |
| :-------------------------------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [boTyp](#botyp)                                                             | `string`  | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                          |
| [versionStruktur](#versionstruktur)                                         | `string`  | Required | cannot be null | [Untitled schema](bilanzierung-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/versionStruktur")                                         |
| [marktlokationsId](#marktlokationsid)                                       | `string`  | Optional | cannot be null | [Untitled schema](bilanzierung-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/marktlokationsId")                                       |
| [aggregationsverantwortung](#aggregationsverantwortung)                     | `string`  | Optional | cannot be null | [Untitled schema](aggregationsverantwortung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Aggregationsverantwortung.schema.json#/properties/aggregationsverantwortung")                              |
| [zeitreihentyp](#zeitreihentyp)                                             | `string`  | Optional | cannot be null | [Untitled schema](bilanzierung-properties-zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/zeitreihentyp")                                             |
| [prognosegrundlage](#prognosegrundlage)                                     | `string`  | Optional | cannot be null | [Untitled schema](prognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Prognosegrundlage.schema.json#/properties/prognosegrundlage")                                                      |
| [bilanzierungsbeginn](#bilanzierungsbeginn)                                 | `string`  | Optional | cannot be null | [Untitled schema](bilanzierung-properties-bilanzierungsbeginn.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzierungsbeginn")                                 |
| [bilanzierungsende](#bilanzierungsende)                                     | `string`  | Optional | cannot be null | [Untitled schema](bilanzierung-properties-bilanzierungsende.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzierungsende")                                     |
| [bilanzkreis](#bilanzkreis)                                                 | `string`  | Optional | cannot be null | [Untitled schema](bilanzierung-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzkreis")                                                 |
| [fallgruppenzuordnung](#fallgruppenzuordnung)                               | `string`  | Optional | cannot be null | [Untitled schema](fallgruppenzuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fallgruppenzuordnung.schema.json#/properties/fallgruppenzuordnung")                                             |
| [temperaturarbeit](#temperaturarbeit)                                       | `object`  | Optional | cannot be null | [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/temperaturarbeit")                                                                                |
| [jahresverbrauchsprognose](#jahresverbrauchsprognose)                       | `object`  | Optional | cannot be null | [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/jahresverbrauchsprognose")                                                                        |
| [kundenwert](#kundenwert)                                                   | `object`  | Optional | cannot be null | [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/kundenwert")                                                                                      |
| [verbrauchsaufteilung](#verbrauchsaufteilung)                               | `object`  | Optional | cannot be null | [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/verbrauchsaufteilung")                                                                            |
| [wahlrechtPrognosegrundlage](#wahlrechtprognosegrundlage)                   | `string`  | Optional | cannot be null | [Untitled schema](wahlrechtprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WahlrechtPrognosegrundlage.schema.json#/properties/wahlrechtPrognosegrundlage")                           |
| [grundWahlrechtPrognosegrundlage](#grundwahlrechtprognosegrundlage)         | `string`  | Optional | cannot be null | [Untitled schema](wahlrechtprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WahlrechtPrognosegrundlage.schema.json#/properties/grundWahlrechtPrognosegrundlage")                      |
| [abwicklungsmodell](#abwicklungsmodell)                                     | `string`  | Optional | cannot be null | [Untitled schema](abwicklungsmodell.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Abwicklungsmodell.schema.json#/properties/abwicklungsmodell")                                                      |
| [vorjahresverbrauch](#vorjahresverbrauch)                                   | `object`  | Optional | cannot be null | [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/vorjahresverbrauch")                                                                              |
| [datenqualitaet](#datenqualitaet)                                           | `string`  | Optional | cannot be null | [Untitled schema](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                                               |
| [zeitraumId](#zeitraumid)                                                   | `integer` | Optional | cannot be null | [Untitled schema](bilanzierung-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/zeitraumId")                                                   |
| [lastprofile](#lastprofile)                                                 | `array`   | Optional | cannot be null | [Untitled schema](bilanzierung-properties-lastprofile.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/lastprofile")                                                 |
| [lastprofileBilanzierungsbeteiligter](#lastprofilebilanzierungsbeteiligter) | `array`   | Optional | cannot be null | [Untitled schema](bilanzierung-properties-lastprofilebilanzierungsbeteiligter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/lastprofileBilanzierungsbeteiligter") |
| [detailsPrognosegrundlage](#detailsprognosegrundlage)                       | `array`   | Optional | cannot be null | [Untitled schema](bilanzierung-properties-detailsprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/detailsPrognosegrundlage")                       |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

### boTyp Type

`string`

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



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## marktlokationsId



`marktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/marktlokationsId")

### marktlokationsId Type

`string`

## aggregationsverantwortung



`aggregationsverantwortung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](aggregationsverantwortung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Aggregationsverantwortung.schema.json#/properties/aggregationsverantwortung")

### aggregationsverantwortung Type

`string`

### aggregationsverantwortung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"UENB"` |             |
| `"VNB"`  |             |

## zeitreihentyp



`zeitreihentyp`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/zeitreihentyp")

### zeitreihentyp Type

`string`

## prognosegrundlage



`prognosegrundlage`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](prognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Prognosegrundlage.schema.json#/properties/prognosegrundlage")

### prognosegrundlage Type

`string`

### prognosegrundlage Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"WERTE"`   |             |
| `"PROFILE"` |             |

## bilanzierungsbeginn



`bilanzierungsbeginn`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-bilanzierungsbeginn.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzierungsbeginn")

### bilanzierungsbeginn Type

`string`

### bilanzierungsbeginn Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## bilanzierungsende



`bilanzierungsende`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-bilanzierungsende.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzierungsende")

### bilanzierungsende Type

`string`

### bilanzierungsende Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## bilanzkreis



`bilanzkreis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/bilanzkreis")

### bilanzkreis Type

`string`

## fallgruppenzuordnung



`fallgruppenzuordnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](fallgruppenzuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fallgruppenzuordnung.schema.json#/properties/fallgruppenzuordnung")

### fallgruppenzuordnung Type

`string`

### fallgruppenzuordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"GABI_RLMmT"`  |             |
| `"GABI_RLMoT"`  |             |
| `"GABI_RLMNEV"` |             |

## temperaturarbeit



`temperaturarbeit`

*   is optional

*   Type: `object` ([Details](menge.md))

*   cannot be null

*   defined in: [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/temperaturarbeit")

### temperaturarbeit Type

`object` ([Details](menge.md))

## jahresverbrauchsprognose



`jahresverbrauchsprognose`

*   is optional

*   Type: `object` ([Details](menge.md))

*   cannot be null

*   defined in: [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/jahresverbrauchsprognose")

### jahresverbrauchsprognose Type

`object` ([Details](menge.md))

## kundenwert



`kundenwert`

*   is optional

*   Type: `object` ([Details](menge.md))

*   cannot be null

*   defined in: [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/kundenwert")

### kundenwert Type

`object` ([Details](menge.md))

## verbrauchsaufteilung



`verbrauchsaufteilung`

*   is optional

*   Type: `object` ([Details](menge.md))

*   cannot be null

*   defined in: [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/verbrauchsaufteilung")

### verbrauchsaufteilung Type

`object` ([Details](menge.md))

## wahlrechtPrognosegrundlage



`wahlrechtPrognosegrundlage`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](wahlrechtprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WahlrechtPrognosegrundlage.schema.json#/properties/wahlrechtPrognosegrundlage")

### wahlrechtPrognosegrundlage Type

`string`

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



`grundWahlrechtPrognosegrundlage`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](wahlrechtprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WahlrechtPrognosegrundlage.schema.json#/properties/grundWahlrechtPrognosegrundlage")

### grundWahlrechtPrognosegrundlage Type

`string`

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



`abwicklungsmodell`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](abwicklungsmodell.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Abwicklungsmodell.schema.json#/properties/abwicklungsmodell")

### abwicklungsmodell Type

`string`

### abwicklungsmodell Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                            | Explanation |
| :----------------------------------------------- | :---------- |
| `"MODELL_1_BILANZIERUNG_AN_MARKTLOKATION"`       |             |
| `"MODELL_2_BILANZIERUNG_IM_BILANZIERUNGSGEBIET"` |             |

## vorjahresverbrauch



`vorjahresverbrauch`

*   is optional

*   Type: `object` ([Details](menge.md))

*   cannot be null

*   defined in: [Untitled schema](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/vorjahresverbrauch")

### vorjahresverbrauch Type

`object` ([Details](menge.md))

## datenqualitaet



`datenqualitaet`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

### datenqualitaet Type

`string`

### datenqualitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                          | Explanation |
| :----------------------------- | :---------- |
| `"DATEN"`                      |             |
| `"ERWARTETE_DATEN"`            |             |
| `"IM_SYSTEM_VORHANDENE_DATEN"` |             |
| `"INFORMATIVE_DATEN"`          |             |

## zeitraumId



`zeitraumId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/zeitraumId")

### zeitraumId Type

`integer`

## lastprofile



`lastprofile`

*   is optional

*   Type: `object[]` ([Details](lastprofil.md))

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-lastprofile.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/lastprofile")

### lastprofile Type

`object[]` ([Details](lastprofil.md))

## lastprofileBilanzierungsbeteiligter



`lastprofileBilanzierungsbeteiligter`

*   is optional

*   Type: `object[]` ([Details](lastprofil.md))

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-lastprofilebilanzierungsbeteiligter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/lastprofileBilanzierungsbeteiligter")

### lastprofileBilanzierungsbeteiligter Type

`object[]` ([Details](lastprofil.md))

## detailsPrognosegrundlage



`detailsPrognosegrundlage`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Untitled schema](bilanzierung-properties-detailsprognosegrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Bilanzierung.schema.json#/properties/detailsPrognosegrundlage")

### detailsPrognosegrundlage Type

`string[]`
