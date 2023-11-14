## Untitled object in undefined Type

`object` ([Details](enfg.md))

# Untitled object in undefined Properties

| Property                                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                              |
| :------------------------------------------------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [grundlageVerringerungUmlagen](#grundlageverringerungumlagen) | `string` | Optional | cannot be null | [Untitled schema](grundlageverringerungumlagen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/GrundlageVerringerungUmlagen.schema.json#/properties/grundlageVerringerungUmlagen") |
| [grund](#grund)                                               | `string` | Optional | cannot be null | [Untitled schema](grundlageverringerungumlagengrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AbgabeArt.schema.json#/properties/grund")                                      |

## grundlageVerringerungUmlagen



`grundlageVerringerungUmlagen`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](grundlageverringerungumlagen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/GrundlageVerringerungUmlagen.schema.json#/properties/grundlageVerringerungUmlagen")

### grundlageVerringerungUmlagen Type

`string`

### grundlageVerringerungUmlagen Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                      | Explanation |
| :----------------------------------------- | :---------- |
| `"ERFUELLT_VORAUSSETZUNG_NACH_ENFG"`       |             |
| `"ERFUELLT_NICHT_VORAUSSETZUNG_NACH_ENFG"` |             |
| `"KEINE_ANGABE"`                           |             |

## grund



`grund`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](grundlageverringerungumlagengrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AbgabeArt.schema.json#/properties/grund")

### grund Type

`string`

### grund Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                     | Explanation |
| :------------------------------------------------------------------------ | :---------- |
| `"ENFG_STROMSPEICHER_UND_VERLUSTENERGIE"`                                 |             |
| `"ENFG_ELEKTRISCH_ANGETRIEBENE_WAERMEPUMPEN"`                             |             |
| `"ENFG_UMLAGEERHEBUNG_BEI_ANLAGEN_ZUR_VERSTROMUNG_VON_KUPPELGASEN"`       |             |
| `"ENFG_HERSTELLUNG_VON_GRUENEN_WASSERSTOFF"`                              |             |
| `"ENFG_STROMKOSTENINTENSIVE_UNTERNEHMEN"`                                 |             |
| `"ENFG_HERSTELLUNG_VON_WASSERSTOFF_IN_STROMKOSTENINTENSIVEN_UNTERNEHMEN"` |             |
| `"ENFG_SCHIENENBAHNEN"`                                                   |             |
| `"ENFG_ELEKTRISCHE_BETRIEBENE_BUSSEN_IM_LINIENVERKEHR"`                   |             |
| `"ENFG_LANDSTROMANLAGEN"`                                                 |             |
