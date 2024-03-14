## Untitled object in undefined Type

`object` ([Details](preisblatt.md))

# Untitled object in undefined Properties

| Property                                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                                            |
| :---------------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                           | `string`  | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                    |
| [versionStruktur](#versionstruktur)       | `string`  | Required | cannot be null | [Untitled schema](preisblatt-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/versionStruktur")       |
| [bezeichnung](#bezeichnung)               | `string`  | Optional | cannot be null | [Untitled schema](preisblatt-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/bezeichnung")               |
| [gueltigkeit](#gueltigkeit)               | `object`  | Optional | cannot be null | [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeit")                                         |
| [preisstatus](#preisstatus)               | `string`  | Optional | cannot be null | [Untitled schema](preisstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Preisstatus.schema.json#/properties/preisstatus")                                  |
| [sparte](#sparte)                         | `string`  | Optional | cannot be null | [Untitled schema](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                                 |
| [bilanzierungsdatum](#bilanzierungsdatum) | `string`  | Optional | cannot be null | [Untitled schema](preisblatt-properties-bilanzierungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/bilanzierungsdatum") |
| [regelzone](#regelzone)                   | `string`  | Optional | cannot be null | [Untitled schema](preisblatt-properties-regelzone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/regelzone")                   |
| [leistungstyp](#leistungstyp)             | `string`  | Optional | cannot be null | [Untitled schema](leistungstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Leistungstyp.schema.json#/properties/leistungstyp")                               |
| [nichtGenutzt](#nichtgenutzt)             | `boolean` | Optional | cannot be null | [Untitled schema](preisblatt-properties-nichtgenutzt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/nichtGenutzt")             |
| [preispositionen](#preispositionen)       | `array`   | Optional | cannot be null | [Untitled schema](preisblatt-properties-preispositionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/preispositionen")       |

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

### boTyp Default Value

The default value is:

```json
"PREISBLATT"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](preisblatt-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## bezeichnung



`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](preisblatt-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`

## gueltigkeit



`gueltigkeit`

*   is optional

*   Type: `object` ([Details](zeitraum.md))

*   cannot be null

*   defined in: [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeit")

### gueltigkeit Type

`object` ([Details](zeitraum.md))

## preisstatus



`preisstatus`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](preisstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Preisstatus.schema.json#/properties/preisstatus")

### preisstatus Type

`string`

### preisstatus Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"VORLAEUFIG"` |             |
| `"ENDGUELTIG"` |             |

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

## bilanzierungsdatum



`bilanzierungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](preisblatt-properties-bilanzierungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/bilanzierungsdatum")

### bilanzierungsdatum Type

`string`

### bilanzierungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## regelzone



`regelzone`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](preisblatt-properties-regelzone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/regelzone")

### regelzone Type

`string`

## leistungstyp



`leistungstyp`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](leistungstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Leistungstyp.schema.json#/properties/leistungstyp")

### leistungstyp Type

`string`

### leistungstyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                               | Explanation |
| :---------------------------------- | :---------- |
| `"ARBEITSPREIS_WIRKARBEIT"`         |             |
| `"LEISTUNGSPREIS_WIRKLEISTUNG"`     |             |
| `"ARBEITSPREIS_BLINDARBEIT_IND"`    |             |
| `"ARBEITSPREIS_BLINDARBEIT_KAP"`    |             |
| `"GRUNDPREIS"`                      |             |
| `"MEHRMINDERMENGE"`                 |             |
| `"MESSSTELLENBETRIEB"`              |             |
| `"MESSDIENSTLEISTUNG"`              |             |
| `"MESSDIENSTLEISTUNG_INKL_MESSUNG"` |             |
| `"ABRECHNUNG"`                      |             |
| `"KONZESSIONS_ABGABE"`              |             |
| `"KWK_UMLAGE"`                      |             |
| `"OFFSHORE_UMLAGE"`                 |             |
| `"ABLAV_UMLAGE"`                    |             |
| `"REGELENERGIE_UMLAGE"`             |             |
| `"BILANZIERUNG_UMLAGE"`             |             |
| `"AUSLESUNG_ZUSAETZLICH"`           |             |
| `"ABLESUNG_ZUSAETZLICH"`            |             |
| `"ABRECHNUNG_ZUSAETZLICH"`          |             |
| `"SPERRUNG"`                        |             |
| `"ENTSPERRUNG"`                     |             |
| `"MAHNKOSTEN"`                      |             |
| `"INKASSOKOSTEN"`                   |             |

## nichtGenutzt



`nichtGenutzt`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Untitled schema](preisblatt-properties-nichtgenutzt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/nichtGenutzt")

### nichtGenutzt Type

`boolean`

## preispositionen



`preispositionen`

*   is optional

*   Type: `object[]` ([Details](preisposition.md))

*   cannot be null

*   defined in: [Untitled schema](preisblatt-properties-preispositionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Preisblatt.schema.json#/properties/preispositionen")

### preispositionen Type

`object[]` ([Details](preisposition.md))
