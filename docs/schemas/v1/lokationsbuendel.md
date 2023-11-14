## Untitled object in undefined Type

`object` ([Details](lokationsbuendel.md))

# Untitled object in undefined Properties

| Property                                                                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                    |
| :------------------------------------------------------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [boTyp](#botyp)                                                                       | `string`  | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                                            |
| [versionStruktur](#versionstruktur)                                                   | `string`  | Required | cannot be null | [Untitled schema](lokationsbuendel-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/versionStruktur")                                                   |
| [lokationsbuendelstrukturId](#lokationsbuendelstrukturid)                             | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-lokationsbuendelstrukturid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelstrukturId")                             |
| [lokationsbuendelNummer](#lokationsbuendelnummer)                                     | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-lokationsbuendelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelNummer")                                     |
| [standardisierteLokationsbuendelstruktur](#standardisiertelokationsbuendelstruktur)   | `boolean` | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-standardisiertelokationsbuendelstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/standardisierteLokationsbuendelstruktur")   |
| [objectcode](#objectcode)                                                             | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-objectcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/objectcode")                                                             |
| [referenzMarktlokation](#referenzmarktlokation)                                       | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-referenzmarktlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzMarktlokation")                                       |
| [referenzMesslokation](#referenzmesslokation)                                         | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-referenzmesslokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzMesslokation")                                         |
| [referenzNetzlokation](#referenznetzlokation)                                         | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-referenznetzlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzNetzlokation")                                         |
| [referenzTechnischeRessource](#referenztechnischeressource)                           | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-referenztechnischeressource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzTechnischeRessource")                           |
| [vorgelagerteMesslokation](#vorgelagertemesslokation)                                 | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-vorgelagertemesslokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/vorgelagerteMesslokation")                                 |
| [vorgelagerteNetzlokation](#vorgelagertenetzlokation)                                 | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-vorgelagertenetzlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/vorgelagerteNetzlokation")                                 |
| [referenzMarktlokationTechnischeRessource](#referenzmarktlokationtechnischeressource) | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-referenzmarktlokationtechnischeressource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzMarktlokationTechnischeRessource") |

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
| `"AD_HOC_STEUERKANAL"`          |             |
| `"LOKATIONSBUENDEL"`            |             |

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

## lokationsbuendelstrukturId



`lokationsbuendelstrukturId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-lokationsbuendelstrukturid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelstrukturId")

### lokationsbuendelstrukturId Type

`string`

## lokationsbuendelNummer



`lokationsbuendelNummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-lokationsbuendelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelNummer")

### lokationsbuendelNummer Type

`string`

## standardisierteLokationsbuendelstruktur



`standardisierteLokationsbuendelstruktur`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-standardisiertelokationsbuendelstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/standardisierteLokationsbuendelstruktur")

### standardisierteLokationsbuendelstruktur Type

`boolean`

## objectcode



`objectcode`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-objectcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/objectcode")

### objectcode Type

`string`

## referenzMarktlokation



`referenzMarktlokation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-referenzmarktlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzMarktlokation")

### referenzMarktlokation Type

`string`

## referenzMesslokation



`referenzMesslokation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-referenzmesslokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzMesslokation")

### referenzMesslokation Type

`string`

## referenzNetzlokation



`referenzNetzlokation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-referenznetzlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzNetzlokation")

### referenzNetzlokation Type

`string`

## referenzTechnischeRessource



`referenzTechnischeRessource`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-referenztechnischeressource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzTechnischeRessource")

### referenzTechnischeRessource Type

`string`

## vorgelagerteMesslokation



`vorgelagerteMesslokation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-vorgelagertemesslokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/vorgelagerteMesslokation")

### vorgelagerteMesslokation Type

`string`

## vorgelagerteNetzlokation



`vorgelagerteNetzlokation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-vorgelagertenetzlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/vorgelagerteNetzlokation")

### vorgelagerteNetzlokation Type

`string`

## referenzMarktlokationTechnischeRessource



`referenzMarktlokationTechnischeRessource`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-referenzmarktlokationtechnischeressource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/referenzMarktlokationTechnischeRessource")

### referenzMarktlokationTechnischeRessource Type

`string`
