## Vertragskonditionen Type

`object` ([Vertragskonditionen](vertragskonditionen.md))

# Vertragskonditionen Properties

| Property                                                                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                 |
| :-------------------------------------------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [netznutzungszahler](#netznutzungszahler)                                               | `string`  | Optional | cannot be null | [Vertragskonditionen](netznutzungszahler.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netznutzungszahler.schema.json#/properties/netznutzungszahler")                                                                              |
| [netznutzungsvertrag](#netznutzungsvertrag)                                             | `string`  | Optional | cannot be null | [Vertragskonditionen](netznutzungsvertrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netznutzungsvertrag.schema.json#/properties/netznutzungsvertrag")                                                                           |
| [netznutzungsabrechnung](#netznutzungsabrechnung)                                       | `object`  | Optional | cannot be null | [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/netznutzungsabrechnung")                                                                                               |
| [beinhaltetSingulaerGenutzteBetriebsmittel](#beinhaltetsingulaergenutztebetriebsmittel) | `boolean` | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-beinhaltetsingulaergenutztebetriebsmittel.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/beinhaltetSingulaerGenutzteBetriebsmittel") |
| [netznutzungsabrechnungsgrundlage](#netznutzungsabrechnungsgrundlage)                   | `string`  | Optional | cannot be null | [Vertragskonditionen](netznutzungsabrechnungsgrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netznutzungsabrechnungsgrundlage.schema.json#/properties/netznutzungsabrechnungsgrundlage")                                    |
| [netznutzungsabrechnungsvariante](#netznutzungsabrechnungsvariante)                     | `string`  | Optional | cannot be null | [Vertragskonditionen](netznutzungsabrechnungsvariante.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netznutzungsabrechnungsvariante.schema.json#/properties/netznutzungsabrechnungsvariante")                                       |
| [haushaltskunde](#haushaltskunde)                                                       | `boolean` | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-haushaltskunde.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/haushaltskunde")                                                       |
| [abrechnungUeberNna](#abrechnunguebernna)                                               | `boolean` | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-abrechnunguebernna.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/abrechnungUeberNna")                                               |
| [gemeinderabatt](#gemeinderabatt)                                                       | `object`  | Optional | cannot be null | [Vertragskonditionen](gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Gemeinderabatt.schema.json#/properties/gemeinderabatt")                                                                                           |
| [startAbrechnungsjahr](#startabrechnungsjahr)                                           | `string`  | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-startabrechnungsjahr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/startAbrechnungsjahr")                                           |
| [naechstenetznutzungsabrechnung](#naechstenetznutzungsabrechnung)                       | `string`  | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-naechstenetznutzungsabrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/naechstenetznutzungsabrechnung")                       |
| [abrechnungsintervall](#abrechnungsintervall)                                           | `integer` | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-abrechnungsintervall.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/abrechnungsintervall")                                           |
| [netznutzungsabrechnungIntervall](#netznutzungsabrechnungintervall)                     | `integer` | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-netznutzungsabrechnungintervall.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/netznutzungsabrechnungIntervall")                     |
| [geplanteTurnusablesung](#geplanteturnusablesung)                                       | `object`  | Optional | cannot be null | [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/geplanteTurnusablesung")                                                                                               |
| [beauftragungMsb](#beauftragungmsb)                                                     | `string`  | Optional | cannot be null | [Vertragskonditionen](beauftragungmsb.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BeauftragungMsb.schema.json#/properties/beauftragungMsb")                                                                                       |
| [kuendigungsfrist](#kuendigungsfrist)                                                   | `object`  | Optional | cannot be null | [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/kuendigungsfrist")                                                                                                     |
| [vertragslaufzeit](#vertragslaufzeit)                                                   | `object`  | Optional | cannot be null | [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/vertragslaufzeit")                                                                                                     |
| [kuendigungstermin](#kuendigungstermin)                                                 | `string`  | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-kuendigungstermin.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/kuendigungstermin")                                                 |
| [abschlagszyklus](#abschlagszyklus)                                                     | `object`  | Optional | cannot be null | [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/abschlagszyklus")                                                                                                      |
| [anzahl\_abschlaege](#anzahl_abschlaege)                                                | `number`  | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-anzahl_abschlaege.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/anzahl_abschlaege")                                                 |
| [beschreibung](#beschreibung)                                                           | `string`  | Optional | cannot be null | [Vertragskonditionen](vertragskonditionen-properties-beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/beschreibung")                                                           |
| [vertragsverlaengerung](#vertragsverlaengerung)                                         | `object`  | Optional | cannot be null | [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/vertragsverlaengerung")                                                                                                |

## netznutzungszahler



`netznutzungszahler`

*   is optional

*   Type: `string` ([Netznutzungszahler](netznutzungszahler.md))

*   cannot be null

*   defined in: [Vertragskonditionen](netznutzungszahler.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netznutzungszahler.schema.json#/properties/netznutzungszahler")

### netznutzungszahler Type

`string` ([Netznutzungszahler](netznutzungszahler.md))

### netznutzungszahler Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"KUNDE"`     |             |
| `"LIEFERANT"` |             |

## netznutzungsvertrag



`netznutzungsvertrag`

*   is optional

*   Type: `string` ([Netznutzungsvertrag](netznutzungsvertrag.md))

*   cannot be null

*   defined in: [Vertragskonditionen](netznutzungsvertrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netznutzungsvertrag.schema.json#/properties/netznutzungsvertrag")

### netznutzungsvertrag Type

`string` ([Netznutzungsvertrag](netznutzungsvertrag.md))

### netznutzungsvertrag Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"KUNDEN_NB"`      |             |
| `"LIEFERANTEN_NB"` |             |

## netznutzungsabrechnung



`netznutzungsabrechnung`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/netznutzungsabrechnung")

### netznutzungsabrechnung Type

`object` ([Zeitraum](zeitraum.md))

## beinhaltetSingulaerGenutzteBetriebsmittel



`beinhaltetSingulaerGenutzteBetriebsmittel`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-beinhaltetsingulaergenutztebetriebsmittel.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/beinhaltetSingulaerGenutzteBetriebsmittel")

### beinhaltetSingulaerGenutzteBetriebsmittel Type

`boolean`

## netznutzungsabrechnungsgrundlage



`netznutzungsabrechnungsgrundlage`

*   is optional

*   Type: `string` ([Netznutzungsabrechnungsgrundlage](netznutzungsabrechnungsgrundlage.md))

*   cannot be null

*   defined in: [Vertragskonditionen](netznutzungsabrechnungsgrundlage.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netznutzungsabrechnungsgrundlage.schema.json#/properties/netznutzungsabrechnungsgrundlage")

### netznutzungsabrechnungsgrundlage Type

`string` ([Netznutzungsabrechnungsgrundlage](netznutzungsabrechnungsgrundlage.md))

### netznutzungsabrechnungsgrundlage Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                     | Explanation |
| :------------------------ | :---------- |
| `"LIEFERSCHEIN"`          |             |
| `"ABWEICHENDE_GRUNDLAGE"` |             |

## netznutzungsabrechnungsvariante



`netznutzungsabrechnungsvariante`

*   is optional

*   Type: `string` ([Netznutzungsabrechnungsvariante](netznutzungsabrechnungsvariante.md))

*   cannot be null

*   defined in: [Vertragskonditionen](netznutzungsabrechnungsvariante.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netznutzungsabrechnungsvariante.schema.json#/properties/netznutzungsabrechnungsvariante")

### netznutzungsabrechnungsvariante Type

`string` ([Netznutzungsabrechnungsvariante](netznutzungsabrechnungsvariante.md))

### netznutzungsabrechnungsvariante Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                           | Explanation |
| :------------------------------ | :---------- |
| `"ARBEITSPREIS_GRUNDPREIS"`     |             |
| `"ARBEITSPREIS_LEISTUNGSPREIS"` |             |

## haushaltskunde



`haushaltskunde`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-haushaltskunde.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/haushaltskunde")

### haushaltskunde Type

`boolean`

## abrechnungUeberNna



`abrechnungUeberNna`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-abrechnunguebernna.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/abrechnungUeberNna")

### abrechnungUeberNna Type

`boolean`

## gemeinderabatt



`gemeinderabatt`

*   is optional

*   Type: `object` ([Gemeinderabatt](gemeinderabatt.md))

*   cannot be null

*   defined in: [Vertragskonditionen](gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Gemeinderabatt.schema.json#/properties/gemeinderabatt")

### gemeinderabatt Type

`object` ([Gemeinderabatt](gemeinderabatt.md))

## startAbrechnungsjahr



`startAbrechnungsjahr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-startabrechnungsjahr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/startAbrechnungsjahr")

### startAbrechnungsjahr Type

`string`

### startAbrechnungsjahr Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## naechstenetznutzungsabrechnung



`naechstenetznutzungsabrechnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-naechstenetznutzungsabrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/naechstenetznutzungsabrechnung")

### naechstenetznutzungsabrechnung Type

`string`

## abrechnungsintervall



`abrechnungsintervall`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-abrechnungsintervall.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/abrechnungsintervall")

### abrechnungsintervall Type

`integer`

## netznutzungsabrechnungIntervall



`netznutzungsabrechnungIntervall`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-netznutzungsabrechnungintervall.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/netznutzungsabrechnungIntervall")

### netznutzungsabrechnungIntervall Type

`integer`

## geplanteTurnusablesung



`geplanteTurnusablesung`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/geplanteTurnusablesung")

### geplanteTurnusablesung Type

`object` ([Zeitraum](zeitraum.md))

## beauftragungMsb



`beauftragungMsb`

*   is optional

*   Type: `string` ([BeauftragungMsb](beauftragungmsb.md))

*   cannot be null

*   defined in: [Vertragskonditionen](beauftragungmsb.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BeauftragungMsb.schema.json#/properties/beauftragungMsb")

### beauftragungMsb Type

`string` ([BeauftragungMsb](beauftragungmsb.md))

### beauftragungMsb Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"VERTRAG_AN_MSB"`         |             |
| `"VERTRAGSBEENDIGUNG_MSB"` |             |

## kuendigungsfrist



`kuendigungsfrist`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/kuendigungsfrist")

### kuendigungsfrist Type

`object` ([Zeitraum](zeitraum.md))

## vertragslaufzeit



`vertragslaufzeit`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/vertragslaufzeit")

### vertragslaufzeit Type

`object` ([Zeitraum](zeitraum.md))

## kuendigungstermin



`kuendigungstermin`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-kuendigungstermin.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/kuendigungstermin")

### kuendigungstermin Type

`string`

## abschlagszyklus

In diesen Zyklen werden Abschläge gestellt. Alternativ kann auch die Anzahl in den Konditionen angeben werden.

`abschlagszyklus`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/abschlagszyklus")

### abschlagszyklus Type

`object` ([Zeitraum](zeitraum.md))

## anzahl\_abschlaege

Anzahl der vereinbarten Abschläge pro Jahr, z.B. 12

`anzahl_abschlaege`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-anzahl_abschlaege.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/anzahl_abschlaege")

### anzahl\_abschlaege Type

`number`

### anzahl\_abschlaege Constraints

**unknown format**: the value of this string must follow the format: `float`

## beschreibung

Freitext zur Beschreibung der Konditionen

`beschreibung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertragskonditionen](vertragskonditionen-properties-beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/beschreibung")

### beschreibung Type

`string`

## vertragsverlaengerung

Falls der Vertrag nicht gekündigt wird, verlängert er sich automatisch um die hier angegebene Zeit

`vertragsverlaengerung`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Vertragskonditionen](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/vertragsverlaengerung")

### vertragsverlaengerung Type

`object` ([Zeitraum](zeitraum.md))
