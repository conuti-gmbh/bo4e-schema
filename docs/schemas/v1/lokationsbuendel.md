## Untitled object in undefined Type

`object` ([Details](lokationsbuendel.md))

# Untitled object in undefined Properties

| Property                                                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                  |
| :---------------------------------------------------------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                                     | `string`  | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                                          |
| [versionStruktur](#versionstruktur)                                                 | `string`  | Required | cannot be null | [Untitled schema](lokationsbuendel-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/versionStruktur")                                                 |
| [lokationsbuendelstrukturId](#lokationsbuendelstrukturid)                           | `string`  | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-lokationsbuendelstrukturid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelstrukturId")                           |
| [lokationsbuendelNummer](#lokationsbuendelnummer)                                   | `integer` | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-lokationsbuendelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelNummer")                                   |
| [standardisierteLokationsbuendelstruktur](#standardisiertelokationsbuendelstruktur) | `boolean` | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-standardisiertelokationsbuendelstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/standardisierteLokationsbuendelstruktur") |
| [datenqualitaet](#datenqualitaet)                                                   | `string`  | Optional | cannot be null | [Untitled schema](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                                                               |
| [zeitraumId](#zeitraumid)                                                           | `integer` | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/zeitraumId")                                                           |
| [zuordnungObjectcode](#zuordnungobjectcode)                                         | `array`   | Optional | cannot be null | [Untitled schema](lokationsbuendel-properties-zuordnungobjectcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/zuordnungObjectcode")                                         |

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
"LOKATIONSBUENDEL"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

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

*   Type: `integer`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-lokationsbuendelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelNummer")

### lokationsbuendelNummer Type

`integer`

## standardisierteLokationsbuendelstruktur



`standardisierteLokationsbuendelstruktur`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-standardisiertelokationsbuendelstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/standardisierteLokationsbuendelstruktur")

### standardisierteLokationsbuendelstruktur Type

`boolean`

## datenqualitaet



`datenqualitaet`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

### datenqualitaet Type

`string`

### datenqualitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                    | Explanation |
| :--------------------------------------- | :---------- |
| `"DATEN"`                                |             |
| `"ERWARTETE_DATEN"`                      |             |
| `"IM_SYSTEM_VORHANDENE_DATEN"`           |             |
| `"INFORMATIVE_DATEN"`                    |             |
| `"GUELTIGE_DATEN"`                       |             |
| `"KEINE_DATEN"`                          |             |
| `"IM_SYSTEM_KEINE_DATEN_VORHANDEN"`      |             |
| `"KEINE_DATEN_ERWARTET"`                 |             |
| `"DIFFERENZ_DATEN"`                      |             |
| `"DIFFERENZ_ERWARTETE_DATEN"`            |             |
| `"DIFFERENZ_IM_SYSTEM_VORHANDENE_DATEN"` |             |

## zeitraumId



`zeitraumId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/zeitraumId")

### zeitraumId Type

`integer`

## zuordnungObjectcode



`zuordnungObjectcode`

*   is optional

*   Type: `object[]` ([Details](zuordnungobjectcode.md))

*   cannot be null

*   defined in: [Untitled schema](lokationsbuendel-properties-zuordnungobjectcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/zuordnungObjectcode")

### zuordnungObjectcode Type

`object[]` ([Details](zuordnungobjectcode.md))
