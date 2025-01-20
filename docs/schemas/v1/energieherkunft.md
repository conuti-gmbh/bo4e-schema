## Energieherkunft Type

`object` ([Energieherkunft](energieherkunft.md))

# Energieherkunft Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                             |
| :------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [erzeugungsart](#erzeugungsart) | `string` | Optional | cannot be null | [Energieherkunft](erzeugungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Erzeugungsart.schema.json#/properties/erzeugungsart")                             |
| [anteilProzent](#anteilprozent) | `number` | Optional | cannot be null | [Energieherkunft](energieherkunft-properties-anteilprozent.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energieherkunft.schema.json#/properties/anteilProzent") |

## erzeugungsart

Auflistung der Erzeugungsarten von Energie.

`erzeugungsart`

*   is optional

*   Type: `string` ([Erzeugungsart](erzeugungsart.md))

*   cannot be null

*   defined in: [Energieherkunft](erzeugungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Erzeugungsart.schema.json#/properties/erzeugungsart")

### erzeugungsart Type

`string` ([Erzeugungsart](erzeugungsart.md))

### erzeugungsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"EEG"`                    |             |
| `"KWK"`                    |             |
| `"EEG_DV"`                 |             |
| `"KWK_DV"`                 |             |
| `"WIND"`                   |             |
| `"SOLAR"`                  |             |
| `"KERNKRAFT"`              |             |
| `"WASSER"`                 |             |
| `"GEOTHERMIE"`             |             |
| `"BIOMASSE"`               |             |
| `"KOHLE"`                  |             |
| `"GAS"`                    |             |
| `"SONSTIGE"`               |             |
| `"SONSTIGE_EEG"`           |             |
| `"SONSTIGE_ERZEUGUNGSART"` |             |

## anteilProzent

Prozentualer Anteil der Erzeugung

`anteilProzent`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Energieherkunft](energieherkunft-properties-anteilprozent.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Energieherkunft.schema.json#/properties/anteilProzent")

### anteilProzent Type

`number`

### anteilProzent Constraints

**unknown format**: the value of this string must follow the format: `float`
