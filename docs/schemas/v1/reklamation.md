## Reklamation Type

`object` ([Reklamation](reklamation.md))

# Reklamation Properties

| Property                                                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                   |
| :-------------------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                           | `string` | Required | cannot be null | [Reklamation](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                               |
| [versionStruktur](#versionstruktur)                       | `string` | Required | cannot be null | [Reklamation](reklamation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/versionStruktur")                |
| [lokationsId](#lokationsid)                               | `string` | Optional | cannot be null | [Reklamation](reklamation-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/lokationsId")                        |
| [lokationsTyp](#lokationstyp)                             | `string` | Optional | cannot be null | [Reklamation](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")                                          |
| [obiskennzahl](#obiskennzahl)                             | `string` | Optional | cannot be null | [Reklamation](reklamation-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/obiskennzahl")                      |
| [zeitraumMesswertanfrage](#zeitraummesswertanfrage)       | `object` | Optional | cannot be null | [Reklamation](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitraumMesswertanfrage")                                        |
| [reklamationsgrund](#reklamationsgrund)                   | `string` | Optional | cannot be null | [Reklamation](reklamationsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Reklamationsgrund.schema.json#/properties/reklamationsgrund")                           |
| [reklamationsgrundBemerkung](#reklamationsgrundbemerkung) | `object` | Optional | cannot be null | [Reklamation](reklamationsgrundbemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ReklamationsgrundBemerkung.schema.json#/properties/reklamationsgrundBemerkung") |
| [konfiguration](#konfiguration)                           | `string` | Optional | cannot be null | [Reklamation](reklamation-properties-konfiguration.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/konfiguration")                    |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Reklamation](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"REKLAMATION"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Reklamation](reklamation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## lokationsId

Für welche Markt- oder Messlokation gilt diese Reklamation.

`lokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Reklamation](reklamation-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/lokationsId")

### lokationsId Type

`string`

## lokationsTyp

Lokationstyp

`lokationsTyp`

*   is optional

*   Type: `string` ([Lokationstyp](lokationstyp.md))

*   cannot be null

*   defined in: [Reklamation](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")

### lokationsTyp Type

`string` ([Lokationstyp](lokationstyp.md))

### lokationsTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"MALO"`                 |             |
| `"MELO"`                 |             |
| `"NELO"`                 |             |
| `"TECHNISCHE_RESSOURCE"` |             |

## obiskennzahl

OBIS-Kennzahl

`obiskennzahl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Reklamation](reklamation-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/obiskennzahl")

### obiskennzahl Type

`string`

## zeitraumMesswertanfrage



`zeitraumMesswertanfrage`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Reklamation](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitraumMesswertanfrage")

### zeitraumMesswertanfrage Type

`object` ([Zeitraum](zeitraum.md))

## reklamationsgrund

Reklamationsgrund

`reklamationsgrund`

*   is optional

*   Type: `string` ([Reklamationsgrund](reklamationsgrund.md))

*   cannot be null

*   defined in: [Reklamation](reklamationsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Reklamationsgrund.schema.json#/properties/reklamationsgrund")

### reklamationsgrund Type

`string` ([Reklamationsgrund](reklamationsgrund.md))

### reklamationsgrund Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                             | Explanation |
| :------------------------------------------------ | :---------- |
| `"WERTE_ZU_HOCH"`                                 |             |
| `"WERTE_ZU_NIEDRIG"`                              |             |
| `"WERTE_FEHLEN"`                                  |             |
| `"KONFIGURATION_WIRKT_NICHT"`                     |             |
| `"KONFIGURATION_WIRKT_TEILWEISE"`                 |             |
| `"WERTE_WERDEN_NICHT_NACH_VORGABEN_UEBERMITTELT"` |             |
| `"UEBERSICHT_FEHLT"`                              |             |
| `"UEBERSICHT_UNPLAUSIBEL"`                        |             |
| `"AUSGEROLLTE_DEFINITION_FEHLT"`                  |             |
| `"AUSGEROLLTE_DEFINITION_UNPLAUSIBEL"`            |             |

## reklamationsgrundBemerkung

Freitext für eine weitere Beschreibung des Reklamationsgrunds

`reklamationsgrundBemerkung`

*   is optional

*   Type: `object` ([ReklamationsgrundBemerkung](reklamationsgrundbemerkung.md))

*   cannot be null

*   defined in: [Reklamation](reklamationsgrundbemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ReklamationsgrundBemerkung.schema.json#/properties/reklamationsgrundBemerkung")

### reklamationsgrundBemerkung Type

`object` ([ReklamationsgrundBemerkung](reklamationsgrundbemerkung.md))

## konfiguration

konfiguration

`konfiguration`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Reklamation](reklamation-properties-konfiguration.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/konfiguration")

### konfiguration Type

`string`
