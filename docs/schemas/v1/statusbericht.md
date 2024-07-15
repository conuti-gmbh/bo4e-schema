## Statusbericht Type

`object` ([Statusbericht](statusbericht.md))

# Statusbericht Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                          |
| :---------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                     | `string` | Required | cannot be null | [Statusbericht](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                    |
| [versionStruktur](#versionstruktur) | `string` | Required | cannot be null | [Statusbericht](statusbericht-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusbericht.schema.json#/properties/versionStruktur") |
| [status](#status)                   | `string` | Optional | cannot be null | [Statusbericht](berichtstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BerichtStatus.schema.json#/properties/status")                                   |
| [pruefgegenstand](#pruefgegenstand) | `string` | Optional | cannot be null | [Statusbericht](statusbericht-properties-pruefgegenstand.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusbericht.schema.json#/properties/pruefgegenstand") |
| [datumPruefung](#datumpruefung)     | `string` | Optional | cannot be null | [Statusbericht](statusbericht-properties-datumpruefung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusbericht.schema.json#/properties/datumPruefung")     |
| [fehler](#fehler)                   | `object` | Optional | cannot be null | [Statusbericht](fehler.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Fehler.schema.json#/properties/fehler")                                                  |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Statusbericht](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"STATUSBERICHT"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Statusbericht](statusbericht-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusbericht.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## status



`status`

*   is optional

*   Type: `string` ([BerichtStatus](berichtstatus.md))

*   cannot be null

*   defined in: [Statusbericht](berichtstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BerichtStatus.schema.json#/properties/status")

### status Type

`string` ([BerichtStatus](berichtstatus.md))

### status Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"ERFOLGREICH"` |             |
| `"FEHLER"`      |             |

## pruefgegenstand



`pruefgegenstand`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Statusbericht](statusbericht-properties-pruefgegenstand.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusbericht.schema.json#/properties/pruefgegenstand")

### pruefgegenstand Type

`string`

## datumPruefung



`datumPruefung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Statusbericht](statusbericht-properties-datumpruefung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusbericht.schema.json#/properties/datumPruefung")

### datumPruefung Type

`string`

### datumPruefung Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## fehler



`fehler`

*   is optional

*   Type: `object` ([Fehler](fehler.md))

*   cannot be null

*   defined in: [Statusbericht](fehler.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Fehler.schema.json#/properties/fehler")

### fehler Type

`object` ([Fehler](fehler.md))
