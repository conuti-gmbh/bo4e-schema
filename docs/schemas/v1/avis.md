## Untitled object in undefined Type

`object` ([Details](avis.md))

# Untitled object in undefined Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                          |
| :---------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                     | `string` | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                  |
| [versionStruktur](#versionstruktur) | `string` | Required | cannot be null | [Untitled schema](avis-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Avis.schema.json#/properties/versionStruktur") |
| [avisNummer](#avisnummer)           | `string` | Optional | cannot be null | [Untitled schema](avis-properties-avisnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Avis.schema.json#/properties/avisNummer")           |
| [avisTyp](#avistyp)                 | `string` | Optional | cannot be null | [Untitled schema](avistyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AvisTyp.schema.json#/properties/avisTyp")                            |
| [zuZahlen](#zuzahlen)               | `object` | Optional | cannot be null | [Untitled schema](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/zuZahlen")                              |
| [positionen](#positionen)           | `array`  | Optional | cannot be null | [Untitled schema](avis-properties-positionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Avis.schema.json#/properties/positionen")           |

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
"AVIS"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](avis-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Avis.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## avisNummer



`avisNummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](avis-properties-avisnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Avis.schema.json#/properties/avisNummer")

### avisNummer Type

`string`

## avisTyp



`avisTyp`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](avistyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AvisTyp.schema.json#/properties/avisTyp")

### avisTyp Type

`string`

### avisTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"ABGELEHNTE_FORDERUNG"` |             |
| `"ZAHLUNGSAVIS"`         |             |

## zuZahlen



`zuZahlen`

*   is optional

*   Type: `object` ([Details](betrag.md))

*   cannot be null

*   defined in: [Untitled schema](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/zuZahlen")

### zuZahlen Type

`object` ([Details](betrag.md))

## positionen



`positionen`

*   is optional

*   Type: `object[]` ([Details](avisposition.md))

*   cannot be null

*   defined in: [Untitled schema](avis-properties-positionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Avis.schema.json#/properties/positionen")

### positionen Type

`object[]` ([Details](avisposition.md))
