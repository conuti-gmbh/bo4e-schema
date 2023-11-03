## Untitled object in undefined Type

`object` ([Details](netzlokation.md))

# Untitled object in undefined Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                          |
| :---------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                     | `string` | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                  |
| [versionStruktur](#versionstruktur) | `string` | Required | cannot be null | [Untitled schema](netzlokation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/versionStruktur") |
| [netzlokationsId](#netzlokationsid) | `string` | Optional | cannot be null | [Untitled schema](netzlokation-properties-netzlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/netzlokationsId") |
| [sparte](#sparte)                   | `string` | Optional | cannot be null | [Untitled schema](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                               |
| [zaehlwerke](#zaehlwerke)           | `array`  | Optional | cannot be null | [Untitled schema](netzlokation-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/zaehlwerke")           |

## boTyp



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

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](netzlokation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

## netzlokationsId



`netzlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](netzlokation-properties-netzlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/netzlokationsId")

### netzlokationsId Type

`string`

## sparte



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

## zaehlwerke



`zaehlwerke`

*   is optional

*   Type: `object[]` ([Details](zaehlwerk.md))

*   cannot be null

*   defined in: [Untitled schema](netzlokation-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/zaehlwerke")

### zaehlwerke Type

`object[]` ([Details](zaehlwerk.md))
