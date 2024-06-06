## Untitled object in undefined Type

`object` ([Details](tarifinfo.md))

# Untitled object in undefined Properties

| Property                                         | Type     | Required | Nullable       | Defined by                                                                                                                                                                                    |
| :----------------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                  | `string` | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                            |
| [versionStruktur](#versionstruktur)              | `string` | Required | cannot be null | [Untitled schema](tarifinfo-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/versionStruktur") |
| [anbieter](#anbieter)                            | `object` | Optional | cannot be null | [Untitled schema](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/anbieter")                       |
| [anbietername](#anbietername)                    | `string` | Optional | cannot be null | [Untitled schema](tarifinfo-properties-anbietername.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/anbietername")       |
| [anwendung\_von](#anwendung_von)                 | `string` | Optional | cannot be null | [Untitled schema](tarifinfo-properties-anwendung_von.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/anwendung_von")     |
| [bemerkung](#bemerkung)                          | `string` | Optional | cannot be null | [Untitled schema](tarifinfo-properties-bemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/bemerkung")             |
| [bezeichnung](#bezeichnung)                      | `string` | Optional | cannot be null | [Untitled schema](tarifinfo-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/bezeichnung")         |
| [energiemix](#energiemix)                        | `object` | Optional | cannot be null | [Untitled schema](energiemix.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/energiemix")                              |
| [kundentypen](#kundentypen)                      | `array`  | Optional | cannot be null | [Untitled schema](tarifinfo-properties-kundentypen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/kundentypen")         |
| [registeranzahl](#registeranzahl)                | `string` | Optional | cannot be null | [Untitled schema](registeranzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Registeranzahl.schema.json#/properties/registeranzahl")                 |
| [sparte](#sparte)                                | `string` | Optional | cannot be null | [Untitled schema](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                         |
| [tarifmerkmale](#tarifmerkmale)                  | `array`  | Optional | cannot be null | [Untitled schema](tarifinfo-properties-tarifmerkmale.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/tarifmerkmale")     |
| [tariftyp](#tariftyp)                            | `string` | Optional | cannot be null | [Untitled schema](tariftyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tariftyp.schema.json#/properties/tariftyp")                                   |
| [vertragskonditionen](#vertragskonditionen)      | `object` | Optional | cannot be null | [Untitled schema](vertragskonditionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/vertragskonditionen")   |
| [website](#website)                              | `string` | Optional | cannot be null | [Untitled schema](tarifinfo-properties-website.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/website")                 |
| [zeitliche\_gueltigkeit](#zeitliche_gueltigkeit) | `object` | Optional | cannot be null | [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitliche_gueltigkeit")                       |

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
"TARIFINFO"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](tarifinfo-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## anbieter

Der Marktteilnehmer (Lieferant), der diesen Tarif anbietet

`anbieter`

*   is optional

*   Type: `object` ([Details](marktteilnehmer.md))

*   cannot be null

*   defined in: [Untitled schema](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/anbieter")

### anbieter Type

`object` ([Details](marktteilnehmer.md))

## anbietername

Der Name des Marktpartners, der den Tarif anbietet

`anbietername`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](tarifinfo-properties-anbietername.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/anbietername")

### anbietername Type

`string`

## anwendung\_von

Angabe des inklusiven Zeitpunkts, ab dem der Tarif bzw. der Preis angewendet und abgerechnet wird

`anwendung_von`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](tarifinfo-properties-anwendung_von.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/anwendung_von")

### anwendung\_von Type

`string`

### anwendung\_von Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## bemerkung

Freitext

`bemerkung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](tarifinfo-properties-bemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/bemerkung")

### bemerkung Type

`string`

## bezeichnung

Name des Tarifs

`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](tarifinfo-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`

## energiemix

Der Energiemix, der für diesen Tarif gilt

`energiemix`

*   is optional

*   Type: `object` ([Details](energiemix.md))

*   cannot be null

*   defined in: [Untitled schema](energiemix.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/energiemix")

### energiemix Type

`object` ([Details](energiemix.md))

## kundentypen

Kundentypen für den der Tarif gilt, z.B. Privatkunden

`kundentypen`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Untitled schema](tarifinfo-properties-kundentypen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/kundentypen")

### kundentypen Type

`string[]`

## registeranzahl

Die Art des Tarifes, z.B. Eintarif oder Mehrtarif

`registeranzahl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](registeranzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Registeranzahl.schema.json#/properties/registeranzahl")

### registeranzahl Type

`string`

### registeranzahl Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"EINTARIF"`  |             |
| `"MEHRTARIF"` |             |
| `"ZWEITARIF"` |             |

## sparte

Strom oder Gas, etc.

`sparte`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

### sparte Type

`string`

### sparte Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"STROM"`      |             |
| `"GAS"`        |             |
| `"FERNWAERME"` |             |
| `"NAHWAERME"`  |             |
| `"WASSER"`     |             |
| `"ABWASSER"`   |             |

## tarifmerkmale

Weitere Merkmale des Tarifs, z.B. Festpreis oder Vorkasse

`tarifmerkmale`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Untitled schema](tarifinfo-properties-tarifmerkmale.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/tarifmerkmale")

### tarifmerkmale Type

`string[]`

## tariftyp

Hinweis auf den Tariftyp, z.B. Grundversorgung oder Sondertarif

`tariftyp`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](tariftyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tariftyp.schema.json#/properties/tariftyp")

### tariftyp Type

`string`

### tariftyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"ERSATZVERSORGUNG"`       |             |
| `"GRUNDVERSORGUNG"`        |             |
| `"GRUND_ERSATZVERSORGUNG"` |             |
| `"SONDERTARIF"`            |             |

## vertragskonditionen

Mindestlaufzeiten und Kündigungsfristen zusammengefasst

`vertragskonditionen`

*   is optional

*   Type: `object` ([Details](vertragskonditionen.md))

*   cannot be null

*   defined in: [Untitled schema](vertragskonditionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/vertragskonditionen")

### vertragskonditionen Type

`object` ([Details](vertragskonditionen.md))

## website

Internetseite auf dem der Tarif zu finden ist

`website`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](tarifinfo-properties-website.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tarifinfo.schema.json#/properties/website")

### website Type

`string`

## zeitliche\_gueltigkeit

Angabe, in welchem Zeitraum der Tarif gültig ist

`zeitliche_gueltigkeit`

*   is optional

*   Type: `object` ([Details](zeitraum.md))

*   cannot be null

*   defined in: [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitliche_gueltigkeit")

### zeitliche\_gueltigkeit Type

`object` ([Details](zeitraum.md))
