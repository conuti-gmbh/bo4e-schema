## Rechnungsposition Type

`object` ([Rechnungsposition](rechnungsposition.md))

# Rechnungsposition Properties

| Property                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :-------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [einzelpreis](#einzelpreis)                         | `object`  | Optional | cannot be null | [Rechnungsposition](preis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/einzelpreis")                                                                        |
| [lieferungBis](#lieferungbis)                       | `string`  | Optional | cannot be null | [Rechnungsposition](rechnungsposition-properties-lieferungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/lieferungBis")                       |
| [lieferungVon](#lieferungvon)                       | `string`  | Optional | cannot be null | [Rechnungsposition](rechnungsposition-properties-lieferungvon.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/lieferungVon")                       |
| [positionsMenge](#positionsmenge)                   | `object`  | Optional | cannot be null | [Rechnungsposition](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/positionsMenge")                                                                     |
| [positionsnummer](#positionsnummer)                 | `integer` | Optional | cannot be null | [Rechnungsposition](rechnungsposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/positionsnummer")                 |
| [artikelnummer](#artikelnummer)                     | `string`  | Optional | cannot be null | [Rechnungsposition](rechnungsposition-properties-artikelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/artikelnummer")                     |
| [teilsummeNetto](#teilsummenetto)                   | `object`  | Optional | cannot be null | [Rechnungsposition](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/teilsummeNetto")                                                                   |
| [teilsummeSteuer](#teilsummesteuer)                 | `object`  | Optional | cannot be null | [Rechnungsposition](steuerbetrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/teilsummeSteuer")                                                      |
| [zeitbezogeneMenge](#zeitbezogenemenge)             | `object`  | Optional | cannot be null | [Rechnungsposition](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/zeitbezogeneMenge")                                                                  |
| [abschlag](#abschlag)                               | `object`  | Optional | cannot be null | [Rechnungsposition](abschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/abschlag")                                                                     |
| [zuschlag](#zuschlag)                               | `object`  | Optional | cannot be null | [Rechnungsposition](zuschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zuschlag.schema.json#/properties/zuschlag")                                                                     |
| [gemeinderabatt](#gemeinderabatt)                   | `object`  | Optional | cannot be null | [Rechnungsposition](gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Gemeinderabatt.schema.json#/properties/gemeinderabatt")                                                   |
| [gesamtZuAbschlagsbetrag](#gesamtzuabschlagsbetrag) | `number`  | Optional | cannot be null | [Rechnungsposition](rechnungsposition-properties-gesamtzuabschlagsbetrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/gesamtZuAbschlagsbetrag") |
| [korrekturfaktor](#korrekturfaktor)                 | `number`  | Optional | cannot be null | [Rechnungsposition](rechnungsposition-properties-korrekturfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/korrekturfaktor")                 |
| [ausfuehrungsdatum](#ausfuehrungsdatum)             | `string`  | Optional | cannot be null | [Rechnungsposition](rechnungsposition-properties-ausfuehrungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/ausfuehrungsdatum")             |

## einzelpreis



`einzelpreis`

*   is optional

*   Type: `object` ([Preis](preis.md))

*   cannot be null

*   defined in: [Rechnungsposition](preis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/einzelpreis")

### einzelpreis Type

`object` ([Preis](preis.md))

## lieferungBis



`lieferungBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnungsposition](rechnungsposition-properties-lieferungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/lieferungBis")

### lieferungBis Type

`string`

### lieferungBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## lieferungVon



`lieferungVon`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnungsposition](rechnungsposition-properties-lieferungvon.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/lieferungVon")

### lieferungVon Type

`string`

### lieferungVon Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## positionsMenge



`positionsMenge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Rechnungsposition](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/positionsMenge")

### positionsMenge Type

`object` ([Menge](menge.md))

## positionsnummer



`positionsnummer`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Rechnungsposition](rechnungsposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/positionsnummer")

### positionsnummer Type

`integer`

## artikelnummer



`artikelnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnungsposition](rechnungsposition-properties-artikelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/artikelnummer")

### artikelnummer Type

`string`

## teilsummeNetto



`teilsummeNetto`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Rechnungsposition](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/teilsummeNetto")

### teilsummeNetto Type

`object` ([Betrag](betrag.md))

## teilsummeSteuer



`teilsummeSteuer`

*   is optional

*   Type: `object` ([Steuerbetrag](steuerbetrag.md))

*   cannot be null

*   defined in: [Rechnungsposition](steuerbetrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Steuerbetrag.schema.json#/properties/teilsummeSteuer")

### teilsummeSteuer Type

`object` ([Steuerbetrag](steuerbetrag.md))

## zeitbezogeneMenge



`zeitbezogeneMenge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Rechnungsposition](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/zeitbezogeneMenge")

### zeitbezogeneMenge Type

`object` ([Menge](menge.md))

## abschlag



`abschlag`

*   is optional

*   Type: `object` ([Abschlag](abschlag.md))

*   cannot be null

*   defined in: [Rechnungsposition](abschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/abschlag")

### abschlag Type

`object` ([Abschlag](abschlag.md))

## zuschlag



`zuschlag`

*   is optional

*   Type: `object` ([Zuschlag](zuschlag.md))

*   cannot be null

*   defined in: [Rechnungsposition](zuschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zuschlag.schema.json#/properties/zuschlag")

### zuschlag Type

`object` ([Zuschlag](zuschlag.md))

## gemeinderabatt



`gemeinderabatt`

*   is optional

*   Type: `object` ([Gemeinderabatt](gemeinderabatt.md))

*   cannot be null

*   defined in: [Rechnungsposition](gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Gemeinderabatt.schema.json#/properties/gemeinderabatt")

### gemeinderabatt Type

`object` ([Gemeinderabatt](gemeinderabatt.md))

## gesamtZuAbschlagsbetrag



`gesamtZuAbschlagsbetrag`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Rechnungsposition](rechnungsposition-properties-gesamtzuabschlagsbetrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/gesamtZuAbschlagsbetrag")

### gesamtZuAbschlagsbetrag Type

`number`

### gesamtZuAbschlagsbetrag Constraints

**unknown format**: the value of this string must follow the format: `float`

## korrekturfaktor



`korrekturfaktor`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Rechnungsposition](rechnungsposition-properties-korrekturfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/korrekturfaktor")

### korrekturfaktor Type

`number`

### korrekturfaktor Constraints

**unknown format**: the value of this string must follow the format: `float`

## ausfuehrungsdatum



`ausfuehrungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Rechnungsposition](rechnungsposition-properties-ausfuehrungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Rechnungsposition.schema.json#/properties/ausfuehrungsdatum")

### ausfuehrungsdatum Type

`string`

### ausfuehrungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
