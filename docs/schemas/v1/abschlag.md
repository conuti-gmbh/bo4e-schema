## Abschlag Type

`object` ([Abschlag](abschlag.md))

# Abschlag Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                            |
| :------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [typ](#typ)         | `string` | Optional | cannot be null | [Abschlag](abschlagtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AbschlagTyp.schema.json#/properties/typ")                 |
| [prozent](#prozent) | `number` | Optional | cannot be null | [Abschlag](abschlag-properties-prozent.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/prozent") |

## typ

AbschlagTyp

`typ`

*   is optional

*   Type: `string` ([AbschlagTyp](abschlagtyp.md))

*   cannot be null

*   defined in: [Abschlag](abschlagtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AbschlagTyp.schema.json#/properties/typ")

### typ Type

`string` ([AbschlagTyp](abschlagtyp.md))

### typ Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                       | Explanation |
| :-------------------------- | :---------- |
| `"GEMEINDERABATT_KAV"`      |             |
| `"ANPASSUNG_P19_STROM_NEV"` |             |

## prozent

Prozentuale Angabe zum Auf-/Abschlag

`prozent`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Abschlag](abschlag-properties-prozent.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/prozent")

### prozent Type

`number`

### prozent Constraints

**unknown format**: the value of this string must follow the format: `float`
