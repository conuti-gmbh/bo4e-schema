## Lastprofil Type

`object` ([Lastprofil](lastprofil.md))

# Lastprofil Properties

| Property                                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :------------------------------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [bezeichnung](#bezeichnung)                             | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/bezeichnung")                             |
| [verfahren](#verfahren)                                 | `string`  | Optional | cannot be null | [Lastprofil](profilverfahren.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profilverfahren.schema.json#/properties/verfahren")                                           |
| [profilart](#profilart)                                 | `string`  | Optional | cannot be null | [Lastprofil](profilart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profilart.schema.json#/properties/profilart")                                                       |
| [profilschar](#profilschar)                             | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-profilschar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/profilschar")                             |
| [einspeisung](#einspeisung)                             | `boolean` | Optional | cannot be null | [Lastprofil](lastprofil-properties-einspeisung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/einspeisung")                             |
| [herausgeber](#herausgeber)                             | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-herausgeber.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/herausgeber")                             |
| [tagesparameter](#tagesparameter)                       | `object`  | Optional | cannot be null | [Lastprofil](tagesparameter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/tagesparameter")                                         |
| [referenzprofilbezeichnung](#referenzprofilbezeichnung) | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-referenzprofilbezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/referenzprofilbezeichnung") |
| [referenzprofil](#referenzprofil)                       | `string`  | Optional | cannot be null | [Lastprofil](lastprofil-properties-referenzprofil.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/referenzprofil")                       |
| [profiltyp](#profiltyp)                                 | `string`  | Optional | cannot be null | [Lastprofil](profiltyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profiltyp.schema.json#/properties/profiltyp")                                                       |
| [normierungsfaktor](#normierungsfaktor)                 | `string`  | Optional | cannot be null | [Lastprofil](normierungsfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Normierungsfaktor.schema.json#/properties/normierungsfaktor")                               |
| [tagesmitteltemperatur](#tagesmitteltemperatur)         | `object`  | Optional | cannot be null | [Lastprofil](tagesmitteltemperatur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/tagesmitteltemperatur")                    |
| [begrenzungskonstante](#begrenzungskonstante)           | `string`  | Optional | cannot be null | [Lastprofil](begrenzungskonstante.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Begrenzungskonstante.schema.json#/properties/begrenzungskonstante")                      |

## bezeichnung

Bezeichnung des Profils

`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`

## verfahren

Profilverfahren

`verfahren`

*   is optional

*   Type: `string` ([Profilverfahren](profilverfahren.md))

*   cannot be null

*   defined in: [Lastprofil](profilverfahren.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profilverfahren.schema.json#/properties/verfahren")

### verfahren Type

`string` ([Profilverfahren](profilverfahren.md))

### verfahren Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"SYNTHETISCH"` |             |
| `"ANALYTISCH"`  |             |

## profilart

Profilart

`profilart`

*   is optional

*   Type: `string` ([Profilart](profilart.md))

*   cannot be null

*   defined in: [Lastprofil](profilart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profilart.schema.json#/properties/profilart")

### profilart Type

`string` ([Profilart](profilart.md))

### profilart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                        | Explanation |
| :------------------------------------------- | :---------- |
| `"ART_STANDARDLASTPROFIL"`                   |             |
| `"ART_TAGESPARAMETERABHAENGIGES_LASTPROFIL"` |             |
| `"ART_LASTPROFIL"`                           |             |

## profilschar

Profilschar des Profils

`profilschar`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-profilschar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/profilschar")

### profilschar Type

`string`

## einspeisung

Kennzeichen Einspeisung

`einspeisung`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-einspeisung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/einspeisung")

### einspeisung Type

`boolean`

## herausgeber

Herausgeber des Lastprofils

`herausgeber`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-herausgeber.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/herausgeber")

### herausgeber Type

`string`

## tagesparameter



`tagesparameter`

*   is optional

*   Type: `object` ([Tagesparameter](tagesparameter.md))

*   cannot be null

*   defined in: [Lastprofil](tagesparameter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesparameter.schema.json#/properties/tagesparameter")

### tagesparameter Type

`object` ([Tagesparameter](tagesparameter.md))

## referenzprofilbezeichnung

Bezeichnung des Referenzprofils

`referenzprofilbezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-referenzprofilbezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/referenzprofilbezeichnung")

### referenzprofilbezeichnung Type

`string`

## referenzprofil

Referenzprofil

`referenzprofil`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Lastprofil](lastprofil-properties-referenzprofil.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Lastprofil.schema.json#/properties/referenzprofil")

### referenzprofil Type

`string`

## profiltyp

Profiltyp

`profiltyp`

*   is optional

*   Type: `string` ([Profiltyp](profiltyp.md))

*   cannot be null

*   defined in: [Lastprofil](profiltyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Profiltyp.schema.json#/properties/profiltyp")

### profiltyp Type

`string` ([Profiltyp](profiltyp.md))

### profiltyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                    | Explanation |
| :----------------------------------------------------------------------- | :---------- |
| `"SLP_SEP"`                                                              |             |
| `"TLP_TEP"`                                                              |             |
| `"TEP"`                                                                  |             |
| `"GEWERBE_ALLGEMEIN"`                                                    |             |
| `"GEWERBE_WERKTAGS_8_18_UHR"`                                            |             |
| `"GEWERBE_MIT_STARKEM_BIS_UEBERWIEGENDEM_VERBRAUCH_IN_DEN_ABENDSTUNDEN"` |             |
| `"GEWERBE_DURCHLAUFEND"`                                                 |             |
| `"GEWERBE_LADEN_FRISEUR"`                                                |             |
| `"GEWERBE_BAECKEREI_MIT_BACKSTUBE"`                                      |             |
| `"GEWERBE_WOCHENENDBETRIEB"`                                             |             |
| `"LANDWIRTSCHAFTSBETRIEBE_ALLGEMEIN"`                                    |             |
| `"LANDWIRTSCHAFTSBETRIEBE_MIT_MILCHWIRTSCHAFT_NEBENERWERBS_TIERZUCHT"`   |             |
| `"LANDWIRTSCHAFT_OHNE_MILCHVIEH"`                                        |             |
| `"HAUSHALT"`                                                             |             |
| `"BANDLAST"`                                                             |             |
| `"UNTERBRECHBARE_VERBRAUCHSEINRICHTUNG"`                                 |             |
| `"HEIZWAERMESPEICHER"`                                                   |             |
| `"STRASSENBELEUCHTUNG"`                                                  |             |
| `"PHOTOVOLTAIK_MARKTLOKATION"`                                           |             |
| `"BLOCKHEIZKRAFTWERK"`                                                   |             |
| `"SONSTIGE_VERBRAUCHENDE_MARKTLOKATION"`                                 |             |
| `"SONSTIGE_ERZEUGENDE_MARKTLOKATION"`                                    |             |
| `"E_MOBILITAET_LADEPUNKT_IM_OEFFENTLICHEN_BEREICH"`                      |             |
| `"E_MOBILITAET_LADEPUNKT_EINES_HAUSHALTS"`                               |             |
| `"E_MOBILITAET_LADEPUNKT_EINES_GEWERBES"`                                |             |

## normierungsfaktor

Normierungsfaktor

`normierungsfaktor`

*   is optional

*   Type: `string` ([Normierungsfaktor](normierungsfaktor.md))

*   cannot be null

*   defined in: [Lastprofil](normierungsfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Normierungsfaktor.schema.json#/properties/normierungsfaktor")

### normierungsfaktor Type

`string` ([Normierungsfaktor](normierungsfaktor.md))

### normierungsfaktor Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                 | Explanation |
| :------------------------------------ | :---------- |
| `"NORMIERUNGSFAKTOR_1_000_000_KWH_A"` |             |
| `"NORMIERUNGSFAKTOR_300_KWH_K"`       |             |
| `"NORMIERUNGSFAKTOR_1_000_000_KW"`    |             |

## tagesmitteltemperatur



`tagesmitteltemperatur`

*   is optional

*   Type: `object` ([Tagesmitteltemperatur](tagesmitteltemperatur.md))

*   cannot be null

*   defined in: [Lastprofil](tagesmitteltemperatur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Tagesmitteltemperatur.schema.json#/properties/tagesmitteltemperatur")

### tagesmitteltemperatur Type

`object` ([Tagesmitteltemperatur](tagesmitteltemperatur.md))

## begrenzungskonstante

Begrenzungskonstante

`begrenzungskonstante`

*   is optional

*   Type: `string` ([Begrenzungskonstante](begrenzungskonstante.md))

*   cannot be null

*   defined in: [Lastprofil](begrenzungskonstante.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Begrenzungskonstante.schema.json#/properties/begrenzungskonstante")

### begrenzungskonstante Type

`string` ([Begrenzungskonstante](begrenzungskonstante.md))

### begrenzungskonstante Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"BEGRENZUNGSKONSTANTE_0"` |             |
| `"BEGRENZUNGSKONSTANTE_1"` |             |
