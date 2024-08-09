## Verwendungszeitraum Type

`object` ([Verwendungszeitraum](verwendungszeitraum.md))

# Verwendungszeitraum Properties

| Property                                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                          |
| :------------------------------------------------ | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                   | `string`  | Required | cannot be null | [Verwendungszeitraum](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                              |
| [versionStruktur](#versionstruktur)               | `string`  | Required | cannot be null | [Verwendungszeitraum](verwendungszeitraum-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/versionStruktur")               |
| [verwendungAb](#verwendungab)                     | `string`  | Optional | cannot be null | [Verwendungszeitraum](verwendungszeitraum-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/verwendungAb")                     |
| [verwendungBis](#verwendungbis)                   | `string`  | Optional | cannot be null | [Verwendungszeitraum](verwendungszeitraum-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/verwendungBis")                   |
| [zeitraumId](#zeitraumid)                         | `integer` | Optional | cannot be null | [Verwendungszeitraum](verwendungszeitraum-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/zeitraumId")                         |
| [datenqualitaet](#datenqualitaet)                 | `string`  | Optional | cannot be null | [Verwendungszeitraum](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                                   |
| [freitext](#freitext)                             | `object`  | Optional | cannot be null | [Verwendungszeitraum](freitext.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Freitext.schema.json#/properties/freitext")                                                                      |
| [antwortstatus](#antwortstatus)                   | `string`  | Optional | cannot be null | [Verwendungszeitraum](verwendungszeitraum-properties-antwortstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/antwortstatus")                   |
| [antwortstatusCodeliste](#antwortstatuscodeliste) | `string`  | Optional | cannot be null | [Verwendungszeitraum](verwendungszeitraum-properties-antwortstatuscodeliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/antwortstatusCodeliste") |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Verwendungszeitraum](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"VERWENDUNGSZEITRAUM"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Verwendungszeitraum](verwendungszeitraum-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/versionStruktur")

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

*   defined in: [Verwendungszeitraum](verwendungszeitraum-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/verwendungAb")

### verwendungAb Type

`string`

### verwendungAb Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## verwendungBis



`verwendungBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verwendungszeitraum](verwendungszeitraum-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/verwendungBis")

### verwendungBis Type

`string`

### verwendungBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## zeitraumId



`zeitraumId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Verwendungszeitraum](verwendungszeitraum-properties-zeitraumid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/zeitraumId")

### zeitraumId Type

`integer`

## datenqualitaet



`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Verwendungszeitraum](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

### datenqualitaet Type

`string` ([Datenqualitaet](datenqualitaet.md))

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

## freitext



`freitext`

*   is optional

*   Type: `object` ([Freitext](freitext.md))

*   cannot be null

*   defined in: [Verwendungszeitraum](freitext.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Freitext.schema.json#/properties/freitext")

### freitext Type

`object` ([Freitext](freitext.md))

## antwortstatus



`antwortstatus`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verwendungszeitraum](verwendungszeitraum-properties-antwortstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/antwortstatus")

### antwortstatus Type

`string`

## antwortstatusCodeliste



`antwortstatusCodeliste`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Verwendungszeitraum](verwendungszeitraum-properties-antwortstatuscodeliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Verwendungszeitraum.schema.json#/properties/antwortstatusCodeliste")

### antwortstatusCodeliste Type

`string`
