## Tagesmitteltemperatur Type

`object` ([Tagesmitteltemperatur](tagesmitteltemperatur.md))

# Tagesmitteltemperatur Properties

| Property                                                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                               |
| :------------------------------------------------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [berechnungTagesmitteltemperatur](#berechnungtagesmitteltemperatur) | `string` | Optional | cannot be null | [Tagesmitteltemperatur](berechnungsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Berechnungsmethode.schema.json#/properties/berechnungTagesmitteltemperatur")                             |
| [anteilA](#anteila)                                                 | `number` | Optional | cannot be null | [Tagesmitteltemperatur](tagesmitteltemperatur-properties-anteila.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/anteilA")                             |
| [anteilB](#anteilb)                                                 | `number` | Optional | cannot be null | [Tagesmitteltemperatur](tagesmitteltemperatur-properties-anteilb.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/anteilB")                             |
| [anteilC](#anteilc)                                                 | `number` | Optional | cannot be null | [Tagesmitteltemperatur](tagesmitteltemperatur-properties-anteilc.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/anteilC")                             |
| [anteilD](#anteild)                                                 | `number` | Optional | cannot be null | [Tagesmitteltemperatur](tagesmitteltemperatur-properties-anteild.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/anteilD")                             |
| [begrenzungstemperatur](#begrenzungstemperatur)                     | `string` | Optional | cannot be null | [Tagesmitteltemperatur](tagesmitteltemperatur-properties-begrenzungstemperatur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/begrenzungstemperatur") |

## berechnungTagesmitteltemperatur

Berechnungsmethode

`berechnungTagesmitteltemperatur`

*   is optional

*   Type: `string` ([Berechnungsmethode](berechnungsmethode.md))

*   cannot be null

*   defined in: [Tagesmitteltemperatur](berechnungsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Berechnungsmethode.schema.json#/properties/berechnungTagesmitteltemperatur")

### berechnungTagesmitteltemperatur Type

`string` ([Berechnungsmethode](berechnungsmethode.md))

### berechnungTagesmitteltemperatur Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                        | Explanation |
| :--------------------------------------------------------------------------- | :---------- |
| `"24H_MITTELWERT"`                                                           |             |
| `"VOM_ANBIETER_ZUR_VERFUEGUNG_GESTELLTE_AEQUIVALENTE_TAGESMITTELTEMPERATUR"` |             |
| `"AEQUIVALENTE_TAGESMITTELTEMPERATUR"`                                       |             |

## anteilA

Anteil A

`anteilA`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Tagesmitteltemperatur](tagesmitteltemperatur-properties-anteila.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/anteilA")

### anteilA Type

`number`

### anteilA Constraints

**unknown format**: the value of this string must follow the format: `float`

## anteilB

Anteil B

`anteilB`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Tagesmitteltemperatur](tagesmitteltemperatur-properties-anteilb.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/anteilB")

### anteilB Type

`number`

### anteilB Constraints

**unknown format**: the value of this string must follow the format: `float`

## anteilC

Anteil C

`anteilC`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Tagesmitteltemperatur](tagesmitteltemperatur-properties-anteilc.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/anteilC")

### anteilC Type

`number`

### anteilC Constraints

**unknown format**: the value of this string must follow the format: `float`

## anteilD

Anteil D

`anteilD`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Tagesmitteltemperatur](tagesmitteltemperatur-properties-anteild.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/anteilD")

### anteilD Type

`number`

### anteilD Constraints

**unknown format**: the value of this string must follow the format: `float`

## begrenzungstemperatur

Begrenzungstemperatur

`begrenzungstemperatur`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tagesmitteltemperatur](tagesmitteltemperatur-properties-begrenzungstemperatur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/begrenzungstemperatur")

### begrenzungstemperatur Type

`string`
