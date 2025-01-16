## Angebot Type

`object` ([Angebot](angebot.md))

# Angebot Properties

| Property                                                                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                         |
| :---------------------------------------------------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                                     | `string` | Required | cannot be null | [Angebot](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                         |
| [versionStruktur](#versionstruktur)                                                 | `string` | Required | cannot be null | [Angebot](angebot-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/versionStruktur")  |
| [angebotsnummer](#angebotsnummer)                                                   | `string` | Optional | cannot be null | [Angebot](angebot-properties-angebotsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/angebotsnummer")    |
| [anfragereferenz](#anfragereferenz)                                                 | `string` | Optional | cannot be null | [Angebot](angebot-properties-anfragereferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/anfragereferenz")  |
| [angebotsdatum](#angebotsdatum)                                                     | `string` | Optional | cannot be null | [Angebot](angebot-properties-angebotsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/angebotsdatum")      |
| [sparte](#sparte)                                                                   | `string` | Optional | cannot be null | [Angebot](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                      |
| [bindefrist](#bindefrist)                                                           | `string` | Optional | cannot be null | [Angebot](angebot-properties-bindefrist.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/bindefrist")            |
| [angebotgeber](#angebotgeber)                                                       | `object` | Optional | cannot be null | [Angebot](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/angebotgeber")            |
| [angebotnehmer](#angebotnehmer)                                                     | `object` | Optional | cannot be null | [Angebot](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/angebotnehmer")           |
| [unterzeichnerAngebotsnehmer](#unterzeichnerangebotsnehmer)                         | `object` | Optional | cannot be null | [Angebot](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/unterzeichnerAngebotsnehmer") |
| [unterzeichnerAngebotsgeber](#unterzeichnerangebotsgeber)                           | `object` | Optional | cannot be null | [Angebot](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/unterzeichnerAngebotsgeber")  |
| [zeitspanneEinrichtungUebermittlungWerte](#zeitspanneeinrichtunguebermittlungwerte) | `object` | Optional | cannot be null | [Angebot](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitspanneEinrichtungUebermittlungWerte")  |
| [bindefristAngebot](#bindefristangebot)                                             | `object` | Optional | cannot be null | [Angebot](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/bindefristAngebot")                        |
| [varianten](#varianten)                                                             | `array`  | Optional | cannot be null | [Angebot](angebot-properties-varianten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/varianten")              |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Angebot](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"ANGEBOT"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Angebot](angebot-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## angebotsnummer

angebotsnummer

`angebotsnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Angebot](angebot-properties-angebotsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/angebotsnummer")

### angebotsnummer Type

`string`

## anfragereferenz

anfragereferenz

`anfragereferenz`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Angebot](angebot-properties-anfragereferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/anfragereferenz")

### anfragereferenz Type

`string`

## angebotsdatum

angebotsdatum

`angebotsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Angebot](angebot-properties-angebotsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/angebotsdatum")

### angebotsdatum Type

`string`

### angebotsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## sparte

Sparte

`sparte`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [Angebot](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

### sparte Type

`string` ([Sparte](sparte.md))

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

bindefrist

`bindefrist`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Angebot](angebot-properties-bindefrist.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/bindefrist")

### bindefrist Type

`string`

### bindefrist Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## angebotgeber



`angebotgeber`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Angebot](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/angebotgeber")

### angebotgeber Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## angebotnehmer



`angebotnehmer`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Angebot](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/angebotnehmer")

### angebotnehmer Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## unterzeichnerAngebotsnehmer



`unterzeichnerAngebotsnehmer`

*   is optional

*   Type: `object` ([Ansprechpartner](ansprechpartner.md))

*   cannot be null

*   defined in: [Angebot](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/unterzeichnerAngebotsnehmer")

### unterzeichnerAngebotsnehmer Type

`object` ([Ansprechpartner](ansprechpartner.md))

## unterzeichnerAngebotsgeber



`unterzeichnerAngebotsgeber`

*   is optional

*   Type: `object` ([Ansprechpartner](ansprechpartner.md))

*   cannot be null

*   defined in: [Angebot](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/unterzeichnerAngebotsgeber")

### unterzeichnerAngebotsgeber Type

`object` ([Ansprechpartner](ansprechpartner.md))

## zeitspanneEinrichtungUebermittlungWerte



`zeitspanneEinrichtungUebermittlungWerte`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Angebot](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitspanneEinrichtungUebermittlungWerte")

### zeitspanneEinrichtungUebermittlungWerte Type

`object` ([Zeitraum](zeitraum.md))

## bindefristAngebot



`bindefristAngebot`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Angebot](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/bindefristAngebot")

### bindefristAngebot Type

`object` ([Zeitraum](zeitraum.md))

## varianten

varianten

`varianten`

*   is optional

*   Type: `object[]` ([Angebotsvariante](angebotsvariante.md))

*   cannot be null

*   defined in: [Angebot](angebot-properties-varianten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Angebot.schema.json#/properties/varianten")

### varianten Type

`object[]` ([Angebotsvariante](angebotsvariante.md))
