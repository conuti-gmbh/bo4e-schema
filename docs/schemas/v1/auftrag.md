## Auftrag Type

`object` ([Auftrag](auftrag.md))

# Auftrag Properties

| Property                                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                            |
| :------------------------------------------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                         | `string` | Required | cannot be null | [Auftrag](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                            |
| [versionStruktur](#versionstruktur)                     | `string` | Required | cannot be null | [Auftrag](auftrag-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/versionStruktur")                     |
| [ausfuehrungsdatum](#ausfuehrungsdatum)                 | `string` | Optional | cannot be null | [Auftrag](auftrag-properties-ausfuehrungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/ausfuehrungsdatum")                 |
| [fertigstellungsdatum](#fertigstellungsdatum)           | `string` | Optional | cannot be null | [Auftrag](auftrag-properties-fertigstellungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/fertigstellungsdatum")           |
| [startdatum](#startdatum)                               | `string` | Optional | cannot be null | [Auftrag](auftrag-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/startdatum")                               |
| [sparte](#sparte)                                       | `string` | Optional | cannot be null | [Auftrag](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                                         |
| [lieferanschrift](#lieferanschrift)                     | `object` | Optional | cannot be null | [Auftrag](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/lieferanschrift")                                               |
| [marktlokationsId](#marktlokationsid)                   | `string` | Optional | cannot be null | [Auftrag](auftrag-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/marktlokationsId")                   |
| [mindestpreis](#mindestpreis)                           | `object` | Optional | cannot be null | [Auftrag](preis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/mindestpreis")                                                      |
| [hoechstpreis](#hoechstpreis)                           | `object` | Optional | cannot be null | [Auftrag](preis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/hoechstpreis")                                                      |
| [energierichtung](#energierichtung)                     | `string` | Optional | cannot be null | [Auftrag](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")                              |
| [berechnungspreis](#berechnungspreis)                   | `number` | Optional | cannot be null | [Auftrag](auftrag-properties-berechnungspreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/berechnungspreis")                   |
| [summeGesamt](#summegesamt)                             | `number` | Optional | cannot be null | [Auftrag](auftrag-properties-summegesamt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/summeGesamt")                             |
| [verschobenerAbmeldetermin](#verschobenerabmeldetermin) | `string` | Optional | cannot be null | [Auftrag](auftrag-properties-verschobenerabmeldetermin.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/verschobenerAbmeldetermin") |
| [behebungsZeitpunkt](#behebungszeitpunkt)               | `string` | Optional | cannot be null | [Auftrag](auftrag-properties-behebungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/behebungsZeitpunkt")               |
| [lieferadresseAltgeraete](#lieferadressealtgeraete)     | `object` | Optional | cannot be null | [Auftrag](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/lieferadresseAltgeraete")                    |
| [definitionsTyp](#definitionstyp)                       | `string` | Optional | cannot be null | [Auftrag](definitionstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DefinitionsTyp.schema.json#/properties/definitionsTyp")                                 |
| [positionsdaten](#positionsdaten)                       | `array`  | Optional | cannot be null | [Auftrag](auftrag-properties-positionsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/positionsdaten")                       |
| [bemerkungen](#bemerkungen)                             | `array`  | Optional | cannot be null | [Auftrag](auftrag-properties-bemerkungen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/bemerkungen")                             |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Auftrag](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"AUFTRAG"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## ausfuehrungsdatum



`ausfuehrungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-ausfuehrungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/ausfuehrungsdatum")

### ausfuehrungsdatum Type

`string`

### ausfuehrungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## fertigstellungsdatum



`fertigstellungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-fertigstellungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/fertigstellungsdatum")

### fertigstellungsdatum Type

`string`

### fertigstellungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## startdatum



`startdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/startdatum")

### startdatum Type

`string`

### startdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## sparte



`sparte`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [Auftrag](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

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

## lieferanschrift



`lieferanschrift`

*   is optional

*   Type: `object` ([Adresse](adresse.md))

*   cannot be null

*   defined in: [Auftrag](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/lieferanschrift")

### lieferanschrift Type

`object` ([Adresse](adresse.md))

## marktlokationsId



`marktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/marktlokationsId")

### marktlokationsId Type

`string`

## mindestpreis



`mindestpreis`

*   is optional

*   Type: `object` ([Preis](preis.md))

*   cannot be null

*   defined in: [Auftrag](preis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/mindestpreis")

### mindestpreis Type

`object` ([Preis](preis.md))

## hoechstpreis



`hoechstpreis`

*   is optional

*   Type: `object` ([Preis](preis.md))

*   cannot be null

*   defined in: [Auftrag](preis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/hoechstpreis")

### hoechstpreis Type

`object` ([Preis](preis.md))

## energierichtung



`energierichtung`

*   is optional

*   Type: `string` ([Energierichtung](energierichtung.md))

*   cannot be null

*   defined in: [Auftrag](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")

### energierichtung Type

`string` ([Energierichtung](energierichtung.md))

### energierichtung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"AUSSP"` |             |
| `"EINSP"` |             |

## berechnungspreis



`berechnungspreis`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-berechnungspreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/berechnungspreis")

### berechnungspreis Type

`number`

### berechnungspreis Constraints

**unknown format**: the value of this string must follow the format: `float`

## summeGesamt



`summeGesamt`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-summegesamt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/summeGesamt")

### summeGesamt Type

`number`

### summeGesamt Constraints

**unknown format**: the value of this string must follow the format: `float`

## verschobenerAbmeldetermin



`verschobenerAbmeldetermin`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-verschobenerabmeldetermin.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/verschobenerAbmeldetermin")

### verschobenerAbmeldetermin Type

`string`

### verschobenerAbmeldetermin Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## behebungsZeitpunkt



`behebungsZeitpunkt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-behebungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/behebungsZeitpunkt")

### behebungsZeitpunkt Type

`string`

### behebungsZeitpunkt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## lieferadresseAltgeraete



`lieferadresseAltgeraete`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Auftrag](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/lieferadresseAltgeraete")

### lieferadresseAltgeraete Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## definitionsTyp



`definitionsTyp`

*   is optional

*   Type: `string` ([DefinitionsTyp](definitionstyp.md))

*   cannot be null

*   defined in: [Auftrag](definitionstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DefinitionsTyp.schema.json#/properties/definitionsTyp")

### definitionsTyp Type

`string` ([DefinitionsTyp](definitionstyp.md))

### definitionsTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"ZAEHLZEIT"`       |             |
| `"SCHALTZEIT"`      |             |
| `"LEISTUNGSKURVEN"` |             |

## positionsdaten



`positionsdaten`

*   is optional

*   Type: `object[]` ([AuftragPosition](auftragposition.md))

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-positionsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/positionsdaten")

### positionsdaten Type

`object[]` ([AuftragPosition](auftragposition.md))

## bemerkungen



`bemerkungen`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Auftrag](auftrag-properties-bemerkungen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Auftrag.schema.json#/properties/bemerkungen")

### bemerkungen Type

`string[]`
