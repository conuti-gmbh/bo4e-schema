## PositionsAufAbschlag Type

`object` ([PositionsAufAbschlag](positionsaufabschlag.md))

# PositionsAufAbschlag Properties

| Property                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                  |
| :-------------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bezeichnung](#bezeichnung)                   | `string` | Optional | cannot be null | [PositionsAufAbschlag](positionsaufabschlag-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/PositionsAufAbschlag.schema.json#/properties/bezeichnung")           |
| [beschreibung](#beschreibung)                 | `string` | Optional | cannot be null | [PositionsAufAbschlag](positionsaufabschlag-properties-beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/PositionsAufAbschlag.schema.json#/properties/beschreibung")         |
| [aufAbschlagstyp](#aufabschlagstyp)           | `string` | Optional | cannot be null | [PositionsAufAbschlag](aufabschlagstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AufAbschlagstyp.schema.json#/properties/aufAbschlagstyp")                                       |
| [aufAbschlagswert](#aufabschlagswert)         | `number` | Optional | cannot be null | [PositionsAufAbschlag](positionsaufabschlag-properties-aufabschlagswert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/PositionsAufAbschlag.schema.json#/properties/aufAbschlagswert") |
| [aufAbschlagswaehrung](#aufabschlagswaehrung) | `string` | Optional | cannot be null | [PositionsAufAbschlag](waehrungseinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waehrungseinheit.schema.json#/properties/aufAbschlagswaehrung")                                |

## bezeichnung

bezeichnung

`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [PositionsAufAbschlag](positionsaufabschlag-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/PositionsAufAbschlag.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`

## beschreibung

beschreibung

`beschreibung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [PositionsAufAbschlag](positionsaufabschlag-properties-beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/PositionsAufAbschlag.schema.json#/properties/beschreibung")

### beschreibung Type

`string`

## aufAbschlagstyp

AufAbschlagstyp

`aufAbschlagstyp`

*   is optional

*   Type: `string` ([AufAbschlagstyp](aufabschlagstyp.md))

*   cannot be null

*   defined in: [PositionsAufAbschlag](aufabschlagstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/AufAbschlagstyp.schema.json#/properties/aufAbschlagstyp")

### aufAbschlagstyp Type

`string` ([AufAbschlagstyp](aufabschlagstyp.md))

### aufAbschlagstyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"RELATIV"` |             |
| `"ABSOLUT"` |             |

## aufAbschlagswert

aufAbschlagswert

`aufAbschlagswert`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [PositionsAufAbschlag](positionsaufabschlag-properties-aufabschlagswert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/PositionsAufAbschlag.schema.json#/properties/aufAbschlagswert")

### aufAbschlagswert Type

`number`

### aufAbschlagswert Constraints

**unknown format**: the value of this string must follow the format: `float`

## aufAbschlagswaehrung

Waehrungseinheit

`aufAbschlagswaehrung`

*   is optional

*   Type: `string` ([Waehrungseinheit](waehrungseinheit.md))

*   cannot be null

*   defined in: [PositionsAufAbschlag](waehrungseinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waehrungseinheit.schema.json#/properties/aufAbschlagswaehrung")

### aufAbschlagswaehrung Type

`string` ([Waehrungseinheit](waehrungseinheit.md))

### aufAbschlagswaehrung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"EUR"` |             |
| `"CT"`  |             |
