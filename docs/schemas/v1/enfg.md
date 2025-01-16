## EnFG Type

`object` ([EnFG](enfg.md))

# EnFG Properties

| Property                                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                   |
| :------------------------------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [grundlageVerringerungUmlagen](#grundlageverringerungumlagen) | `string` | Optional | cannot be null | [EnFG](grundlageverringerungumlagen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/GrundlageVerringerungUmlagen.schema.json#/properties/grundlageVerringerungUmlagen") |
| [grund](#grund)                                               | `array`  | Optional | cannot be null | [EnFG](enfg-properties-grund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/EnFG.schema.json#/properties/grund")                                                        |

## grundlageVerringerungUmlagen

GrundlageVerringerungUmlagen

`grundlageVerringerungUmlagen`

*   is optional

*   Type: `string` ([GrundlageVerringerungUmlagen](grundlageverringerungumlagen.md))

*   cannot be null

*   defined in: [EnFG](grundlageverringerungumlagen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/GrundlageVerringerungUmlagen.schema.json#/properties/grundlageVerringerungUmlagen")

### grundlageVerringerungUmlagen Type

`string` ([GrundlageVerringerungUmlagen](grundlageverringerungumlagen.md))

### grundlageVerringerungUmlagen Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                      | Explanation |
| :----------------------------------------- | :---------- |
| `"ERFUELLT_VORAUSSETZUNG_NACH_ENFG"`       |             |
| `"ERFUELLT_NICHT_VORAUSSETZUNG_NACH_ENFG"` |             |
| `"KEINE_ANGABE"`                           |             |

## grund

grund

`grund`

*   is optional

*   Type: `string[]` ([GrundlageVerringerungUmlagenGrund](grundlageverringerungumlagengrund.md))

*   cannot be null

*   defined in: [EnFG](enfg-properties-grund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/EnFG.schema.json#/properties/grund")

### grund Type

`string[]` ([GrundlageVerringerungUmlagenGrund](grundlageverringerungumlagengrund.md))
