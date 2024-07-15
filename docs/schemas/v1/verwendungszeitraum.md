## Untitled object in undefined Type

`object` ([Details](verwendungszeitraum.md))

# Untitled object in undefined Properties

| Property                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                        |
| :---------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                     | `string`  | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                |
| [versionStruktur](#versionstruktur) | `string`  | Required | cannot be null | [Untitled schema](verwendungszeitraum-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/versionStruktur") |
| [verwendungAb](#verwendungab)       | `string`  | Optional | cannot be null | [Untitled schema](verwendungszeitraum-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/verwendungAb")       |
| [verwendungBis](#verwendungbis)     | `string`  | Optional | cannot be null | [Untitled schema](verwendungszeitraum-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/verwendungBis")     |
| [zeitraumId](#zeitraumid)           | `integer` | Optional | cannot be null | [Untitled schema](verwendungszeitraum-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/zeitraumId")           |
| [datenqualitaet](#datenqualitaet)   | `string`  | Optional | cannot be null | [Untitled schema](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                     |

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
"VERWENDUNGSZEITRAUM"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](verwendungszeitraum-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## verwendungAb



`verwendungAb`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](verwendungszeitraum-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/verwendungAb")

### verwendungAb Type

`string`

### verwendungAb Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## verwendungBis



`verwendungBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](verwendungszeitraum-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/verwendungBis")

### verwendungBis Type

`string`

### verwendungBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## zeitraumId



`zeitraumId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Untitled schema](verwendungszeitraum-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/zeitraumId")

### zeitraumId Type

`integer`

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
