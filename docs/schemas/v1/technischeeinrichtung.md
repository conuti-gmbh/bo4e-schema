## TechnischeEinrichtung Type

`object` ([TechnischeEinrichtung](technischeeinrichtung.md))

# TechnischeEinrichtung Properties

| Property                                                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                     |
| :-------------------------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [technischeEinrichtungenVorhanden](#technischeeinrichtungenvorhanden) | `boolean` | Optional | cannot be null | [TechnischeEinrichtung](technischeeinrichtung-properties-technischeeinrichtungenvorhanden.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/TechnischeEinrichtung.schema.json#/properties/technischeEinrichtungenVorhanden") |
| [verbrauchsart](#verbrauchsart)                                       | `string`  | Optional | cannot be null | [TechnischeEinrichtung](verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsart.schema.json#/properties/verbrauchsart")                                                                               |

## technischeEinrichtungenVorhanden

true => ZH7, false => ZH8

`technischeEinrichtungenVorhanden`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [TechnischeEinrichtung](technischeeinrichtung-properties-technischeeinrichtungenvorhanden.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/TechnischeEinrichtung.schema.json#/properties/technischeEinrichtungenVorhanden")

### technischeEinrichtungenVorhanden Type

`boolean`

## verbrauchsart

Verbrauchsart

`verbrauchsart`

*   is optional

*   Type: `string` ([Verbrauchsart](verbrauchsart.md))

*   cannot be null

*   defined in: [TechnischeEinrichtung](verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsart.schema.json#/properties/verbrauchsart")

### verbrauchsart Type

`string` ([Verbrauchsart](verbrauchsart.md))

### verbrauchsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"KL"`   |             |
| `"W"`    |             |
| `"EMOB"` |             |
| `"SB"`   |             |
| `"SW"`   |             |
| `"WK"`   |             |
