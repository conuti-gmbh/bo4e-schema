## Datenstand Type

`object` ([Datenstand](datenstand.md))

# Datenstand Properties

| Property                                                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                |
| :-------------------------------------------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [jahresverbrauchsprognose](#jahresverbrauchsprognose)                       | `object` | Optional | cannot be null | [Datenstand](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/jahresverbrauchsprognose")                                           |
| [tatsaechlichBilanzierteEnergiemenge](#tatsaechlichbilanzierteenergiemenge) | `object` | Optional | cannot be null | [Datenstand](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/tatsaechlichBilanzierteEnergiemenge")                                |
| [zuBilanzierendeEnergiemenge](#zubilanzierendeenergiemenge)                 | `object` | Optional | cannot be null | [Datenstand](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/zuBilanzierendeEnergiemenge")                                        |
| [bilanzkreis](#bilanzkreis)                                                 | `string` | Optional | cannot be null | [Datenstand](datenstand-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Datenstand.schema.json#/properties/bilanzkreis")                       |
| [bilanzierungsgebiet](#bilanzierungsgebiet)                                 | `string` | Optional | cannot be null | [Datenstand](datenstand-properties-bilanzierungsgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Datenstand.schema.json#/properties/bilanzierungsgebiet")       |
| [lastprofile](#lastprofile)                                                 | `array`  | Optional | can be null    | [Datenstand](datenstand-properties-lastprofile.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Datenstand.schema.json#/properties/lastprofile")                       |
| [aggregationsverantwortung](#aggregationsverantwortung)                     | `string` | Optional | cannot be null | [Datenstand](aggregationsverantwortung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Aggregationsverantwortung.schema.json#/properties/aggregationsverantwortung") |

## jahresverbrauchsprognose



`jahresverbrauchsprognose`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Datenstand](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/jahresverbrauchsprognose")

### jahresverbrauchsprognose Type

`object` ([Menge](menge.md))

## tatsaechlichBilanzierteEnergiemenge



`tatsaechlichBilanzierteEnergiemenge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Datenstand](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/tatsaechlichBilanzierteEnergiemenge")

### tatsaechlichBilanzierteEnergiemenge Type

`object` ([Menge](menge.md))

## zuBilanzierendeEnergiemenge



`zuBilanzierendeEnergiemenge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Datenstand](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/zuBilanzierendeEnergiemenge")

### zuBilanzierendeEnergiemenge Type

`object` ([Menge](menge.md))

## bilanzkreis

Bilanzkreis

`bilanzkreis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Datenstand](datenstand-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Datenstand.schema.json#/properties/bilanzkreis")

### bilanzkreis Type

`string`

## bilanzierungsgebiet

Bilanzierungsgebiet

`bilanzierungsgebiet`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Datenstand](datenstand-properties-bilanzierungsgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Datenstand.schema.json#/properties/bilanzierungsgebiet")

### bilanzierungsgebiet Type

`string`

## lastprofile

Eine Liste der verwendeten Lastprofile (SLP, SLP/TLP, ALP etc.)

`lastprofile`

*   is optional

*   Type: `object[]` ([Lastprofil](lastprofil.md))

*   can be null

*   defined in: [Datenstand](datenstand-properties-lastprofile.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Datenstand.schema.json#/properties/lastprofile")

### lastprofile Type

`object[]` ([Lastprofil](lastprofil.md))

## aggregationsverantwortung

Aggregationsverantwortung

`aggregationsverantwortung`

*   is optional

*   Type: `string` ([Aggregationsverantwortung](aggregationsverantwortung.md))

*   cannot be null

*   defined in: [Datenstand](aggregationsverantwortung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Aggregationsverantwortung.schema.json#/properties/aggregationsverantwortung")

### aggregationsverantwortung Type

`string` ([Aggregationsverantwortung](aggregationsverantwortung.md))

### aggregationsverantwortung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"UENB"` |             |
| `"VNB"`  |             |
