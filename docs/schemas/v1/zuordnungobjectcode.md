## ZuordnungObjectcode Type

`object` ([ZuordnungObjectcode](zuordnungobjectcode.md))

# ZuordnungObjectcode Properties

| Property                                                                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                    |
| :------------------------------------------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [referenzLokationsTyp](#referenzlokationstyp)                                         | `string` | Optional | cannot be null | [ZuordnungObjectcode](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/referenzLokationsTyp")                                                                           |
| [referenzLokationsId](#referenzlokationsid)                                           | `string` | Optional | cannot be null | [ZuordnungObjectcode](zuordnungobjectcode-properties-referenzlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/referenzLokationsId")                                           |
| [vorgelagerteLokationTyp](#vorgelagertelokationtyp)                                   | `string` | Optional | cannot be null | [ZuordnungObjectcode](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/vorgelagerteLokationTyp")                                                                        |
| [vorgelagerteLokationId](#vorgelagertelokationid)                                     | `string` | Optional | cannot be null | [ZuordnungObjectcode](zuordnungobjectcode-properties-vorgelagertelokationid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/vorgelagerteLokationId")                                     |
| [objectcode](#objectcode)                                                             | `array`  | Optional | can be null    | [ZuordnungObjectcode](zuordnungobjectcode-properties-objectcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/objectcode")                                                             |
| [referenzMarktlokationTechnischeRessource](#referenzmarktlokationtechnischeressource) | `array`  | Optional | can be null    | [ZuordnungObjectcode](zuordnungobjectcode-properties-referenzmarktlokationtechnischeressource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/referenzMarktlokationTechnischeRessource") |

## referenzLokationsTyp

Gibt an, ob es sich um eine Markt- oder Messlokation handelt

`referenzLokationsTyp`

*   is optional

*   Type: `string` ([Lokationstyp](lokationstyp.md))

*   cannot be null

*   defined in: [ZuordnungObjectcode](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/referenzLokationsTyp")

### referenzLokationsTyp Type

`string` ([Lokationstyp](lokationstyp.md))

### referenzLokationsTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"MALO"`                 |             |
| `"MELO"`                 |             |
| `"NELO"`                 |             |
| `"TECHNISCHE_RESSOURCE"` |             |
| `"STEUERBARE_RESSOURCE"` |             |
| `"TRANCHE"`              |             |

## referenzLokationsId

referenzLokationsId

`referenzLokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [ZuordnungObjectcode](zuordnungobjectcode-properties-referenzlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/referenzLokationsId")

### referenzLokationsId Type

`string`

## vorgelagerteLokationTyp

Gibt an, ob es sich um eine Markt- oder Messlokation handelt

`vorgelagerteLokationTyp`

*   is optional

*   Type: `string` ([Lokationstyp](lokationstyp.md))

*   cannot be null

*   defined in: [ZuordnungObjectcode](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/vorgelagerteLokationTyp")

### vorgelagerteLokationTyp Type

`string` ([Lokationstyp](lokationstyp.md))

### vorgelagerteLokationTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"MALO"`                 |             |
| `"MELO"`                 |             |
| `"NELO"`                 |             |
| `"TECHNISCHE_RESSOURCE"` |             |
| `"STEUERBARE_RESSOURCE"` |             |
| `"TRANCHE"`              |             |

## vorgelagerteLokationId

vorgelagerteLokationId

`vorgelagerteLokationId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [ZuordnungObjectcode](zuordnungobjectcode-properties-vorgelagertelokationid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/vorgelagerteLokationId")

### vorgelagerteLokationId Type

`string`

## objectcode

objectcode

`objectcode`

*   is optional

*   Type: `object[]` ([Objectcode](objectcode.md))

*   can be null

*   defined in: [ZuordnungObjectcode](zuordnungobjectcode-properties-objectcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/objectcode")

### objectcode Type

`object[]` ([Objectcode](objectcode.md))

## referenzMarktlokationTechnischeRessource

referenzMarktlokationTechnischeRessource

`referenzMarktlokationTechnischeRessource`

*   is optional

*   Type: `string[]`

*   can be null

*   defined in: [ZuordnungObjectcode](zuordnungobjectcode-properties-referenzmarktlokationtechnischeressource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abschlag.schema.json#/properties/referenzMarktlokationTechnischeRessource")

### referenzMarktlokationTechnischeRessource Type

`string[]`
