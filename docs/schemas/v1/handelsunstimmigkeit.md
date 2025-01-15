## Handelsunstimmigkeit Type

`object` ([Handelsunstimmigkeit](handelsunstimmigkeit.md))

# Handelsunstimmigkeit Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                               |
| :---------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                     | `string` | Required | cannot be null | [Handelsunstimmigkeit](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                  |
| [versionStruktur](#versionstruktur) | `string` | Required | cannot be null | [Handelsunstimmigkeit](handelsunstimmigkeit-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Handelsunstimmigkeit.schema.json#/properties/versionStruktur") |
| [nummer](#nummer)                   | `string` | Optional | cannot be null | [Handelsunstimmigkeit](handelsunstimmigkeit-properties-nummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Handelsunstimmigkeit.schema.json#/properties/nummer")                   |
| [typ](#typ)                         | `string` | Optional | cannot be null | [Handelsunstimmigkeit](handelsunstimmigkeitstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Handelsunstimmigkeitstyp.schema.json#/properties/typ")                              |
| [begruendung](#begruendung)         | `object` | Optional | cannot be null | [Handelsunstimmigkeit](handelsunstimmigkeitsbegruendung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/begruendung")       |
| [zuZahlen](#zuzahlen)               | `object` | Optional | cannot be null | [Handelsunstimmigkeit](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/zuZahlen")                                                              |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Handelsunstimmigkeit](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"HANDELSUNSTIMMIGKEIT"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Handelsunstimmigkeit](handelsunstimmigkeit-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Handelsunstimmigkeit.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## nummer

Handelsunstimmigkeitsnummer

`nummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Handelsunstimmigkeit](handelsunstimmigkeit-properties-nummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Handelsunstimmigkeit.schema.json#/properties/nummer")

### nummer Type

`string`

## typ

Gibt den Typ der Handelsunstimmigkeit an.

`typ`

*   is optional

*   Type: `string` ([Handelsunstimmigkeitstyp](handelsunstimmigkeitstyp.md))

*   cannot be null

*   defined in: [Handelsunstimmigkeit](handelsunstimmigkeitstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Handelsunstimmigkeitstyp.schema.json#/properties/typ")

### typ Type

`string` ([Handelsunstimmigkeitstyp](handelsunstimmigkeitstyp.md))

### typ Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                     | Explanation |
| :---------------------------------------- | :---------- |
| `"HANDELSRECHNUNG"`                       |             |
| `"LIEFERSCHEIN_HANDELSUNSTIMMIGKEITSTYP"` |             |
| `"LIEFERSCHEIN_GRUND_ARBEITSPREIS"`       |             |
| `"LIEFERSCHEIN_ARBEITS_LEISTUNGSPREIS"`   |             |

## begruendung

Handelsunstimmigskeitsbegründung

`begruendung`

*   is optional

*   Type: `object` ([Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung.md))

*   cannot be null

*   defined in: [Handelsunstimmigkeit](handelsunstimmigkeitsbegruendung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/begruendung")

### begruendung Type

`object` ([Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung.md))

## zuZahlen

angeforderter Betrag

`zuZahlen`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Handelsunstimmigkeit](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/zuZahlen")

### zuZahlen Type

`object` ([Betrag](betrag.md))
