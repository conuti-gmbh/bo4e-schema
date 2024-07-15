## Zaehlwerk Type

`object` ([Zaehlwerk](zaehlwerk.md))

# Zaehlwerk Properties

| Property                                                                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                          |
| :------------------------------------------------------------------------ | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [zaehlwerkId](#zaehlwerkid)                                               | `string`  | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-zaehlwerkid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/zaehlwerkId")                                                    |
| [bezeichnung](#bezeichnung)                                               | `string`  | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/bezeichnung")                                                    |
| [richtung](#richtung)                                                     | `string`  | Optional | cannot be null | [Zaehlwerk](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/richtung")                                                                 |
| [obisKennzahl](#obiskennzahl)                                             | `string`  | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/obisKennzahl")                                                  |
| [wandlerfaktor](#wandlerfaktor)                                           | `number`  | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-wandlerfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/wandlerfaktor")                                                |
| [einheit](#einheit)                                                       | `string`  | Optional | cannot be null | [Zaehlwerk](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/einheit")                                                                      |
| [schwachlastfaehig](#schwachlastfaehig)                                   | `string`  | Optional | cannot be null | [Zaehlwerk](schwachlastfaehig.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Schwachlastfaehig.schema.json#/properties/schwachlastfaehig")                                                    |
| [verbrauchsart](#verbrauchsart)                                           | `string`  | Optional | cannot be null | [Zaehlwerk](verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsart.schema.json#/properties/verbrauchsart")                                                                |
| [unterbrechbarkeit](#unterbrechbarkeit)                                   | `string`  | Optional | cannot be null | [Zaehlwerk](unterbrechbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Unterbrechbarkeit.schema.json#/properties/unterbrechbarkeit")                                                    |
| [waermenutzung](#waermenutzung)                                           | `string`  | Optional | cannot be null | [Zaehlwerk](waermenutzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waermenutzung.schema.json#/properties/waermenutzung")                                                                |
| [konzessionsabgabe](#konzessionsabgabe)                                   | `object`  | Optional | cannot be null | [Zaehlwerk](konzessionsabgabe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Konzessionsabgabe.schema.json#/properties/konzessionsabgabe")                                                     |
| [steuerbefreit](#steuerbefreit)                                           | `boolean` | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-steuerbefreit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/steuerbefreit")                                                |
| [vorkommastelle](#vorkommastelle)                                         | `integer` | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-vorkommastelle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/vorkommastelle")                                              |
| [nachkommastelle](#nachkommastelle)                                       | `integer` | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-nachkommastelle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/nachkommastelle")                                            |
| [abrechnungsrelevant](#abrechnungsrelevant)                               | `boolean` | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-abrechnungsrelevant.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/abrechnungsrelevant")                                    |
| [anzahlAblesungen](#anzahlablesungen)                                     | `integer` | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-anzahlablesungen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/anzahlAblesungen")                                          |
| [zaehlzeiten](#zaehlzeiten)                                               | `object`  | Optional | cannot be null | [Zaehlwerk](zaehlzeitregister.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeitregister.schema.json#/properties/zaehlzeiten")                                                           |
| [konfiguration](#konfiguration)                                           | `string`  | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-konfiguration.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/konfiguration")                                                |
| [messprodukt](#messprodukt)                                               | `string`  | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-messprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/messprodukt")                                                    |
| [wertegranularitaet](#wertegranularitaet)                                 | `string`  | Optional | cannot be null | [Zaehlwerk](wertegranularitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Wertegranularitaet.schema.json#/properties/wertegranularitaet")                                                 |
| [notwendigkeitZweiteMessung](#notwendigkeitzweitemessung)                 | `string`  | Optional | cannot be null | [Zaehlwerk](notwendigkeitzweitemessung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/NotwendigkeitZweiteMessung.schema.json#/properties/notwendigkeitZweiteMessung")                         |
| [werteuebermittlungVerwendungszweck](#werteuebermittlungverwendungszweck) | `string`  | Optional | cannot be null | [Zaehlwerk](werteuebermittlungverwendungszweck.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WerteuebermittlungVerwendungszweck.schema.json#/properties/werteuebermittlungVerwendungszweck") |
| [artEMobilitaet](#artemobilitaet)                                         | `string`  | Optional | cannot be null | [Zaehlwerk](artemobilitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArtEmobilitaet.schema.json#/properties/artEMobilitaet")                                                             |
| [konfigurationsprodukt](#konfigurationsprodukt)                           | `string`  | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/konfigurationsprodukt")                                |
| [keinKonfigurationsprodukt](#keinkonfigurationsprodukt)                   | `boolean` | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-keinkonfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/keinKonfigurationsprodukt")                        |
| [leistungskurvendefinition](#leistungskurvendefinition)                   | `string`  | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-leistungskurvendefinition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/leistungskurvendefinition")                        |
| [verwendungszwecke](#verwendungszwecke)                                   | `array`   | Optional | cannot be null | [Zaehlwerk](zaehlwerk-properties-verwendungszwecke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/verwendungszwecke")                                        |

## zaehlwerkId



`zaehlwerkId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-zaehlwerkid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/zaehlwerkId")

### zaehlwerkId Type

`string`

## bezeichnung



`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`

## richtung



`richtung`

*   is optional

*   Type: `string` ([Energierichtung](energierichtung.md))

*   cannot be null

*   defined in: [Zaehlwerk](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/richtung")

### richtung Type

`string` ([Energierichtung](energierichtung.md))

### richtung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"AUSSP"` |             |
| `"EINSP"` |             |

## obisKennzahl



`obisKennzahl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/obisKennzahl")

### obisKennzahl Type

`string`

## wandlerfaktor



`wandlerfaktor`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-wandlerfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/wandlerfaktor")

### wandlerfaktor Type

`number`

### wandlerfaktor Constraints

**unknown format**: the value of this string must follow the format: `float`

## einheit



`einheit`

*   is optional

*   Type: `string` ([Mengeneinheit](mengeneinheit.md))

*   cannot be null

*   defined in: [Zaehlwerk](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/einheit")

### einheit Type

`string` ([Mengeneinheit](mengeneinheit.md))

### einheit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"W"`          |             |
| `"WH"`         |             |
| `"KW"`         |             |
| `"KWH"`        |             |
| `"KVARH"`      |             |
| `"MW"`         |             |
| `"MWH"`        |             |
| `"STUECK"`     |             |
| `"KUBIKMETER"` |             |
| `"STUNDE"`     |             |
| `"TAG"`        |             |
| `"MONAT"`      |             |
| `"JAHR"`       |             |
| `"PROZENT"`    |             |
| `"ANZAHL"`     |             |
| `"VAR"`        |             |
| `"KVAR"`       |             |
| `"VARH"`       |             |
| `"KWHK"`       |             |

## schwachlastfaehig



`schwachlastfaehig`

*   is optional

*   Type: `string` ([Schwachlastfaehig](schwachlastfaehig.md))

*   cannot be null

*   defined in: [Zaehlwerk](schwachlastfaehig.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Schwachlastfaehig.schema.json#/properties/schwachlastfaehig")

### schwachlastfaehig Type

`string` ([Schwachlastfaehig](schwachlastfaehig.md))

### schwachlastfaehig Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                       | Explanation |
| :-------------------------- | :---------- |
| `"SCHWACHLASTFAEHIG"`       |             |
| `"NICHT_SCHWACHLASTFAEHIG"` |             |

## verbrauchsart



`verbrauchsart`

*   is optional

*   Type: `string` ([Verbrauchsart](verbrauchsart.md))

*   cannot be null

*   defined in: [Zaehlwerk](verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsart.schema.json#/properties/verbrauchsart")

### verbrauchsart Type

`string` ([Verbrauchsart](verbrauchsart.md))

### verbrauchsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"KL"`   |             |
| `"W"`    |             |
| `"EMOB"` |             |
| `"SB"`   |             |
| `"SW"`   |             |
| `"WK"`   |             |

## unterbrechbarkeit



`unterbrechbarkeit`

*   is optional

*   Type: `string` ([Unterbrechbarkeit](unterbrechbarkeit.md))

*   cannot be null

*   defined in: [Zaehlwerk](unterbrechbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Unterbrechbarkeit.schema.json#/properties/unterbrechbarkeit")

### unterbrechbarkeit Type

`string` ([Unterbrechbarkeit](unterbrechbarkeit.md))

### unterbrechbarkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"UV"`  |             |
| `"NUV"` |             |

## waermenutzung



`waermenutzung`

*   is optional

*   Type: `string` ([Waermenutzung](waermenutzung.md))

*   cannot be null

*   defined in: [Zaehlwerk](waermenutzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waermenutzung.schema.json#/properties/waermenutzung")

### waermenutzung Type

`string` ([Waermenutzung](waermenutzung.md))

### waermenutzung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                         | Explanation |
| :---------------------------- | :---------- |
| `"SPEICHERHEIZUNG"`           |             |
| `"WAERMEPUMPE"`               |             |
| `"DIREKTHEIZUNG"`             |             |
| `"WAERMEPUMPE_WAERME_KAELTE"` |             |
| `"WAERMEPUMPE_KAELTE"`        |             |
| `"WAERMEPUMPE_WAERME"`        |             |

## konzessionsabgabe



`konzessionsabgabe`

*   is optional

*   Type: `object` ([Konzessionsabgabe](konzessionsabgabe.md))

*   cannot be null

*   defined in: [Zaehlwerk](konzessionsabgabe.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Konzessionsabgabe.schema.json#/properties/konzessionsabgabe")

### konzessionsabgabe Type

`object` ([Konzessionsabgabe](konzessionsabgabe.md))

## steuerbefreit



`steuerbefreit`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-steuerbefreit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/steuerbefreit")

### steuerbefreit Type

`boolean`

## vorkommastelle



`vorkommastelle`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-vorkommastelle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/vorkommastelle")

### vorkommastelle Type

`integer`

## nachkommastelle



`nachkommastelle`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-nachkommastelle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/nachkommastelle")

### nachkommastelle Type

`integer`

## abrechnungsrelevant



`abrechnungsrelevant`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-abrechnungsrelevant.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/abrechnungsrelevant")

### abrechnungsrelevant Type

`boolean`

## anzahlAblesungen



`anzahlAblesungen`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-anzahlablesungen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/anzahlAblesungen")

### anzahlAblesungen Type

`integer`

## zaehlzeiten



`zaehlzeiten`

*   is optional

*   Type: `object` ([Zaehlzeitregister](zaehlzeitregister.md))

*   cannot be null

*   defined in: [Zaehlwerk](zaehlzeitregister.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeitregister.schema.json#/properties/zaehlzeiten")

### zaehlzeiten Type

`object` ([Zaehlzeitregister](zaehlzeitregister.md))

## konfiguration



`konfiguration`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-konfiguration.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/konfiguration")

### konfiguration Type

`string`

## messprodukt



`messprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-messprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/messprodukt")

### messprodukt Type

`string`

## wertegranularitaet



`wertegranularitaet`

*   is optional

*   Type: `string` ([Wertegranularitaet](wertegranularitaet.md))

*   cannot be null

*   defined in: [Zaehlwerk](wertegranularitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Wertegranularitaet.schema.json#/properties/wertegranularitaet")

### wertegranularitaet Type

`string` ([Wertegranularitaet](wertegranularitaet.md))

### wertegranularitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"JAEHRLICH"`     |             |
| `"HALBJAEHRLICH"` |             |
| `"QUARTALSWEISE"` |             |
| `"MONATLICH"`     |             |

## notwendigkeitZweiteMessung



`notwendigkeitZweiteMessung`

*   is optional

*   Type: `string` ([NotwendigkeitZweiteMessung](notwendigkeitzweitemessung.md))

*   cannot be null

*   defined in: [Zaehlwerk](notwendigkeitzweitemessung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/NotwendigkeitZweiteMessung.schema.json#/properties/notwendigkeitZweiteMessung")

### notwendigkeitZweiteMessung Type

`string` ([NotwendigkeitZweiteMessung](notwendigkeitzweitemessung.md))

### notwendigkeitZweiteMessung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"VORHANDEN"`       |             |
| `"NICHT_VORHANDEN"` |             |

## werteuebermittlungVerwendungszweck



`werteuebermittlungVerwendungszweck`

*   is optional

*   Type: `string` ([WerteuebermittlungVerwendungszweck](werteuebermittlungverwendungszweck.md))

*   cannot be null

*   defined in: [Zaehlwerk](werteuebermittlungverwendungszweck.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/WerteuebermittlungVerwendungszweck.schema.json#/properties/werteuebermittlungVerwendungszweck")

### werteuebermittlungVerwendungszweck Type

`string` ([WerteuebermittlungVerwendungszweck](werteuebermittlungverwendungszweck.md))

### werteuebermittlungVerwendungszweck Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"VORHANDEN"`       |             |
| `"NICHT_VORHANDEN"` |             |

## artEMobilitaet



`artEMobilitaet`

*   is optional

*   Type: `string` ([ArtEmobilitaet](artemobilitaet.md))

*   cannot be null

*   defined in: [Zaehlwerk](artemobilitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArtEmobilitaet.schema.json#/properties/artEMobilitaet")

### artEMobilitaet Type

`string` ([ArtEmobilitaet](artemobilitaet.md))

### artEMobilitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value  | Explanation |
| :----- | :---------- |
| `"WB"` |             |
| `"LS"` |             |
| `"LP"` |             |

## konfigurationsprodukt



`konfigurationsprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/konfigurationsprodukt")

### konfigurationsprodukt Type

`string`

## keinKonfigurationsprodukt



`keinKonfigurationsprodukt`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-keinkonfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/keinKonfigurationsprodukt")

### keinKonfigurationsprodukt Type

`boolean`

## leistungskurvendefinition



`leistungskurvendefinition`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-leistungskurvendefinition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/leistungskurvendefinition")

### leistungskurvendefinition Type

`string`

## verwendungszwecke



`verwendungszwecke`

*   is optional

*   Type: `object[]` ([Verwendungszweck](verwendungszweck.md))

*   cannot be null

*   defined in: [Zaehlwerk](zaehlwerk-properties-verwendungszwecke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlwerk.schema.json#/properties/verwendungszwecke")

### verwendungszwecke Type

`object[]` ([Verwendungszweck](verwendungszweck.md))
