## Untitled object in undefined Type

`object` ([Details](angebot.md))

# Untitled object in undefined Properties

| Property                                                                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                 |
| :---------------------------------------------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                                     | `string` | Required | cannot be null | [Untitled schema](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                         |
| [versionStruktur](#versionstruktur)                                                 | `string` | Required | cannot be null | [Untitled schema](angebot-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/versionStruktur")  |
| [angebotsnummer](#angebotsnummer)                                                   | `string` | Optional | cannot be null | [Untitled schema](angebot-properties-angebotsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/angebotsnummer")    |
| [anfragereferenz](#anfragereferenz)                                                 | `string` | Optional | cannot be null | [Untitled schema](angebot-properties-anfragereferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/anfragereferenz")  |
| [angebotsdatum](#angebotsdatum)                                                     | `string` | Optional | cannot be null | [Untitled schema](angebot-properties-angebotsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/angebotsdatum")      |
| [sparte](#sparte)                                                                   | `string` | Optional | cannot be null | [Untitled schema](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                      |
| [bindefrist](#bindefrist)                                                           | `string` | Optional | cannot be null | [Untitled schema](angebot-properties-bindefrist.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/bindefrist")            |
| [angebotgeber](#angebotgeber)                                                       | `object` | Optional | cannot be null | [Untitled schema](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/angebotgeber")            |
| [angebotnehmer](#angebotnehmer)                                                     | `object` | Optional | cannot be null | [Untitled schema](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/angebotnehmer")           |
| [unterzeichnerAngebotsnehmer](#unterzeichnerangebotsnehmer)                         | `object` | Optional | cannot be null | [Untitled schema](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/unterzeichnerAngebotsnehmer") |
| [unterzeichnerAngebotsgeber](#unterzeichnerangebotsgeber)                           | `object` | Optional | cannot be null | [Untitled schema](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/unterzeichnerAngebotsgeber")  |
| [zeitspanneEinrichtungUebermittlungWerte](#zeitspanneeinrichtunguebermittlungwerte) | `object` | Optional | cannot be null | [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitspanneEinrichtungUebermittlungWerte")  |
| [bindefristAngebot](#bindefristangebot)                                             | `object` | Optional | cannot be null | [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/bindefristAngebot")                        |
| [varianten](#varianten)                                                             | `array`  | Optional | cannot be null | [Untitled schema](angebot-properties-varianten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/varianten")              |

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
"ANGEBOT"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](angebot-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## angebotsnummer



`angebotsnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](angebot-properties-angebotsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/angebotsnummer")

### angebotsnummer Type

`string`

## anfragereferenz



`anfragereferenz`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](angebot-properties-anfragereferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/anfragereferenz")

### anfragereferenz Type

`string`

## angebotsdatum



`angebotsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](angebot-properties-angebotsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/angebotsdatum")

### angebotsdatum Type

`string`

### angebotsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

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

## bindefrist



`bindefrist`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](angebot-properties-bindefrist.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/bindefrist")

### bindefrist Type

`string`

### bindefrist Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## angebotgeber



`angebotgeber`

*   is optional

*   Type: `object` ([Details](geschaeftspartner.md))

*   cannot be null

*   defined in: [Untitled schema](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/angebotgeber")

### angebotgeber Type

`object` ([Details](geschaeftspartner.md))

## angebotnehmer



`angebotnehmer`

*   is optional

*   Type: `object` ([Details](geschaeftspartner.md))

*   cannot be null

*   defined in: [Untitled schema](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/angebotnehmer")

### angebotnehmer Type

`object` ([Details](geschaeftspartner.md))

## unterzeichnerAngebotsnehmer



`unterzeichnerAngebotsnehmer`

*   is optional

*   Type: `object` ([Details](ansprechpartner.md))

*   cannot be null

*   defined in: [Untitled schema](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/unterzeichnerAngebotsnehmer")

### unterzeichnerAngebotsnehmer Type

`object` ([Details](ansprechpartner.md))

## unterzeichnerAngebotsgeber



`unterzeichnerAngebotsgeber`

*   is optional

*   Type: `object` ([Details](ansprechpartner.md))

*   cannot be null

*   defined in: [Untitled schema](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/unterzeichnerAngebotsgeber")

### unterzeichnerAngebotsgeber Type

`object` ([Details](ansprechpartner.md))

## zeitspanneEinrichtungUebermittlungWerte



`zeitspanneEinrichtungUebermittlungWerte`

*   is optional

*   Type: `object` ([Details](zeitraum.md))

*   cannot be null

*   defined in: [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitspanneEinrichtungUebermittlungWerte")

### zeitspanneEinrichtungUebermittlungWerte Type

`object` ([Details](zeitraum.md))

## bindefristAngebot



`bindefristAngebot`

*   is optional

*   Type: `object` ([Details](zeitraum.md))

*   cannot be null

*   defined in: [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/bindefristAngebot")

### bindefristAngebot Type

`object` ([Details](zeitraum.md))

## varianten



`varianten`

*   is optional

*   Type: `object[]` ([Details](angebotsvariante.md))

*   cannot be null

*   defined in: [Untitled schema](angebot-properties-varianten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/varianten")

### varianten Type

`object[]` ([Details](angebotsvariante.md))
