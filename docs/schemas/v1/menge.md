## Menge Type

`object` ([Menge](menge.md))

# Menge Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                         |
| :------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [wert](#wert)             | `number` | Optional | cannot be null | [Menge](menge-properties-wert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/wert")             |
| [einheit](#einheit)       | `string` | Optional | cannot be null | [Menge](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/einheit")         |
| [startdatum](#startdatum) | `string` | Optional | cannot be null | [Menge](menge-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/startdatum") |
| [enddatum](#enddatum)     | `string` | Optional | cannot be null | [Menge](menge-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/enddatum")     |

## wert

Wert

`wert`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Menge](menge-properties-wert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/wert")

### wert Type

`number`

### wert Constraints

**unknown format**: the value of this string must follow the format: `float`

## einheit

Einheit: Messgrößen, die per Messung oder Vorgabe ermittelt werden können

`einheit`

*   is optional

*   Type: `string` ([Mengeneinheit](mengeneinheit.md))

*   cannot be null

*   defined in: [Menge](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/einheit")

### einheit Type

`string` ([Mengeneinheit](mengeneinheit.md))

### einheit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                     | Explanation |
| :------------------------ | :---------- |
| `"W"`                     |             |
| `"WH"`                    |             |
| `"KW"`                    |             |
| `"KWH"`                   |             |
| `"KVARH"`                 |             |
| `"MW"`                    |             |
| `"MWH"`                   |             |
| `"STUECK"`                |             |
| `"KUBIKMETER"`            |             |
| `"STUNDE"`                |             |
| `"TAG"`                   |             |
| `"MONAT"`                 |             |
| `"JAHR"`                  |             |
| `"PROZENT"`               |             |
| `"ANZAHL"`                |             |
| `"VAR"`                   |             |
| `"KVAR"`                  |             |
| `"VARH"`                  |             |
| `"KWHK"`                  |             |
| `"Z16"`                   |             |
| `"KWT"`                   |             |
| `"WATT_PRO_QUADRATMETER"` |             |
| `"METER_PRO_SEKUNDE"`     |             |

## startdatum

startdatum

`startdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Menge](menge-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/startdatum")

### startdatum Type

`string`

### startdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## enddatum

enddatum

`enddatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Menge](menge-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/enddatum")

### enddatum Type

`string`

### enddatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
