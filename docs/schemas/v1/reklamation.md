## Untitled object in undefined Type

`object` ([Details](reklamation.md))

# Untitled object in undefined Properties

| Property                                                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                              |
| :-------------------------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                           | `string` | Required | cannot be null | [Untitled schema](reklamation-properties-botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/boTyp")                                           |
| [versionStruktur](#versionstruktur)                       | `string` | Required | cannot be null | [Untitled schema](reklamation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/versionStruktur")                       |
| [lokationsId](#lokationsid)                               | `string` | Optional | cannot be null | [Untitled schema](reklamation-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/lokationsId")                               |
| [lokationsTyp](#lokationstyp)                             | `string` | Optional | cannot be null | [Untitled schema](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")                                                 |
| [obiskennzahl](#obiskennzahl)                             | `string` | Optional | cannot be null | [Untitled schema](reklamation-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/obiskennzahl")                             |
| [zeitraumMesswertanfrage](#zeitraummesswertanfrage)       | `object` | Optional | cannot be null | [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitraumMesswertanfrage")                                               |
| [reklamationsgrund](#reklamationsgrund)                   | `string` | Optional | cannot be null | [Untitled schema](reklamationsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Reklamationsgrund.schema.json#/properties/reklamationsgrund")                                  |
| [reklamationsgrundBemerkung](#reklamationsgrundbemerkung) | `string` | Optional | cannot be null | [Untitled schema](reklamation-properties-reklamationsgrundbemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/reklamationsgrundBemerkung") |

## boTyp



`boTyp`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](reklamation-properties-botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/boTyp")

### boTyp Type

`string`

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](reklamation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

## lokationsId



`lokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](reklamation-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/lokationsId")

### lokationsId Type

`string`

## lokationsTyp



`lokationsTyp`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")

### lokationsTyp Type

`string`

### lokationsTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"MALO"` |             |
| `"MELO"` |             |

## obiskennzahl



`obiskennzahl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](reklamation-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/obiskennzahl")

### obiskennzahl Type

`string`

## zeitraumMesswertanfrage



`zeitraumMesswertanfrage`

*   is optional

*   Type: `object` ([Details](zeitraum.md))

*   cannot be null

*   defined in: [Untitled schema](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/zeitraumMesswertanfrage")

### zeitraumMesswertanfrage Type

`object` ([Details](zeitraum.md))

## reklamationsgrund



`reklamationsgrund`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](reklamationsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Reklamationsgrund.schema.json#/properties/reklamationsgrund")

### reklamationsgrund Type

`string`

### reklamationsgrund Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"WERTE_ZU_HOCH"`    |             |
| `"WERTE_ZU_NIEDRIG"` |             |
| `"WERTE_FEHLEN"`     |             |

## reklamationsgrundBemerkung



`reklamationsgrundBemerkung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](reklamation-properties-reklamationsgrundbemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Reklamation.schema.json#/properties/reklamationsgrundBemerkung")

### reklamationsgrundBemerkung Type

`string`
