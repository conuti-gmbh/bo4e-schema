## Untitled object in undefined Type

`object` ([Details](zusatzdaten.md))

# Untitled object in undefined Properties

| Property                                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                        |
| :------------------------------------------------ | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [prozessId](#prozessid)                           | `string`  | Optional | cannot be null | [Untitled schema](zusatzdaten-properties-prozessid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/prozessId")                           |
| [eventname](#eventname)                           | `string`  | Optional | cannot be null | [Untitled schema](eventname.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/EventName.schema.json#/properties/eventname")                                                    |
| [ediTyp](#edityp)                                 | `string`  | Optional | cannot be null | [Untitled schema](zusatzdaten-properties-edityp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/ediTyp")                                 |
| [ediEmpfangsDatum](#ediempfangsdatum)             | `string`  | Optional | cannot be null | [Untitled schema](zusatzdaten-properties-ediempfangsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/ediEmpfangsDatum")             |
| [ediVersion](#ediversion)                         | `string`  | Optional | cannot be null | [Untitled schema](zusatzdaten-properties-ediversion.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/ediVersion")                         |
| [marktpartnerRolle](#marktpartnerrolle)           | `string`  | Optional | cannot be null | [Untitled schema](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/marktpartnerRolle")                                          |
| [contrlReferenz](#contrlreferenz)                 | `string`  | Optional | cannot be null | [Untitled schema](zusatzdaten-properties-contrlreferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/contrlReferenz")                 |
| [parentBusinessKey](#parentbusinesskey)           | `string`  | Optional | cannot be null | [Untitled schema](zusatzdaten-properties-parentbusinesskey.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/parentBusinessKey")           |
| [targetBusinessKey](#targetbusinesskey)           | `string`  | Optional | cannot be null | [Untitled schema](zusatzdaten-properties-targetbusinesskey.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/targetBusinessKey")           |
| [ermaechtigungVorhanden](#ermaechtigungvorhanden) | `boolean` | Optional | cannot be null | [Untitled schema](zusatzdaten-properties-ermaechtigungvorhanden.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/ermaechtigungVorhanden") |

## prozessId



`prozessId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](zusatzdaten-properties-prozessid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/prozessId")

### prozessId Type

`string`

## eventname

Identifikation des Events

`eventname`

*   is optional

*   Type: `string` ([EventName](eventname.md))

*   cannot be null

*   defined in: [Untitled schema](eventname.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/EventName.schema.json#/properties/eventname")

### eventname Type

`string` ([EventName](eventname.md))

### eventname Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                      | Explanation |
| :----------------------------------------- | :---------- |
| `"ECS_LIEFERBEGINN"`                       |             |
| `"START_MALOIDENT"`                        |             |
| `"START_KUENDIGUNG"`                       |             |
| `"START_LIEFERBEGINN"`                     |             |
| `"START_LIEFERENDE"`                       |             |
| `"START_VERSAND_SDAE"`                     |             |
| `"START_ABMELDEANFRAGE"`                   |             |
| `"START_AUFH_ZUK_ZUORDNUNG"`               |             |
| `"START_ENDE_ZUORDNUNG"`                   |             |
| `"START_ABR_NN"`                           |             |
| `"START_ABR_BK"`                           |             |
| `"START_EINRICHTUNG_KONFIG"`               |             |
| `"START_BERECHNUNGSFORMEL"`                |             |
| `"START_WIEDERHERST_LB"`                   |             |
| `"START_EOG"`                              |             |
| `"START_ANFORDERUNG_MESSWERTE"`            |             |
| `"START_BESTELLUNG_ABRECHNUNGSDATEN"`      |             |
| `"START_ERHEBUNG_MESSWERTE"`               |             |
| `"START_BESTELLUNG_SDAE"`                  |             |
| `"START_VERSAND_LIEFERSCHEIN"`             |             |
| `"START_VERSAND_ANTWORT_NNA"`              |             |
| `"START_ANFRAGE_KONFIGURATION"`            |             |
| `"START_BESTELLUNG_KONFIGURATION"`         |             |
| `"START_BESTELLUNG_ANGEBOT_KONFIGURATION"` |             |
| `"START_BESTELLUNG_ZAEHLZEITDEFINITION"`   |             |
| `"START_VERSAND_BESTANDSLISTE"`            |             |
| `"START_VERSAND_ANF_STORNO"`               |             |
| `"START_VERSAND_BEST_BEEND_KONFIG"`        |             |
| `"START_VERSAND_STORNO_MSCONS"`            |             |
| `"START_BEGINN_MSB"`                       |             |
| `"START_ENDE_MSB"`                         |             |
| `"START_KUENDIGUNG_MSB"`                   |             |
| `"START_GESCHAEFTSDATENANFRAGE"`           |             |
| `"START_VERSAND_PREISBLATT_IMS"`           |             |

## ediTyp



`ediTyp`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](zusatzdaten-properties-edityp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/ediTyp")

### ediTyp Type

`string`

## ediEmpfangsDatum



`ediEmpfangsDatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](zusatzdaten-properties-ediempfangsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/ediEmpfangsDatum")

### ediEmpfangsDatum Type

`string`

### ediEmpfangsDatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## ediVersion



`ediVersion`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](zusatzdaten-properties-ediversion.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/ediVersion")

### ediVersion Type

`string`

## marktpartnerRolle

Diese Rollen kann ein Marktteilnehmer einnehmen

`marktpartnerRolle`

*   is optional

*   Type: `string` ([Marktrolle](marktrolle.md))

*   cannot be null

*   defined in: [Untitled schema](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/marktpartnerRolle")

### marktpartnerRolle Type

`string` ([Marktrolle](marktrolle.md))

### marktpartnerRolle Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"NB"`              |             |
| `"LF"`              |             |
| `"MSB"`             |             |
| `"MSBA"`            |             |
| `"GMSB"`            |             |
| `"MDL"`             |             |
| `"DL"`              |             |
| `"BKV"`             |             |
| `"UENB"`            |             |
| `"KUNDE-SELBST-NN"` |             |
| `"MGV"`             |             |
| `"EIV"`             |             |
| `"RB"`              |             |
| `"KUNDE"`           |             |
| `"INTERESSENT"`     |             |
| `"KN"`              |             |
| `"UBA"`             |             |
| `"BIKO"`            |             |
| `"ESA"`             |             |

## contrlReferenz



`contrlReferenz`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](zusatzdaten-properties-contrlreferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/contrlReferenz")

### contrlReferenz Type

`string`

## parentBusinessKey



`parentBusinessKey`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](zusatzdaten-properties-parentbusinesskey.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/parentBusinessKey")

### parentBusinessKey Type

`string`

## targetBusinessKey



`targetBusinessKey`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](zusatzdaten-properties-targetbusinesskey.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/targetBusinessKey")

### targetBusinessKey Type

`string`

## ermaechtigungVorhanden

Rückmeldung der SST Lesen\_Zuordnungsermächtigung mit Information ob Zuordnungsermächtigung vorliegt

`ermaechtigungVorhanden`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Untitled schema](zusatzdaten-properties-ermaechtigungvorhanden.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/cdoc/Zusatzdaten.schema.json#/properties/ermaechtigungVorhanden")

### ermaechtigungVorhanden Type

`boolean`
