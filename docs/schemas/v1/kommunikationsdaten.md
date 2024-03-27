## Untitled object in undefined Type

`object` ([Details](kommunikationsdaten.md))

# Untitled object in undefined Properties

| Property                                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                        |
| :------------------------------------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [boTyp](#botyp)                                                     | `string`  | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                                |
| [versionStruktur](#versionstruktur)                                 | `string`  | Required | cannot be null | [Untitled schema](kommunikationsdaten-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Kommunikationsdaten.schema.json#/properties/versionStruktur")                                 |
| [gueltigkeit](#gueltigkeit)                                         | `string`  | Optional | cannot be null | [Untitled schema](kommunikationsdaten-properties-gueltigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Kommunikationsdaten.schema.json#/properties/gueltigkeit")                                         |
| [kommunikationsDatenBlattInaktiv](#kommunikationsdatenblattinaktiv) | `boolean` | Optional | cannot be null | [Untitled schema](kommunikationsdaten-properties-kommunikationsdatenblattinaktiv.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Kommunikationsdaten.schema.json#/properties/kommunikationsDatenBlattInaktiv") |
| [marktteilnehmer](#marktteilnehmer)                                 | `object`  | Optional | cannot be null | [Untitled schema](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/marktteilnehmer")                                                                    |
| [kommunikationsangaben](#kommunikationsangaben)                     | `array`   | Optional | cannot be null | [Untitled schema](kommunikationsdaten-properties-kommunikationsangaben.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Kommunikationsdaten.schema.json#/properties/kommunikationsangaben")                     |

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

### boTyp Default Value

The default value is:

```json
"KOMMUNIKATIONSDATEN"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](kommunikationsdaten-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Kommunikationsdaten.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## gueltigkeit



`gueltigkeit`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](kommunikationsdaten-properties-gueltigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Kommunikationsdaten.schema.json#/properties/gueltigkeit")

### gueltigkeit Type

`string`

### gueltigkeit Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## kommunikationsDatenBlattInaktiv



`kommunikationsDatenBlattInaktiv`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Untitled schema](kommunikationsdaten-properties-kommunikationsdatenblattinaktiv.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Kommunikationsdaten.schema.json#/properties/kommunikationsDatenBlattInaktiv")

### kommunikationsDatenBlattInaktiv Type

`boolean`

## marktteilnehmer



`marktteilnehmer`

*   is optional

*   Type: `object` ([Details](marktteilnehmer.md))

*   cannot be null

*   defined in: [Untitled schema](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/marktteilnehmer")

### marktteilnehmer Type

`object` ([Details](marktteilnehmer.md))

## kommunikationsangaben



`kommunikationsangaben`

*   is optional

*   Type: `object[]` ([Details](marktteilnehmer.md))

*   cannot be null

*   defined in: [Untitled schema](kommunikationsdaten-properties-kommunikationsangaben.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Kommunikationsdaten.schema.json#/properties/kommunikationsangaben")

### kommunikationsangaben Type

`object[]` ([Details](marktteilnehmer.md))
