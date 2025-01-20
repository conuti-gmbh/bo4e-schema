## Ansprechpartner Type

`object` ([Ansprechpartner](ansprechpartner.md))

# Ansprechpartner Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                |
| :---------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                     | `string` | Required | cannot be null | [Ansprechpartner](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                        |
| [versionStruktur](#versionstruktur) | `string` | Required | cannot be null | [Ansprechpartner](ansprechpartner-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/versionStruktur") |
| [nachname](#nachname)               | `string` | Optional | cannot be null | [Ansprechpartner](ansprechpartner-properties-nachname.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/nachname")               |
| [eMailAdresse](#emailadresse)       | `string` | Optional | cannot be null | [Ansprechpartner](ansprechpartner-properties-emailadresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/eMailAdresse")       |
| [rufnummern](#rufnummern)           | `array`  | Optional | cannot be null | [Ansprechpartner](ansprechpartner-properties-rufnummern.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/rufnummern")           |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Ansprechpartner](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"ANSPRECHPARTNER"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Ansprechpartner](ansprechpartner-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## nachname

Nachname (Familienname) des Ansprechpartners

`nachname`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Ansprechpartner](ansprechpartner-properties-nachname.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/nachname")

### nachname Type

`string`

## eMailAdresse

E-Mail Adresse

`eMailAdresse`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Ansprechpartner](ansprechpartner-properties-emailadresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/eMailAdresse")

### eMailAdresse Type

`string`

## rufnummern

Liste der Telefonnummern, unter denen der Ansprechpartner erreichbar ist.

`rufnummern`

*   is optional

*   Type: `object[]` ([Rufnummer](rufnummer.md))

*   cannot be null

*   defined in: [Ansprechpartner](ansprechpartner-properties-rufnummern.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/rufnummern")

### rufnummern Type

`object[]` ([Rufnummer](rufnummer.md))
