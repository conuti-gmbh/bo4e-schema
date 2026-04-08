## Untitled object in undefined Type

`object` ([Details](process.md))

# Untitled object in undefined Properties

| Property                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                |
| :-------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [businessKey](#businesskey)       | `string`  | Optional | cannot be null | [Untitled schema](process-properties-businesskey.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/businessKey")       |
| [dataSource](#datasource)         | `string`  | Optional | cannot be null | [Untitled schema](datasource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/DataSource.schema.json#/properties/dataSource")                         |
| [version](#version)               | `integer` | Optional | cannot be null | [Untitled schema](process-properties-version.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/version")               |
| [edifactVersion](#edifactversion) | `integer` | Optional | cannot be null | [Untitled schema](process-properties-edifactversion.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/edifactVersion") |
| [data](#data)                     | `object`  | Optional | cannot be null | [Untitled schema](processdata.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/ProcessData.schema.json#/properties/data")                             |
| [tenantId](#tenantid)             | `string`  | Optional | cannot be null | [Untitled schema](process-properties-tenantid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/tenantId")             |
| [processDate](#processdate)       | `string`  | Optional | cannot be null | [Untitled schema](process-properties-processdate.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/processDate")       |

## businessKey

BusinessKey

`businessKey`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](process-properties-businesskey.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/businessKey")

### businessKey Type

`string`

## dataSource

CDOC DataSource

`dataSource`

*   is optional

*   Type: `string` ([DataSource](datasource.md))

*   cannot be null

*   defined in: [Untitled schema](datasource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/DataSource.schema.json#/properties/dataSource")

### dataSource Type

`string` ([DataSource](datasource.md))

### dataSource Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"INBOUND"`  |             |
| `"OUTBOUND"` |             |

## version

Versionierung des JSON Schemas

`version`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Untitled schema](process-properties-version.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/version")

### version Type

`integer`

## edifactVersion

Angabe der EDIFACT Formatversion in Format YYYYMM, Beispiel 202504

`edifactVersion`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Untitled schema](process-properties-edifactversion.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/edifactVersion")

### edifactVersion Type

`integer`

## data



`data`

*   is optional

*   Type: `object` ([Details](processdata.md))

*   cannot be null

*   defined in: [Untitled schema](processdata.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/ProcessData.schema.json#/properties/data")

### data Type

`object` ([Details](processdata.md))

## tenantId

Identifikation des Mandanten, NONE bei System ohne Mandanten

`tenantId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](process-properties-tenantid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/tenantId")

### tenantId Type

`string`

### tenantId Default Value

The default value is:

```json
"NONE"
```

## processDate

Prozessdatum

`processDate`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](process-properties-processdate.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Process.schema.json#/properties/processDate")

### processDate Type

`string`

### processDate Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
