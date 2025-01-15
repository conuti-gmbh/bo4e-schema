## Fehler Type

`object` ([Fehler](fehler.md))

# Fehler Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                  |
| :------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [typ](#typ)                     | `string` | Optional | cannot be null | [Fehler](fehlertyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/FehlerTyp.schema.json#/properties/typ")                             |
| [fehlerDetails](#fehlerdetails) | `array`  | Optional | cannot be null | [Fehler](fehler-properties-fehlerdetails.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Fehler.schema.json#/properties/fehlerDetails") |

## typ

Gibt den Typ des Fehlers an.

`typ`

*   is optional

*   Type: `string` ([FehlerTyp](fehlertyp.md))

*   cannot be null

*   defined in: [Fehler](fehlertyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/FehlerTyp.schema.json#/properties/typ")

### typ Type

`string` ([FehlerTyp](fehlertyp.md))

### typ Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"VERARBEITUNG"` |             |
| `"SYNTAX"`       |             |

## fehlerDetails

Fehlerdetails

`fehlerDetails`

*   is optional

*   Type: `object[]` ([FehlerDetail](fehlerdetail.md))

*   cannot be null

*   defined in: [Fehler](fehler-properties-fehlerdetails.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Fehler.schema.json#/properties/fehlerDetails")

### fehlerDetails Type

`object[]` ([FehlerDetail](fehlerdetail.md))
