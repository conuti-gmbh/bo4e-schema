## Zuschlag Type

`object` ([Zuschlag](zuschlag.md))

# Zuschlag Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                            |
| :------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [typ](#typ)         | `string` | Optional | cannot be null | [Zuschlag](zuschlagtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ZuschlagTyp.schema.json#/properties/typ")                 |
| [prozent](#prozent) | `number` | Optional | cannot be null | [Zuschlag](zuschlag-properties-prozent.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zuschlag.schema.json#/properties/prozent") |

## typ

ZuschlagTyp

`typ`

*   is optional

*   Type: `string` ([ZuschlagTyp](zuschlagtyp.md))

*   cannot be null

*   defined in: [Zuschlag](zuschlagtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ZuschlagTyp.schema.json#/properties/typ")

### typ Type

`string` ([ZuschlagTyp](zuschlagtyp.md))

### typ Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                           | Explanation |
| :------------------------------------------------------------------------------ | :---------- |
| `"UMSPANNUNGSZUSCHLAG"`                                                         |             |
| `"BETRIEBSMITTEL_P19_STROM_NEV"`                                                |             |
| `"ANPASSUNG_P19_STROM_NEV"`                                                     |             |
| `"ANPASSUNG_PAUSCHALE_NETZENTGELTREDUZIERUNG_NACH_P14A_ENWG_AUF_HOEHE_DER_NNE"` |             |

## prozent

prozent

`prozent`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Zuschlag](zuschlag-properties-prozent.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zuschlag.schema.json#/properties/prozent")

### prozent Type

`number`

### prozent Constraints

**unknown format**: the value of this string must follow the format: `float`
