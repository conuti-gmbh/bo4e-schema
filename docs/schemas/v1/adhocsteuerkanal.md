## AdHocSteuerkanal Type

`object` ([AdHocSteuerkanal](adhocsteuerkanal.md))

# AdHocSteuerkanal Properties

| Property                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                               |
| :---------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                 | `string` | Required | cannot be null | [AdHocSteuerkanal](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                      |
| [versionStruktur](#versionstruktur)             | `string` | Required | cannot be null | [AdHocSteuerkanal](adhocsteuerkanal-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/AdHocSteuerkanal.schema.json#/properties/versionStruktur")             |
| [konfigurationsprodukt](#konfigurationsprodukt) | `string` | Optional | cannot be null | [AdHocSteuerkanal](adhocsteuerkanal-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/AdHocSteuerkanal.schema.json#/properties/konfigurationsprodukt") |
| [zieladresse](#zieladresse)                     | `object` | Optional | cannot be null | [AdHocSteuerkanal](zieladresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zieladresse.schema.json#/properties/zieladresse")                                                     |
| [aussteller](#aussteller)                       | `object` | Optional | cannot be null | [AdHocSteuerkanal](aussteller.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Aussteller.schema.json#/properties/aussteller")                                                        |
| [zertifikatsNutzer](#zertifikatsnutzer)         | `object` | Optional | cannot be null | [AdHocSteuerkanal](zertifikatsnutzer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZertifikatsNutzer.schema.json#/properties/zertifikatsNutzer")                                   |
| [IPAdresseCLSDevice](#ipadresseclsdevice)       | `object` | Optional | cannot be null | [AdHocSteuerkanal](ipadresseclsdevice.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/IPAdresseCLSDevice.schema.json#/properties/IPAdresseCLSDevice")                                |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [AdHocSteuerkanal](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"AD_HOC_STEUERKANAL"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [AdHocSteuerkanal](adhocsteuerkanal-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/AdHocSteuerkanal.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## konfigurationsprodukt



`konfigurationsprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AdHocSteuerkanal](adhocsteuerkanal-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/AdHocSteuerkanal.schema.json#/properties/konfigurationsprodukt")

### konfigurationsprodukt Type

`string`

## zieladresse



`zieladresse`

*   is optional

*   Type: `object` ([Zieladresse](zieladresse.md))

*   cannot be null

*   defined in: [AdHocSteuerkanal](zieladresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zieladresse.schema.json#/properties/zieladresse")

### zieladresse Type

`object` ([Zieladresse](zieladresse.md))

## aussteller



`aussteller`

*   is optional

*   Type: `object` ([Aussteller](aussteller.md))

*   cannot be null

*   defined in: [AdHocSteuerkanal](aussteller.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Aussteller.schema.json#/properties/aussteller")

### aussteller Type

`object` ([Aussteller](aussteller.md))

## zertifikatsNutzer



`zertifikatsNutzer`

*   is optional

*   Type: `object` ([ZertifikatsNutzer](zertifikatsnutzer.md))

*   cannot be null

*   defined in: [AdHocSteuerkanal](zertifikatsnutzer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZertifikatsNutzer.schema.json#/properties/zertifikatsNutzer")

### zertifikatsNutzer Type

`object` ([ZertifikatsNutzer](zertifikatsnutzer.md))

## IPAdresseCLSDevice



`IPAdresseCLSDevice`

*   is optional

*   Type: `object` ([IPAdresseCLSDevice](ipadresseclsdevice.md))

*   cannot be null

*   defined in: [AdHocSteuerkanal](ipadresseclsdevice.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/IPAdresseCLSDevice.schema.json#/properties/IPAdresseCLSDevice")

### IPAdresseCLSDevice Type

`object` ([IPAdresseCLSDevice](ipadresseclsdevice.md))
