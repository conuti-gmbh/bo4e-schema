## Zaehlzeitregister Type

`object` ([Zaehlzeitregister](zaehlzeitregister.md))

# Zaehlzeitregister Properties

| Property                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                               |
| :------------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [register](#register)                       | `string` | Optional | cannot be null | [Zaehlzeitregister](zaehlzeitregister-properties-register.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeitregister.schema.json#/properties/register")                       |
| [zaehlzeitDefinition](#zaehlzeitdefinition) | `string` | Optional | cannot be null | [Zaehlzeitregister](zaehlzeitregister-properties-zaehlzeitdefinition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeitregister.schema.json#/properties/zaehlzeitDefinition") |
| [schwachlastfaehig](#schwachlastfaehig)     | `string` | Optional | cannot be null | [Zaehlzeitregister](schwachlastfaehig.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Schwachlastfaehig.schema.json#/properties/schwachlastfaehig")                                 |

## register



`register`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeitregister](zaehlzeitregister-properties-register.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeitregister.schema.json#/properties/register")

### register Type

`string`

## zaehlzeitDefinition



`zaehlzeitDefinition`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeitregister](zaehlzeitregister-properties-zaehlzeitdefinition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeitregister.schema.json#/properties/zaehlzeitDefinition")

### zaehlzeitDefinition Type

`string`

## schwachlastfaehig



`schwachlastfaehig`

*   is optional

*   Type: `string` ([Schwachlastfaehig](schwachlastfaehig.md))

*   cannot be null

*   defined in: [Zaehlzeitregister](schwachlastfaehig.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Schwachlastfaehig.schema.json#/properties/schwachlastfaehig")

### schwachlastfaehig Type

`string` ([Schwachlastfaehig](schwachlastfaehig.md))

### schwachlastfaehig Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                       | Explanation |
| :-------------------------- | :---------- |
| `"SCHWACHLASTFAEHIG"`       |             |
| `"NICHT_SCHWACHLASTFAEHIG"` |             |
