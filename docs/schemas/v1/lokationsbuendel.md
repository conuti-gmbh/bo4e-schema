## Lokationsbuendel Type

`object` ([Lokationsbuendel](lokationsbuendel.md))

# Lokationsbuendel Properties

| Property                                                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :---------------------------------------------------------------------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                                     | `string`  | Required | cannot be null | [Lokationsbuendel](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                                          |
| [versionStruktur](#versionstruktur)                                                 | `string`  | Required | cannot be null | [Lokationsbuendel](lokationsbuendel-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/versionStruktur")                                                 |
| [lokationsbuendelstrukturId](#lokationsbuendelstrukturid)                           | `string`  | Optional | cannot be null | [Lokationsbuendel](lokationsbuendel-properties-lokationsbuendelstrukturid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelstrukturId")                           |
| [lokationsbuendelNummer](#lokationsbuendelnummer)                                   | `integer` | Optional | cannot be null | [Lokationsbuendel](lokationsbuendel-properties-lokationsbuendelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelNummer")                                   |
| [standardisierteLokationsbuendelstruktur](#standardisiertelokationsbuendelstruktur) | `boolean` | Optional | cannot be null | [Lokationsbuendel](lokationsbuendel-properties-standardisiertelokationsbuendelstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/standardisierteLokationsbuendelstruktur") |
| [datenqualitaet](#datenqualitaet)                                                   | `string`  | Optional | cannot be null | [Lokationsbuendel](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                                                               |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum)                                       | `object`  | Optional | cannot be null | [Lokationsbuendel](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                                                                      |
| [zuordnungObjectcode](#zuordnungobjectcode)                                         | `array`   | Optional | cannot be null | [Lokationsbuendel](lokationsbuendel-properties-zuordnungobjectcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/zuordnungObjectcode")                                         |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Lokationsbuendel](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"LOKATIONSBUENDEL"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Lokationsbuendel](lokationsbuendel-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## lokationsbuendelstrukturId

lokationsbuendelstrukturId

`lokationsbuendelstrukturId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lokationsbuendel](lokationsbuendel-properties-lokationsbuendelstrukturid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelstrukturId")

### lokationsbuendelstrukturId Type

`string`

## lokationsbuendelNummer

lokationsbuendelNummer

`lokationsbuendelNummer`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Lokationsbuendel](lokationsbuendel-properties-lokationsbuendelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/lokationsbuendelNummer")

### lokationsbuendelNummer Type

`integer`

## standardisierteLokationsbuendelstruktur

standardisierteLokationsbuendelstruktur

`standardisierteLokationsbuendelstruktur`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Lokationsbuendel](lokationsbuendel-properties-standardisiertelokationsbuendelstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/standardisierteLokationsbuendelstruktur")

### standardisierteLokationsbuendelstruktur Type

`boolean`

## datenqualitaet

Datenqualitaet

`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Lokationsbuendel](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

### datenqualitaet Type

`string` ([Datenqualitaet](datenqualitaet.md))

### datenqualitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                    | Explanation |
| :--------------------------------------- | :---------- |
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

## gueltigkeitszeitraum



`gueltigkeitszeitraum`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Lokationsbuendel](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))

## zuordnungObjectcode

zuordnungObjectcode

`zuordnungObjectcode`

*   is optional

*   Type: `object[]` ([ZuordnungObjectcode](zuordnungobjectcode.md))

*   cannot be null

*   defined in: [Lokationsbuendel](lokationsbuendel-properties-zuordnungobjectcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Lokationsbuendel.schema.json#/properties/zuordnungObjectcode")

### zuordnungObjectcode Type

`object[]` ([ZuordnungObjectcode](zuordnungobjectcode.md))
