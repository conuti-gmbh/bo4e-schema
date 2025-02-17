## WerteNachTyp2 Type

`object` ([WerteNachTyp2](wertenachtyp2.md))

# WerteNachTyp2 Properties

| Property                                                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                 |
| :-------------------------------------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                             | `string` | Required | cannot be null | [WerteNachTyp2](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                           |
| [versionStruktur](#versionstruktur)                                         | `string` | Required | cannot be null | [WerteNachTyp2](wertenachtyp2-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/WerteNachTyp2.schema.json#/properties/versionStruktur")                                        |
| [konfigurationsprodukt](#konfigurationsprodukt)                             | `string` | Optional | cannot be null | [WerteNachTyp2](wertenachtyp2-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/WerteNachTyp2.schema.json#/properties/konfigurationsprodukt")                            |
| [messprodukt](#messprodukt)                                                 | `string` | Optional | cannot be null | [WerteNachTyp2](wertenachtyp2-properties-messprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/WerteNachTyp2.schema.json#/properties/messprodukt")                                                |
| [zieladresse](#zieladresse)                                                 | `object` | Optional | cannot be null | [WerteNachTyp2](zieladresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zieladresse.schema.json#/properties/zieladresse")                                                                          |
| [aussteller](#aussteller)                                                   | `object` | Optional | cannot be null | [WerteNachTyp2](aussteller.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Aussteller.schema.json#/properties/aussteller")                                                                             |
| [zertifikatsNutzer](#zertifikatsnutzer)                                     | `object` | Optional | cannot be null | [WerteNachTyp2](zertifikatsnutzer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZertifikatsNutzer.schema.json#/properties/zertifikatsNutzer")                                                        |
| [aenderungsmoeglichkeitKonfiguration](#aenderungsmoeglichkeitkonfiguration) | `string` | Optional | cannot be null | [WerteNachTyp2](aenderungsmoeglichkeitkonfiguration.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AenderungsmoeglichkeitKonfiguration.schema.json#/properties/aenderungsmoeglichkeitKonfiguration") |
| [schwellwerte](#schwellwerte)                                               | `array`  | Optional | can be null    | [WerteNachTyp2](wertenachtyp2-properties-schwellwerte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/WerteNachTyp2.schema.json#/properties/schwellwerte")                                              |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [WerteNachTyp2](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"WERTE_NACH_TYP2"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [WerteNachTyp2](wertenachtyp2-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/WerteNachTyp2.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## konfigurationsprodukt

konfigurationsprodukt

`konfigurationsprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [WerteNachTyp2](wertenachtyp2-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/WerteNachTyp2.schema.json#/properties/konfigurationsprodukt")

### konfigurationsprodukt Type

`string`

## messprodukt

messprodukt

`messprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [WerteNachTyp2](wertenachtyp2-properties-messprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/WerteNachTyp2.schema.json#/properties/messprodukt")

### messprodukt Type

`string`

## zieladresse



`zieladresse`

*   is optional

*   Type: `object` ([Zieladresse](zieladresse.md))

*   cannot be null

*   defined in: [WerteNachTyp2](zieladresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zieladresse.schema.json#/properties/zieladresse")

### zieladresse Type

`object` ([Zieladresse](zieladresse.md))

## aussteller



`aussteller`

*   is optional

*   Type: `object` ([Aussteller](aussteller.md))

*   cannot be null

*   defined in: [WerteNachTyp2](aussteller.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Aussteller.schema.json#/properties/aussteller")

### aussteller Type

`object` ([Aussteller](aussteller.md))

## zertifikatsNutzer



`zertifikatsNutzer`

*   is optional

*   Type: `object` ([ZertifikatsNutzer](zertifikatsnutzer.md))

*   cannot be null

*   defined in: [WerteNachTyp2](zertifikatsnutzer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZertifikatsNutzer.schema.json#/properties/zertifikatsNutzer")

### zertifikatsNutzer Type

`object` ([ZertifikatsNutzer](zertifikatsnutzer.md))

## aenderungsmoeglichkeitKonfiguration

AenderungsmoeglichkeitKonfiguration

`aenderungsmoeglichkeitKonfiguration`

*   is optional

*   Type: `string` ([AenderungsmoeglichkeitKonfiguration](aenderungsmoeglichkeitkonfiguration.md))

*   cannot be null

*   defined in: [WerteNachTyp2](aenderungsmoeglichkeitkonfiguration.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AenderungsmoeglichkeitKonfiguration.schema.json#/properties/aenderungsmoeglichkeitKonfiguration")

### aenderungsmoeglichkeitKonfiguration Type

`string` ([AenderungsmoeglichkeitKonfiguration](aenderungsmoeglichkeitkonfiguration.md))

### aenderungsmoeglichkeitKonfiguration Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                  | Explanation |
| :--------------------- | :---------- |
| `"ERFORDERLICH"`       |             |
| `"NICHT_ERFORDERLICH"` |             |

## schwellwerte

schwellwerte

`schwellwerte`

*   is optional

*   Type: `object[]` ([Schwellwert](schwellwert.md))

*   can be null

*   defined in: [WerteNachTyp2](wertenachtyp2-properties-schwellwerte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/WerteNachTyp2.schema.json#/properties/schwellwerte")

### schwellwerte Type

`object[]` ([Schwellwert](schwellwert.md))
