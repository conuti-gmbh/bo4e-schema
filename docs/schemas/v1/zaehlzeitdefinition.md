## Zaehlzeitdefinition Type

`object` ([Zaehlzeitdefinition](zaehlzeitdefinition.md))

# Zaehlzeitdefinition Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                |
| :-------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [boTyp](#botyp)                         | `string` | Required | cannot be null | [Zaehlzeitdefinition](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                    |
| [versionStruktur](#versionstruktur)     | `string` | Required | cannot be null | [Zaehlzeitdefinition](zaehlzeitdefinition-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/versionStruktur")     |
| [beginndatum](#beginndatum)             | `string` | Optional | cannot be null | [Zaehlzeitdefinition](zaehlzeitdefinition-properties-beginndatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/beginndatum")             |
| [endedatum](#endedatum)                 | `string` | Optional | cannot be null | [Zaehlzeitdefinition](zaehlzeitdefinition-properties-endedatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/endedatum")                 |
| [version](#version)                     | `string` | Optional | cannot be null | [Zaehlzeitdefinition](zaehlzeitdefinition-properties-version.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/version")                     |
| [notwendigkeit](#notwendigkeit)         | `string` | Optional | cannot be null | [Zaehlzeitdefinition](definitionennotwendigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DefinitionenNotwendigkeit.schema.json#/properties/notwendigkeit")                    |
| [versionsangabe](#versionsangabe)       | `string` | Optional | cannot be null | [Zaehlzeitdefinition](zaehlzeitdefinition-properties-versionsangabe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/versionsangabe")       |
| [code](#code)                           | `string` | Optional | cannot be null | [Zaehlzeitdefinition](zaehlzeitdefinition-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/code")                           |
| [zaehlzeiten](#zaehlzeiten)             | `array`  | Optional | cannot be null | [Zaehlzeitdefinition](zaehlzeitdefinition-properties-zaehlzeiten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/zaehlzeiten")             |
| [zaehlzeitregister](#zaehlzeitregister) | `array`  | Optional | cannot be null | [Zaehlzeitdefinition](zaehlzeitdefinition-properties-zaehlzeitregister.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/zaehlzeitregister") |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Zaehlzeitdefinition](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"ZAEHLZEITDEFINITION"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeitdefinition](zaehlzeitdefinition-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## beginndatum



`beginndatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeitdefinition](zaehlzeitdefinition-properties-beginndatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/beginndatum")

### beginndatum Type

`string`

### beginndatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## endedatum



`endedatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeitdefinition](zaehlzeitdefinition-properties-endedatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/endedatum")

### endedatum Type

`string`

### endedatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## version



`version`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeitdefinition](zaehlzeitdefinition-properties-version.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/version")

### version Type

`string`

### version Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## notwendigkeit



`notwendigkeit`

*   is optional

*   Type: `string` ([DefinitionenNotwendigkeit](definitionennotwendigkeit.md))

*   cannot be null

*   defined in: [Zaehlzeitdefinition](definitionennotwendigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DefinitionenNotwendigkeit.schema.json#/properties/notwendigkeit")

### notwendigkeit Type

`string` ([DefinitionenNotwendigkeit](definitionennotwendigkeit.md))

### notwendigkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                            | Explanation |
| :----------------------------------------------- | :---------- |
| `"ZAEHLZEITDEFINITIONEN_WERDEN_VERWENDET"`       |             |
| `"ZAEHLZEITDEFINITIONEN_WERDEN_NICHT_VERWENDET"` |             |
| `"DEFINITIONEN_WERDEN_VERWENDET"`                |             |
| `"DEFINITIONEN_WERDEN_NICHT_VERWENDET"`          |             |

## versionsangabe



`versionsangabe`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeitdefinition](zaehlzeitdefinition-properties-versionsangabe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/versionsangabe")

### versionsangabe Type

`string`

## code



`code`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeitdefinition](zaehlzeitdefinition-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/code")

### code Type

`string`

## zaehlzeiten



`zaehlzeiten`

*   is optional

*   Type: `object[]` ([Zaehlzeit](zaehlzeit.md))

*   cannot be null

*   defined in: [Zaehlzeitdefinition](zaehlzeitdefinition-properties-zaehlzeiten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/zaehlzeiten")

### zaehlzeiten Type

`object[]` ([Zaehlzeit](zaehlzeit.md))

## zaehlzeitregister



`zaehlzeitregister`

*   is optional

*   Type: `object[]` ([Zaehlzeitregister](zaehlzeitregister.md))

*   cannot be null

*   defined in: [Zaehlzeitdefinition](zaehlzeitdefinition-properties-zaehlzeitregister.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehlzeitdefinition.schema.json#/properties/zaehlzeitregister")

### zaehlzeitregister Type

`object[]` ([Zaehlzeitregister](zaehlzeitregister.md))
