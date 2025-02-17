## Energiemix Type

`object` ([Energiemix](energiemix.md))

# Energiemix Properties

| Property                                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                          |
| :---------------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [anteil](#anteil)                               | `array`   | Optional | can be null    | [Energiemix](energiemix-properties-anteil.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/anteil")                           |
| [atommuell](#atommuell)                         | `number`  | Optional | cannot be null | [Energiemix](energiemix-properties-atommuell.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/atommuell")                     |
| [bemerkung](#bemerkung)                         | `string`  | Optional | cannot be null | [Energiemix](energiemix-properties-bemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/bemerkung")                     |
| [bezeichnung](#bezeichnung)                     | `string`  | Optional | cannot be null | [Energiemix](energiemix-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/bezeichnung")                 |
| [co2\_emission](#co2_emission)                  | `number`  | Optional | cannot be null | [Energiemix](energiemix-properties-co2_emission.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/co2_emission")               |
| [energieart](#energieart)                       | `string`  | Optional | cannot be null | [Energiemix](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/energieart")                                                |
| [energiemixnummer](#energiemixnummer)           | `integer` | Optional | cannot be null | [Energiemix](energiemix-properties-energiemixnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/energiemixnummer")       |
| [gueltigkeitsjahr](#gueltigkeitsjahr)           | `integer` | Optional | cannot be null | [Energiemix](energiemix-properties-gueltigkeitsjahr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/gueltigkeitsjahr")       |
| [ist\_in\_oeko\_top\_ten](#ist_in_oeko_top_ten) | `boolean` | Optional | cannot be null | [Energiemix](energiemix-properties-ist_in_oeko_top_ten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/ist_in_oeko_top_ten") |
| [oekolabel](#oekolabel)                         | `array`   | Optional | can be null    | [Energiemix](energiemix-properties-oekolabel.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/oekolabel")                     |
| [oekozertifikate](#oekozertifikate)             | `array`   | Optional | can be null    | [Energiemix](energiemix-properties-oekozertifikate.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/oekozertifikate")         |
| [website](#website)                             | `string`  | Optional | cannot be null | [Energiemix](energiemix-properties-website.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/website")                         |

## anteil

Anteile der jeweiligen Erzeugungsart

`anteil`

*   is optional

*   Type: `object[]` ([Energieherkunft](energieherkunft.md))

*   can be null

*   defined in: [Energiemix](energiemix-properties-anteil.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/anteil")

### anteil Type

`object[]` ([Energieherkunft](energieherkunft.md))

## atommuell

Höhe des erzeugten Atommülls in g/kWh

`atommuell`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Energiemix](energiemix-properties-atommuell.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/atommuell")

### atommuell Type

`number`

### atommuell Constraints

**unknown format**: the value of this string must follow the format: `float`

## bemerkung

Bemerkung zum Energiemix

`bemerkung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemix](energiemix-properties-bemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/bemerkung")

### bemerkung Type

`string`

## bezeichnung

Bezeichnung des Energiemix

`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemix](energiemix-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`

## co2\_emission

Höhe des erzeugten CO2-Ausstosses in g/kWh

`co2_emission`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Energiemix](energiemix-properties-co2_emission.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/co2_emission")

### co2\_emission Type

`number`

### co2\_emission Constraints

**unknown format**: the value of this string must follow the format: `float`

## energieart

Sparte

`energieart`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [Energiemix](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/energieart")

### energieart Type

`string` ([Sparte](sparte.md))

### energieart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"STROM"`      |             |
| `"GAS"`        |             |
| `"FERNWAERME"` |             |
| `"NAHWAERME"`  |             |
| `"WASSER"`     |             |
| `"ABWASSER"`   |             |

## energiemixnummer

Eindeutige Nummer zur Identifizierung des Energiemixes

`energiemixnummer`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Energiemix](energiemix-properties-energiemixnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/energiemixnummer")

### energiemixnummer Type

`integer`

## gueltigkeitsjahr

Jahr, für das der Energiemix gilt

`gueltigkeitsjahr`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Energiemix](energiemix-properties-gueltigkeitsjahr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/gueltigkeitsjahr")

### gueltigkeitsjahr Type

`integer`

## ist\_in\_oeko\_top\_ten

Kennzeichen, ob der Versorger zu den Öko Top Ten gehört

`ist_in_oeko_top_ten`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Energiemix](energiemix-properties-ist_in_oeko_top_ten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/ist_in_oeko_top_ten")

### ist\_in\_oeko\_top\_ten Type

`boolean`

## oekolabel

Ökolabel für den Energiemix

`oekolabel`

*   is optional

*   Type: `string[]` ([Oekolabel](oekolabel.md))

*   can be null

*   defined in: [Energiemix](energiemix-properties-oekolabel.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/oekolabel")

### oekolabel Type

`string[]` ([Oekolabel](oekolabel.md))

## oekozertifikate

Zertifikate für den Energiemix

`oekozertifikate`

*   is optional

*   Type: `string[]` ([Oekozertifikat](oekozertifikat.md))

*   can be null

*   defined in: [Energiemix](energiemix-properties-oekozertifikate.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/oekozertifikate")

### oekozertifikate Type

`string[]` ([Oekozertifikat](oekozertifikat.md))

## website

Internetseite, auf der die Strommixdaten veröffentlicht sind

`website`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Energiemix](energiemix-properties-website.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energiemix.schema.json#/properties/website")

### website Type

`string`
