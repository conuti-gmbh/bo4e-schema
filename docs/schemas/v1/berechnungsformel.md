## Berechnungsformel Type

`object` ([Berechnungsformel](berechnungsformel.md))

# Berechnungsformel Properties

| Property                                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                        |
| :-------------------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                               | `string`  | Required | cannot be null | [Berechnungsformel](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                              |
| [versionStruktur](#versionstruktur)           | `string`  | Required | cannot be null | [Berechnungsformel](berechnungsformel-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/versionStruktur")   |
| [beginndatum](#beginndatum)                   | `string`  | Optional | cannot be null | [Berechnungsformel](berechnungsformel-properties-beginndatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/beginndatum")           |
| [notwendigkeit](#notwendigkeit)               | `string`  | Optional | cannot be null | [Berechnungsformel](berechnungsformelnotwendigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BerechnungsformelNotwendigkeit.schema.json#/properties/notwendigkeit")    |
| [lieferrichtung](#lieferrichtung)             | `string`  | Optional | cannot be null | [Berechnungsformel](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/lieferrichtung")                                 |
| [rechenschrittId](#rechenschrittid)           | `integer` | Optional | cannot be null | [Berechnungsformel](berechnungsformel-properties-rechenschrittid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/rechenschrittId")   |
| [rechenschritt](#rechenschritt)               | `object`  | Optional | cannot be null | [Berechnungsformel](rechenschritt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/rechenschritt")                                       |
| [rechenschritte](#rechenschritte)             | `array`   | Optional | can be null    | [Berechnungsformel](berechnungsformel-properties-rechenschritte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/rechenschritte")     |
| [verwendungszweck](#verwendungszweck)         | `array`   | Optional | can be null    | [Berechnungsformel](berechnungsformel-properties-verwendungszweck.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/verwendungszweck") |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum) | `object`  | Optional | cannot be null | [Berechnungsformel](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                          |
| [lokationsId](#lokationsid)                   | `string`  | Optional | cannot be null | [Berechnungsformel](berechnungsformel-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/lokationsId")           |
| [lokationsTyp](#lokationstyp)                 | `string`  | Optional | cannot be null | [Berechnungsformel](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")                                         |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Berechnungsformel](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"BERECHNUNGSFORMEL"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Berechnungsformel](berechnungsformel-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## beginndatum

Der inklusive Zeitpunkt ab dem die Berechnungsformel gültig ist

`beginndatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Berechnungsformel](berechnungsformel-properties-beginndatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/beginndatum")

### beginndatum Type

`string`

### beginndatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## notwendigkeit

BerechnungsformelNotwendigkeit

`notwendigkeit`

*   is optional

*   Type: `string` ([BerechnungsformelNotwendigkeit](berechnungsformelnotwendigkeit.md))

*   cannot be null

*   defined in: [Berechnungsformel](berechnungsformelnotwendigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BerechnungsformelNotwendigkeit.schema.json#/properties/notwendigkeit")

### notwendigkeit Type

`string` ([BerechnungsformelNotwendigkeit](berechnungsformelnotwendigkeit.md))

### notwendigkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                       | Explanation |
| :------------------------------------------ | :---------- |
| `"BERECHNUNGSFORMEL_NOTWENDIG"`             |             |
| `"BERECHNUNGSFORMEL_MUSS_ANGEFRAGT_WERDEN"` |             |
| `"BERECHNUNGSFORMEL_TRIVIAL"`               |             |
| `"BERECHNUNGSFORMEL_NICHT_NOTWENDIG"`       |             |

## lieferrichtung

Spezifiziert die Energierichtung einer Markt- und/oder Messlokation

`lieferrichtung`

*   is optional

*   Type: `string` ([Energierichtung](energierichtung.md))

*   cannot be null

*   defined in: [Berechnungsformel](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/lieferrichtung")

### lieferrichtung Type

`string` ([Energierichtung](energierichtung.md))

### lieferrichtung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"AUSSP"` |             |
| `"EINSP"` |             |

## rechenschrittId

ID des Rechenschritts \[1 - 99999]

`rechenschrittId`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Berechnungsformel](berechnungsformel-properties-rechenschrittid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/rechenschrittId")

### rechenschrittId Type

`integer`

## rechenschritt



`rechenschritt`

*   is optional

*   Type: `object` ([Rechenschritt](rechenschritt.md))

*   cannot be null

*   defined in: [Berechnungsformel](rechenschritt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechenschritt.schema.json#/properties/rechenschritt")

### rechenschritt Type

`object` ([Rechenschritt](rechenschritt.md))

## rechenschritte

Eine Berechnungsformel enthält, falls sie notwendig ist, einen oder mehrere Berechnungschritte, die hier rekursiv abgebildet werden.

`rechenschritte`

*   is optional

*   Type: `object[]` ([Rechenschritt](rechenschritt.md))

*   can be null

*   defined in: [Berechnungsformel](berechnungsformel-properties-rechenschritte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/rechenschritte")

### rechenschritte Type

`object[]` ([Rechenschritt](rechenschritt.md))

## verwendungszweck

Verwendungszweck der Werte

`verwendungszweck`

*   is optional

*   Type: `object[]` ([Verwendungszweck](verwendungszweck.md))

*   can be null

*   defined in: [Berechnungsformel](berechnungsformel-properties-verwendungszweck.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/verwendungszweck")

### verwendungszweck Type

`object[]` ([Verwendungszweck](verwendungszweck.md))

## gueltigkeitszeitraum

Gültigkeitszeitraum der Werte

`gueltigkeitszeitraum`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Berechnungsformel](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))

## lokationsId

Eindeutige Nummer der Lokation, zu der die Berechnungsformel gehört. Verwendung für notwendige interne Zuordnungen.

`lokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Berechnungsformel](berechnungsformel-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Berechnungsformel.schema.json#/properties/lokationsId")

### lokationsId Type

`string`

## lokationsTyp

Gibt an, ob es sich um eine Markt- oder Messlokation handelt

`lokationsTyp`

*   is optional

*   Type: `string` ([Lokationstyp](lokationstyp.md))

*   cannot be null

*   defined in: [Berechnungsformel](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")

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
| `"STEUERBARE_RESSOURCE"` |             |
| `"TRANCHE"`              |             |
