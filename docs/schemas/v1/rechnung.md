## Rechnung Type

`object` ([Rechnung](rechnung.md))

# Rechnung Properties

| Property                                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                 |
| :------------------------------------------------------------------ | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                     | `string`  | Required | cannot be null | [Rechnung](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                |
| [versionStruktur](#versionstruktur)                                 | `string`  | Required | cannot be null | [Rechnung](rechnung-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/versionStruktur")                       |
| [istSelbstausgestellt](#istselbstausgestellt)                       | `boolean` | Optional | cannot be null | [Rechnung](rechnung-properties-istselbstausgestellt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/istSelbstausgestellt")             |
| [bearbeitungsdatum](#bearbeitungsdatum)                             | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-bearbeitungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/bearbeitungsdatum")                   |
| [rechnungsdatum](#rechnungsdatum)                                   | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-rechnungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/rechnungsdatum")                         |
| [faelligkeitsdatum](#faelligkeitsdatum)                             | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-faelligkeitsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/faelligkeitsdatum")                   |
| [rechnungsstatus](#rechnungsstatus)                                 | `string`  | Optional | cannot be null | [Rechnung](rechnungsstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Rechnungsstatus.schema.json#/properties/rechnungsstatus")                                  |
| [vorlaeufigerAbrechnungszeitraum](#vorlaeufigerabrechnungszeitraum) | `object`  | Optional | cannot be null | [Rechnung](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/vorlaeufigerAbrechnungszeitraum")                                 |
| [rechnungsperiode](#rechnungsperiode)                               | `object`  | Optional | cannot be null | [Rechnung](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/rechnungsperiode")                                                |
| [rechnungstyp](#rechnungstyp)                                       | `string`  | Optional | cannot be null | [Rechnung](rechnungstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Rechnungstyp.schema.json#/properties/rechnungstyp")                                           |
| [istReverseCharge](#istreversecharge)                               | `boolean` | Optional | cannot be null | [Rechnung](rechnung-properties-istreversecharge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/istReverseCharge")                     |
| [gesamtbrutto](#gesamtbrutto)                                       | `object`  | Optional | cannot be null | [Rechnung](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/gesamtbrutto")                                                        |
| [zuZahlen](#zuzahlen)                                               | `object`  | Optional | cannot be null | [Rechnung](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/zuZahlen")                                                            |
| [originalRechnungsnummer](#originalrechnungsnummer)                 | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-originalrechnungsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/originalRechnungsnummer")       |
| [referenzNachrichtendatum](#referenznachrichtendatum)               | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-referenznachrichtendatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/referenzNachrichtendatum")     |
| [referenzDokumentennummer](#referenzdokumentennummer)               | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-referenzdokumentennummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/referenzDokumentennummer")     |
| [referenzVorgaengerrechnung](#referenzvorgaengerrechnung)           | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-referenzvorgaengerrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/referenzVorgaengerrechnung") |
| [datumVorgaengerrechnung](#datumvorgaengerrechnung)                 | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-datumvorgaengerrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/datumVorgaengerrechnung")       |
| [netzkonto](#netzkonto)                                             | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-netzkonto.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/netzkonto")                                   |
| [vorausgezahlt](#vorausgezahlt)                                     | `object`  | Optional | cannot be null | [Rechnung](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/vorausgezahlt")                                                       |
| [gemeinderabatt](#gemeinderabatt)                                   | `object`  | Optional | cannot be null | [Rechnung](gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Gemeinderabatt.schema.json#/properties/gemeinderabatt")                                      |
| [ausfuehrungsdatum](#ausfuehrungsdatum)                             | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-ausfuehrungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/ausfuehrungsdatum")                   |
| [sonderrechnungsart](#sonderrechnungsart)                           | `string`  | Optional | cannot be null | [Rechnung](sonderrechnungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/SonderrechnungsArt.schema.json#/properties/sonderrechnungsart")                         |
| [energierichtung](#energierichtung)                                 | `string`  | Optional | cannot be null | [Rechnung](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")                                  |
| [beginnPeriodeBilanzierung](#beginnperiodebilanzierung)             | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-beginnperiodebilanzierung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/beginnPeriodeBilanzierung")   |
| [endePeriodeNetznutzung](#endeperiodenetznutzung)                   | `string`  | Optional | cannot be null | [Rechnung](rechnung-properties-endeperiodenetznutzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/endePeriodeNetznutzung")         |
| [steuerbetraege](#steuerbetraege)                                   | `array`   | Optional | cannot be null | [Rechnung](rechnung-properties-steuerbetraege.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/steuerbetraege")                         |
| [rechnungspositionen](#rechnungspositionen)                         | `array`   | Optional | cannot be null | [Rechnung](rechnung-properties-rechnungspositionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/rechnungspositionen")               |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Rechnung](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"RECHNUNG"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## istSelbstausgestellt

Kennzeichen, ob es sich um eine selbstausgestellte Rechnung handelt

`istSelbstausgestellt`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-istselbstausgestellt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/istSelbstausgestellt")

### istSelbstausgestellt Type

`boolean`

## bearbeitungsdatum



`bearbeitungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-bearbeitungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/bearbeitungsdatum")

### bearbeitungsdatum Type

`string`

### bearbeitungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## rechnungsdatum

Ausstellungsdatum der Rechnung.

`rechnungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-rechnungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/rechnungsdatum")

### rechnungsdatum Type

`string`

### rechnungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## faelligkeitsdatum

Zu diesem Datum ist die Zahlung fällig.

`faelligkeitsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-faelligkeitsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/faelligkeitsdatum")

### faelligkeitsdatum Type

`string`

### faelligkeitsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## rechnungsstatus

Status der Rechnung zur Kennzeichnung des Bearbeitungsstandes. Details siehe ENUM Rechnungsstatus

`rechnungsstatus`

*   is optional

*   Type: `string` ([Rechnungsstatus](rechnungsstatus.md))

*   cannot be null

*   defined in: [Rechnung](rechnungsstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Rechnungsstatus.schema.json#/properties/rechnungsstatus")

### rechnungsstatus Type

`string` ([Rechnungsstatus](rechnungsstatus.md))

### rechnungsstatus Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"DUPLIKAT"`  |             |
| `"ORIGINAL"`  |             |
| `"STORNIERT"` |             |

## vorlaeufigerAbrechnungszeitraum



`vorlaeufigerAbrechnungszeitraum`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Rechnung](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/vorlaeufigerAbrechnungszeitraum")

### vorlaeufigerAbrechnungszeitraum Type

`object` ([Zeitraum](zeitraum.md))

## rechnungsperiode

Der Zeitraum der zugrunde liegenden Lieferung zur Rechnung. In der COM Zeitraum können diese angegeben werden.

`rechnungsperiode`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Rechnung](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/rechnungsperiode")

### rechnungsperiode Type

`object` ([Zeitraum](zeitraum.md))

## rechnungstyp

Ein kontextbezogender Rechnungstyp, z.B. Netznutzungsrechnung. Details siehe ENUM Rechnungstyp

`rechnungstyp`

*   is optional

*   Type: `string` ([Rechnungstyp](rechnungstyp.md))

*   cannot be null

*   defined in: [Rechnung](rechnungstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Rechnungstyp.schema.json#/properties/rechnungstyp")

### rechnungstyp Type

`string` ([Rechnungstyp](rechnungstyp.md))

### rechnungstyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                      | Explanation |
| :--------------------------------------------------------- | :---------- |
| `"ABSCHLUSSRECHNUNG"`                                      |             |
| `"ABSCHLAGSRECHNUNG"`                                      |             |
| `"TURNUSRECHNUNG"`                                         |             |
| `"MONATSRECHNUNG"`                                         |             |
| `"WIMRECHNUNG"`                                            |             |
| `"ZWISCHENRECHNUNG"`                                       |             |
| `"INTEGRIERTE_13TE_RECHNUNG"`                              |             |
| `"ZUSAETZLICHE_13TE_RECHNUNG"`                             |             |
| `"MEHRMINDERMENGENRECHNUNG"`                               |             |
| `"MSBRECHNUNG"`                                            |             |
| `"KAPAZITAETSRECHNUNG"`                                    |             |
| `"SPERRUNG_INBETRIEBNAHME"`                                |             |
| `"VERZUGSKOSTEN"`                                          |             |
| `"BLINDARBEIT"`                                            |             |
| `"SONDERRECHNUNG"`                                         |             |
| `"ABRECHNUNG_VON_KONFIGURATIONEN_UNIVERSALBESTELLPROZESS"` |             |

## istReverseCharge

Kennzeichen, ob bei der Rechnung das Reverse Charge verfahren angewendet wird

`istReverseCharge`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-istreversecharge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/istReverseCharge")

### istReverseCharge Type

`boolean`

## gesamtbrutto

Die Summe aus Netto- und Steuerbetrag. Details Betrag

`gesamtbrutto`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Rechnung](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/gesamtbrutto")

### gesamtbrutto Type

`object` ([Betrag](betrag.md))

## zuZahlen



`zuZahlen`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Rechnung](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/zuZahlen")

### zuZahlen Type

`object` ([Betrag](betrag.md))

## originalRechnungsnummer

Im Falle einer Stornorechnung (storno = true) steht hier die Rechnungsnummer der stornierten Rechnung.

`originalRechnungsnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-originalrechnungsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/originalRechnungsnummer")

### originalRechnungsnummer Type

`string`

## referenzNachrichtendatum



`referenzNachrichtendatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-referenznachrichtendatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/referenzNachrichtendatum")

### referenzNachrichtendatum Type

`string`

## referenzDokumentennummer



`referenzDokumentennummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-referenzdokumentennummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/referenzDokumentennummer")

### referenzDokumentennummer Type

`string`

## referenzVorgaengerrechnung



`referenzVorgaengerrechnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-referenzvorgaengerrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/referenzVorgaengerrechnung")

### referenzVorgaengerrechnung Type

`string`

## datumVorgaengerrechnung



`datumVorgaengerrechnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-datumvorgaengerrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/datumVorgaengerrechnung")

### datumVorgaengerrechnung Type

`string`

### datumVorgaengerrechnung Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## netzkonto



`netzkonto`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-netzkonto.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/netzkonto")

### netzkonto Type

`string`

## vorausgezahlt

Die Summe evtl. vorausgezahlter Beträge, z.B. Abschläge. Angabe als Bruttowert. Details Betrag

`vorausgezahlt`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Rechnung](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/vorausgezahlt")

### vorausgezahlt Type

`object` ([Betrag](betrag.md))

## gemeinderabatt



`gemeinderabatt`

*   is optional

*   Type: `object` ([Gemeinderabatt](gemeinderabatt.md))

*   cannot be null

*   defined in: [Rechnung](gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Gemeinderabatt.schema.json#/properties/gemeinderabatt")

### gemeinderabatt Type

`object` ([Gemeinderabatt](gemeinderabatt.md))

## ausfuehrungsdatum

Das Datum an dem die Leistung erbracht wurde.

`ausfuehrungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-ausfuehrungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/ausfuehrungsdatum")

### ausfuehrungsdatum Type

`string`

### ausfuehrungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## sonderrechnungsart

Sonderrechnungsart

`sonderrechnungsart`

*   is optional

*   Type: `string` ([SonderrechnungsArt](sonderrechnungsart.md))

*   cannot be null

*   defined in: [Rechnung](sonderrechnungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/SonderrechnungsArt.schema.json#/properties/sonderrechnungsart")

### sonderrechnungsart Type

`string` ([SonderrechnungsArt](sonderrechnungsart.md))

### sonderrechnungsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                             | Explanation |
| :-------------------------------- | :---------- |
| `"KONZESSIONSABGABE_TESTAT"`      |             |
| `"INDIVIDUELL_ATYPISCH"`          |             |
| `"INDIVIDUELL_SINGULAER"`         |             |
| `"KWKG_UMLAGE"`                   |             |
| `"OFFSHORE_UMLAGE"`               |             |
| `"P19_STROM_NEV_UMLAGE"`          |             |
| `"P18_ABLAV"`                     |             |
| `"KONZESSIONSABGABE_WECHSEL_RLM"` |             |
| `"PRIVILEGIERUNG_NACH_ENFG"`      |             |

## energierichtung



`energierichtung`

*   is optional

*   Type: `string` ([Energierichtung](energierichtung.md))

*   cannot be null

*   defined in: [Rechnung](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")

### energierichtung Type

`string` ([Energierichtung](energierichtung.md))

### energierichtung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"AUSSP"` |             |
| `"EINSP"` |             |

## beginnPeriodeBilanzierung



`beginnPeriodeBilanzierung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-beginnperiodebilanzierung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/beginnPeriodeBilanzierung")

### beginnPeriodeBilanzierung Type

`string`

### beginnPeriodeBilanzierung Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## endePeriodeNetznutzung



`endePeriodeNetznutzung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-endeperiodenetznutzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/endePeriodeNetznutzung")

### endePeriodeNetznutzung Type

`string`

### endePeriodeNetznutzung Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## steuerbetraege

Eine Liste mit Steuerbeträgen pro Steuerkennzeichen/Steuersatz. Die Summe dieser Beträge ergibt den Wert für
gesamtsteuer. Details Steuerbetrag

`steuerbetraege`

*   is optional

*   Type: `object[]` ([Steuerbetrag](steuerbetrag.md))

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-steuerbetraege.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/steuerbetraege")

### steuerbetraege Type

`object[]` ([Steuerbetrag](steuerbetrag.md))

## rechnungspositionen

Die Rechnungspositionen. Details siehe Rechnungsposition

`rechnungspositionen`

*   is optional

*   Type: `object[]` ([Rechnungsposition](rechnungsposition.md))

*   cannot be null

*   defined in: [Rechnung](rechnung-properties-rechnungspositionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Rechnung.schema.json#/properties/rechnungspositionen")

### rechnungspositionen Type

`object[]` ([Rechnungsposition](rechnungsposition.md))
