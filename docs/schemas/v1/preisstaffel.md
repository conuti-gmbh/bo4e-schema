## Preisstaffel Type

`object` ([Preisstaffel](preisstaffel.md))

# Preisstaffel Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                          |
| :------------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [einheitspreis](#einheitspreis)       | `number` | Optional | cannot be null | [Preisstaffel](preisstaffel-properties-einheitspreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisstaffel.schema.json#/properties/einheitspreis")       |
| [staffelgrenzeVon](#staffelgrenzevon) | `number` | Optional | cannot be null | [Preisstaffel](preisstaffel-properties-staffelgrenzevon.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisstaffel.schema.json#/properties/staffelgrenzeVon") |
| [staffelgrenzeBis](#staffelgrenzebis) | `number` | Optional | cannot be null | [Preisstaffel](preisstaffel-properties-staffelgrenzebis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisstaffel.schema.json#/properties/staffelgrenzeBis") |
| [sigmoidparameter](#sigmoidparameter) | `object` | Optional | cannot be null | [Preisstaffel](sigmoidparameter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Sigmoidparameter.schema.json#/properties/sigmoidparameter")                     |
| [einheit](#einheit)                   | `string` | Optional | cannot be null | [Preisstaffel](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/einheit")                                   |

## einheitspreis

einheitspreis

`einheitspreis`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Preisstaffel](preisstaffel-properties-einheitspreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisstaffel.schema.json#/properties/einheitspreis")

### einheitspreis Type

`number`

### einheitspreis Constraints

**unknown format**: the value of this string must follow the format: `float`

## staffelgrenzeVon

staffelgrenzeVon

`staffelgrenzeVon`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Preisstaffel](preisstaffel-properties-staffelgrenzevon.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisstaffel.schema.json#/properties/staffelgrenzeVon")

### staffelgrenzeVon Type

`number`

### staffelgrenzeVon Constraints

**unknown format**: the value of this string must follow the format: `float`

## staffelgrenzeBis

staffelgrenzeBis

`staffelgrenzeBis`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Preisstaffel](preisstaffel-properties-staffelgrenzebis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisstaffel.schema.json#/properties/staffelgrenzeBis")

### staffelgrenzeBis Type

`number`

### staffelgrenzeBis Constraints

**unknown format**: the value of this string must follow the format: `float`

## sigmoidparameter



`sigmoidparameter`

*   is optional

*   Type: `object` ([Sigmoidparameter](sigmoidparameter.md))

*   cannot be null

*   defined in: [Preisstaffel](sigmoidparameter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Sigmoidparameter.schema.json#/properties/sigmoidparameter")

### sigmoidparameter Type

`object` ([Sigmoidparameter](sigmoidparameter.md))

## einheit

Einheit: Messgrößen, die per Messung oder Vorgabe ermittelt werden können

`einheit`

*   is optional

*   Type: `string` ([Mengeneinheit](mengeneinheit.md))

*   cannot be null

*   defined in: [Preisstaffel](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/einheit")

### einheit Type

`string` ([Mengeneinheit](mengeneinheit.md))

### einheit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"W"`          |             |
| `"WH"`         |             |
| `"KW"`         |             |
| `"KWH"`        |             |
| `"KVARH"`      |             |
| `"MW"`         |             |
| `"MWH"`        |             |
| `"STUECK"`     |             |
| `"KUBIKMETER"` |             |
| `"STUNDE"`     |             |
| `"TAG"`        |             |
| `"MONAT"`      |             |
| `"JAHR"`       |             |
| `"PROZENT"`    |             |
| `"ANZAHL"`     |             |
| `"VAR"`        |             |
| `"KVAR"`       |             |
| `"VARH"`       |             |
| `"KWHK"`       |             |
| `"Z16"`        |             |
| `"KWT"`        |             |
