## ExterneReferenz Type

`object` ([ExterneReferenz](externereferenz.md))

# ExterneReferenz Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                     |
| :---------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [exRefName](#exrefname) | `string` | Optional | cannot be null | [ExterneReferenz](externereferenz-properties-exrefname.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ExterneReferenz.schema.json#/properties/exRefName") |
| [exRefWert](#exrefwert) | `string` | Optional | cannot be null | [ExterneReferenz](externereferenz-properties-exrefwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ExterneReferenz.schema.json#/properties/exRefWert") |

## exRefName

Bezeichnung der externen Referenz (z.B. "hochfrequenz integration services")

`exRefName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [ExterneReferenz](externereferenz-properties-exrefname.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ExterneReferenz.schema.json#/properties/exRefName")

### exRefName Type

`string`

### exRefName Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                | Explanation |
| :----------------------------------- | :---------- |
| `"Kundennummer beim Lieferanten"`    |             |
| `"Kundennummer beim Altlieferanten"` |             |

## exRefWert

Wert der externen Referenz (z.B. "123456"; "4711")

`exRefWert`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [ExterneReferenz](externereferenz-properties-exrefwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ExterneReferenz.schema.json#/properties/exRefWert")

### exRefWert Type

`string`
