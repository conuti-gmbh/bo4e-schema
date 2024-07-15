## Netznutzungsabrechnungsdaten Type

`object` ([Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten.md))

# Netznutzungsabrechnungsdaten Properties

| Property                                                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                    |
| :-------------------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [artikelId](#artikelid)                                         | `string`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-artikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/artikelId")                         |
| [artikelIdTyp](#artikelidtyp)                                   | `string`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](artikelidtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArtikelIdTyp.schema.json#/properties/artikelIdTyp")                                                                          |
| [anzahl](#anzahl)                                               | `integer` | Optional | cannot be null | [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-anzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/anzahl")                               |
| [gemeinderabatt](#gemeinderabatt)                               | `number`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/gemeinderabatt")               |
| [zuschlag](#zuschlag)                                           | `number`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-zuschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/zuschlag")                           |
| [abschlag](#abschlag)                                           | `number`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-abschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/abschlag")                           |
| [singulaereBetriebsmittel](#singulaerebetriebsmittel)           | `object`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/singulaereBetriebsmittel")                                                                             |
| [preisSingulaereBetriebsmittel](#preissingulaerebetriebsmittel) | `object`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](preis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/preisSingulaereBetriebsmittel")                                                                        |
| [abrechnungBlindarbeit](#abrechnungblindarbeit)                 | `boolean` | Optional | cannot be null | [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-abrechnungblindarbeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/abrechnungBlindarbeit") |
| [zahlerBlindarbeit](#zahlerblindarbeit)                         | `string`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](zahlerblindarbeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ZahlerBlindarbeit.schema.json#/properties/zahlerBlindarbeit")                                                           |
| [zahlerBlindarbeitLf](#zahlerblindarbeitlf)                     | `boolean` | Optional | cannot be null | [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-zahlerblindarbeitlf.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/zahlerBlindarbeitLf")     |
| [differenzDaten](#differenzdaten)                               | `boolean` | Optional | cannot be null | [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-differenzdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/differenzDaten")               |
| [zaehlzeiten](#zaehlzeiten)                                     | `object`  | Optional | cannot be null | [Netznutzungsabrechnungsdaten](zaehlzeitregister.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeitregister.schema.json#/properties/zaehlzeiten")                                                                  |

## artikelId



`artikelId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-artikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/artikelId")

### artikelId Type

`string`

## artikelIdTyp



`artikelIdTyp`

*   is optional

*   Type: `string` ([ArtikelIdTyp](artikelidtyp.md))

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](artikelidtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArtikelIdTyp.schema.json#/properties/artikelIdTyp")

### artikelIdTyp Type

`string` ([ArtikelIdTyp](artikelidtyp.md))

### artikelIdTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"ARTIKELID"`        |             |
| `"GRUPPENARTIKELID"` |             |

## anzahl



`anzahl`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-anzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/anzahl")

### anzahl Type

`integer`

## gemeinderabatt



`gemeinderabatt`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/gemeinderabatt")

### gemeinderabatt Type

`number`

### gemeinderabatt Constraints

**unknown format**: the value of this string must follow the format: `float`

## zuschlag



`zuschlag`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-zuschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/zuschlag")

### zuschlag Type

`number`

### zuschlag Constraints

**unknown format**: the value of this string must follow the format: `float`

## abschlag



`abschlag`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-abschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/abschlag")

### abschlag Type

`number`

### abschlag Constraints

**unknown format**: the value of this string must follow the format: `float`

## singulaereBetriebsmittel



`singulaereBetriebsmittel`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/singulaereBetriebsmittel")

### singulaereBetriebsmittel Type

`object` ([Menge](menge.md))

## preisSingulaereBetriebsmittel



`preisSingulaereBetriebsmittel`

*   is optional

*   Type: `object` ([Preis](preis.md))

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](preis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preis.schema.json#/properties/preisSingulaereBetriebsmittel")

### preisSingulaereBetriebsmittel Type

`object` ([Preis](preis.md))

## abrechnungBlindarbeit



`abrechnungBlindarbeit`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-abrechnungblindarbeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/abrechnungBlindarbeit")

### abrechnungBlindarbeit Type

`boolean`

## zahlerBlindarbeit



`zahlerBlindarbeit`

*   is optional

*   Type: `string` ([ZahlerBlindarbeit](zahlerblindarbeit.md))

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](zahlerblindarbeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ZahlerBlindarbeit.schema.json#/properties/zahlerBlindarbeit")

### zahlerBlindarbeit Type

`string` ([ZahlerBlindarbeit](zahlerblindarbeit.md))

### zahlerBlindarbeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"ANSCHLUSSNUTZER"`  |             |
| `"LIEFERANT"`        |             |
| `"NICHT_FESTGELEGT"` |             |

## zahlerBlindarbeitLf



`zahlerBlindarbeitLf`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-zahlerblindarbeitlf.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/zahlerBlindarbeitLf")

### zahlerBlindarbeitLf Type

`boolean`

## differenzDaten



`differenzDaten`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten-properties-differenzdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Netznutzungsabrechnungsdaten.schema.json#/properties/differenzDaten")

### differenzDaten Type

`boolean`

## zaehlzeiten



`zaehlzeiten`

*   is optional

*   Type: `object` ([Zaehlzeitregister](zaehlzeitregister.md))

*   cannot be null

*   defined in: [Netznutzungsabrechnungsdaten](zaehlzeitregister.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeitregister.schema.json#/properties/zaehlzeiten")

### zaehlzeiten Type

`object` ([Zaehlzeitregister](zaehlzeitregister.md))
