## Leistungskurvendefinition Type

`object` ([Leistungskurvendefinition](leistungskurvendefinition.md))

# Leistungskurvendefinition Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                              |
| :---------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                     | `string` | Required | cannot be null | [Leistungskurvendefinition](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                            |
| [versionStruktur](#versionstruktur) | `string` | Required | cannot be null | [Leistungskurvendefinition](leistungskurvendefinition-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/versionStruktur") |
| [beginndatum](#beginndatum)         | `string` | Optional | cannot be null | [Leistungskurvendefinition](leistungskurvendefinition-properties-beginndatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/beginndatum")         |
| [endedatum](#endedatum)             | `string` | Optional | cannot be null | [Leistungskurvendefinition](leistungskurvendefinition-properties-endedatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/endedatum")             |
| [version](#version)                 | `string` | Optional | cannot be null | [Leistungskurvendefinition](leistungskurvendefinition-properties-version.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/version")                 |
| [code](#code)                       | `string` | Optional | cannot be null | [Leistungskurvendefinition](leistungskurvendefinition-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/code")                       |
| [notwendigkeit](#notwendigkeit)     | `string` | Optional | cannot be null | [Leistungskurvendefinition](definitionennotwendigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DefinitionenNotwendigkeit.schema.json#/properties/notwendigkeit")                            |
| [leistungskurven](#leistungskurven) | `array`  | Optional | cannot be null | [Leistungskurvendefinition](leistungskurvendefinition-properties-leistungskurven.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/leistungskurven") |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Leistungskurvendefinition](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"LEISTUNGSKURVENDEFINITION"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Leistungskurvendefinition](leistungskurvendefinition-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## beginndatum

beginndatum

`beginndatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Leistungskurvendefinition](leistungskurvendefinition-properties-beginndatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/beginndatum")

### beginndatum Type

`string`

### beginndatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## endedatum

endedatum

`endedatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Leistungskurvendefinition](leistungskurvendefinition-properties-endedatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/endedatum")

### endedatum Type

`string`

### endedatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## version

version

`version`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Leistungskurvendefinition](leistungskurvendefinition-properties-version.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/version")

### version Type

`string`

### version Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## code

code

`code`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Leistungskurvendefinition](leistungskurvendefinition-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/code")

### code Type

`string`

## notwendigkeit

DefinitionenNotwendigkeit

`notwendigkeit`

*   is optional

*   Type: `string` ([DefinitionenNotwendigkeit](definitionennotwendigkeit.md))

*   cannot be null

*   defined in: [Leistungskurvendefinition](definitionennotwendigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DefinitionenNotwendigkeit.schema.json#/properties/notwendigkeit")

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

## leistungskurven

leistungskurven

`leistungskurven`

*   is optional

*   Type: `object[]` ([Leistungskurve](leistungskurve.md))

*   cannot be null

*   defined in: [Leistungskurvendefinition](leistungskurvendefinition-properties-leistungskurven.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Leistungskurvendefinition.schema.json#/properties/leistungskurven")

### leistungskurven Type

`object[]` ([Leistungskurve](leistungskurve.md))
