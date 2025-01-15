## Energiemenge Type

`object` ([Energiemenge](energiemenge.md))

# Energiemenge Properties

| Property                                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                 |
| :------------------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                               | `string` | Required | cannot be null | [Energiemenge](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                            |
| [versionStruktur](#versionstruktur)                           | `string` | Required | cannot be null | [Energiemenge](energiemenge-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/versionStruktur")                           |
| [lokationsId](#lokationsid)                                   | `string` | Optional | cannot be null | [Energiemenge](energiemenge-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/lokationsId")                                   |
| [lokationsTyp](#lokationstyp)                                 | `string` | Optional | cannot be null | [Energiemenge](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")                                                       |
| [fertigstellungsdatum](#fertigstellungsdatum)                 | `string` | Optional | cannot be null | [Energiemenge](energiemenge-properties-fertigstellungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/fertigstellungsdatum")                 |
| [startdatum](#startdatum)                                     | `string` | Optional | cannot be null | [Energiemenge](energiemenge-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/startdatum")                                     |
| [enddatum](#enddatum)                                         | `string` | Optional | cannot be null | [Energiemenge](energiemenge-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/enddatum")                                         |
| [bilanzierungsdatum](#bilanzierungsdatum)                     | `string` | Optional | cannot be null | [Energiemenge](energiemenge-properties-bilanzierungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/bilanzierungsdatum")                     |
| [beginndatum](#beginndatum)                                   | `string` | Optional | cannot be null | [Energiemenge](energiemenge-properties-beginndatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/beginndatum")                                   |
| [referenzStammdatenmeldungMsb](#referenzstammdatenmeldungmsb) | `string` | Optional | cannot be null | [Energiemenge](energiemenge-properties-referenzstammdatenmeldungmsb.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/referenzStammdatenmeldungMsb") |
| [konfiguration](#konfiguration)                               | `string` | Optional | cannot be null | [Energiemenge](energiemenge-properties-konfiguration.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/konfiguration")                               |
| [energieverbrauch](#energieverbrauch)                         | `array`  | Optional | cannot be null | [Energiemenge](energiemenge-properties-energieverbrauch.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/energieverbrauch")                         |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Energiemenge](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"ENERGIEMENGE"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## lokationsId

Eindeutige Nummer der Marktlokation bzw. der Messlokation, zu der die Energiemenge gehört

`lokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/lokationsId")

### lokationsId Type

`string`

## lokationsTyp

Gibt an, ob es sich um eine Markt- oder Messlokation handelt.

`lokationsTyp`

*   is optional

*   Type: `string` ([Lokationstyp](lokationstyp.md))

*   cannot be null

*   defined in: [Energiemenge](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")

### lokationsTyp Type

`string` ([Lokationstyp](lokationstyp.md))

### lokationsTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"MALO"`                 |             |
| `"MELO"`                 |             |
| `"NELO"`                 |             |
| `"TECHNISCHE_RESSOURCE"` |             |

## fertigstellungsdatum



`fertigstellungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-fertigstellungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/fertigstellungsdatum")

### fertigstellungsdatum Type

`string`

### fertigstellungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## startdatum

Gibt Tag und Uhrzeit (falls vorhanden) an, wann der Zeitraum startet.

`startdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/startdatum")

### startdatum Type

`string`

### startdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## enddatum

Gibt Tag und Uhrzeit (falls vorhanden) an, wann der Zeitraum endet.

`enddatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/enddatum")

### enddatum Type

`string`

### enddatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## bilanzierungsdatum



`bilanzierungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-bilanzierungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/bilanzierungsdatum")

### bilanzierungsdatum Type

`string`

### bilanzierungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## beginndatum



`beginndatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-beginndatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/beginndatum")

### beginndatum Type

`string`

### beginndatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## referenzStammdatenmeldungMsb



`referenzStammdatenmeldungMsb`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-referenzstammdatenmeldungmsb.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/referenzStammdatenmeldungMsb")

### referenzStammdatenmeldungMsb Type

`string`

## konfiguration



`konfiguration`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-konfiguration.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/konfiguration")

### konfiguration Type

`string`

## energieverbrauch

Gibt den Verbrauch in einer Zeiteinheit an.

`energieverbrauch`

*   is optional

*   Type: `object[]` ([Verbrauch](verbrauch.md))

*   cannot be null

*   defined in: [Energiemenge](energiemenge-properties-energieverbrauch.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Energiemenge.schema.json#/properties/energieverbrauch")

### energieverbrauch Type

`object[]` ([Verbrauch](verbrauch.md))
