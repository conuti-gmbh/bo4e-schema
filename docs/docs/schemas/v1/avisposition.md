## Avisposition Type

`object` ([Avisposition](avisposition.md))

# Avisposition Properties

| Property                                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                  |
| :-------------------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [rechnungsNummer](#rechnungsnummer)           | `string`  | Optional | cannot be null | [Avisposition](avisposition-properties-rechnungsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/rechnungsNummer")           |
| [rechnungsDatum](#rechnungsdatum)             | `string`  | Optional | cannot be null | [Avisposition](avisposition-properties-rechnungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/rechnungsDatum")             |
| [istStorno](#iststorno)                       | `boolean` | Optional | cannot be null | [Avisposition](avisposition-properties-iststorno.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/istStorno")                       |
| [istSelbstausgestellt](#istselbstausgestellt) | `boolean` | Optional | cannot be null | [Avisposition](avisposition-properties-istselbstausgestellt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/istSelbstausgestellt") |
| [gesamtBrutto](#gesamtbrutto)                 | `object`  | Optional | cannot be null | [Avisposition](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/gesamtBrutto")                                                     |
| [zuZahlen](#zuzahlen)                         | `object`  | Optional | cannot be null | [Avisposition](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/zuZahlen")                                                         |
| [referenz](#referenz)                         | `string`  | Optional | cannot be null | [Avisposition](avisposition-properties-referenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/referenz")                         |
| [abweichung](#abweichung)                     | `array`   | Optional | cannot be null | [Avisposition](avisposition-properties-abweichung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/abweichung")                     |
| [positionen](#positionen)                     | `array`   | Optional | cannot be null | [Avisposition](avisposition-properties-positionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/positionen")                     |

## rechnungsNummer

rechnungsNummer

`rechnungsNummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Avisposition](avisposition-properties-rechnungsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/rechnungsNummer")

### rechnungsNummer Type

`string`

## rechnungsDatum

rechnungsDatum

`rechnungsDatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Avisposition](avisposition-properties-rechnungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/rechnungsDatum")

### rechnungsDatum Type

`string`

### rechnungsDatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## istStorno

istStorno

`istStorno`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Avisposition](avisposition-properties-iststorno.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/istStorno")

### istStorno Type

`boolean`

## istSelbstausgestellt

istSelbstausgestellt

`istSelbstausgestellt`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Avisposition](avisposition-properties-istselbstausgestellt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/istSelbstausgestellt")

### istSelbstausgestellt Type

`boolean`

## gesamtBrutto



`gesamtBrutto`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Avisposition](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/gesamtBrutto")

### gesamtBrutto Type

`object` ([Betrag](betrag.md))

## zuZahlen



`zuZahlen`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Avisposition](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/zuZahlen")

### zuZahlen Type

`object` ([Betrag](betrag.md))

## referenz

referenz

`referenz`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Avisposition](avisposition-properties-referenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/referenz")

### referenz Type

`string`

## abweichung

abweichung

`abweichung`

*   is optional

*   Type: `object[]` ([Abweichung](abweichung.md))

*   cannot be null

*   defined in: [Avisposition](avisposition-properties-abweichung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/abweichung")

### abweichung Type

`object[]` ([Abweichung](abweichung.md))

## positionen

positionen

`positionen`

*   is optional

*   Type: `object[]` ([Rueckmeldungsposition](rueckmeldungsposition.md))

*   cannot be null

*   defined in: [Avisposition](avisposition-properties-positionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Avisposition.schema.json#/properties/positionen")

### positionen Type

`object[]` ([Rueckmeldungsposition](rueckmeldungsposition.md))
