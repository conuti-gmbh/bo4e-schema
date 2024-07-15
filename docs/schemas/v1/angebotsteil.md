## Angebotsteil Type

`object` ([Angebotsteil](angebotsteil.md))

# Angebotsteil Properties

| Property                                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                            |
| :------------------------------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [anfrageSubreferenz](#anfragesubreferenz)               | `string` | Optional | cannot be null | [Angebotsteil](angebotsteil-properties-anfragesubreferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsteil.schema.json#/properties/anfrageSubreferenz")               |
| [gesamtmengeangebotsteil](#gesamtmengeangebotsteil)     | `object` | Optional | cannot be null | [Angebotsteil](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/gesamtmengeangebotsteil")                                                      |
| [gesamtkostenangebotsteil](#gesamtkostenangebotsteil)   | `object` | Optional | cannot be null | [Angebotsteil](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/gesamtkostenangebotsteil")                                                   |
| [lieferzeitraum](#lieferzeitraum)                       | `object` | Optional | cannot be null | [Angebotsteil](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/lieferzeitraum")                                                         |
| [verweisKatalognummer](#verweiskatalognummer)           | `object` | Optional | cannot be null | [Angebotsteil](katalogverweis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Katalogverweis.schema.json#/properties/verweisKatalognummer")                                       |
| [lieferstellenangebotsteil](#lieferstellenangebotsteil) | `array`  | Optional | cannot be null | [Angebotsteil](angebotsteil-properties-lieferstellenangebotsteil.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsteil.schema.json#/properties/lieferstellenangebotsteil") |
| [positionen](#positionen)                               | `array`  | Optional | cannot be null | [Angebotsteil](angebotsteil-properties-positionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsteil.schema.json#/properties/positionen")                               |

## anfrageSubreferenz



`anfrageSubreferenz`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Angebotsteil](angebotsteil-properties-anfragesubreferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsteil.schema.json#/properties/anfrageSubreferenz")

### anfrageSubreferenz Type

`string`

## gesamtmengeangebotsteil



`gesamtmengeangebotsteil`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Angebotsteil](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/gesamtmengeangebotsteil")

### gesamtmengeangebotsteil Type

`object` ([Menge](menge.md))

## gesamtkostenangebotsteil



`gesamtkostenangebotsteil`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Angebotsteil](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/gesamtkostenangebotsteil")

### gesamtkostenangebotsteil Type

`object` ([Betrag](betrag.md))

## lieferzeitraum



`lieferzeitraum`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Angebotsteil](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/lieferzeitraum")

### lieferzeitraum Type

`object` ([Zeitraum](zeitraum.md))

## verweisKatalognummer



`verweisKatalognummer`

*   is optional

*   Type: `object` ([Katalogverweis](katalogverweis.md))

*   cannot be null

*   defined in: [Angebotsteil](katalogverweis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Katalogverweis.schema.json#/properties/verweisKatalognummer")

### verweisKatalognummer Type

`object` ([Katalogverweis](katalogverweis.md))

## lieferstellenangebotsteil



`lieferstellenangebotsteil`

*   is optional

*   Type: `object[]` ([Marktlokation](marktlokation.md))

*   cannot be null

*   defined in: [Angebotsteil](angebotsteil-properties-lieferstellenangebotsteil.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsteil.schema.json#/properties/lieferstellenangebotsteil")

### lieferstellenangebotsteil Type

`object[]` ([Marktlokation](marktlokation.md))

## positionen



`positionen`

*   is optional

*   Type: `object[]` ([Angebotsposition](angebotsposition.md))

*   cannot be null

*   defined in: [Angebotsteil](angebotsteil-properties-positionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsteil.schema.json#/properties/positionen")

### positionen Type

`object[]` ([Angebotsposition](angebotsposition.md))
