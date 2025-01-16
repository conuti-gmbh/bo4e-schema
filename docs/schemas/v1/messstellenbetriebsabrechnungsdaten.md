## Messstellenbetriebsabrechnungsdaten Type

`object` ([Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten.md))

# Messstellenbetriebsabrechnungsdaten Properties

| Property                                                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                         |
| :-------------------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [messstellenbetriebsabrechnung](#messstellenbetriebsabrechnung) | `boolean` | Optional | cannot be null | [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-messstellenbetriebsabrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/messstellenbetriebsabrechnung") |
| [artikelId](#artikelid)                                         | `string`  | Optional | cannot be null | [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-artikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/artikelId")                                         |
| [artikelIdTyp](#artikelidtyp)                                   | `string`  | Optional | cannot be null | [Messstellenbetriebsabrechnungsdaten](artikelidtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArtikelIdTyp.schema.json#/properties/artikelIdTyp")                                                                                                        |
| [anzahl](#anzahl)                                               | `integer` | Optional | cannot be null | [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-anzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/anzahl")                                               |
| [zuschlag](#zuschlag)                                           | `number`  | Optional | cannot be null | [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-zuschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/zuschlag")                                           |
| [abschlag](#abschlag)                                           | `number`  | Optional | cannot be null | [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-abschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/abschlag")                                           |

## messstellenbetriebsabrechnung

messstellenbetriebsabrechnung

`messstellenbetriebsabrechnung`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-messstellenbetriebsabrechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/messstellenbetriebsabrechnung")

### messstellenbetriebsabrechnung Type

`boolean`

## artikelId

artikelId

`artikelId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-artikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/artikelId")

### artikelId Type

`string`

## artikelIdTyp

ArtikelIdTyp

`artikelIdTyp`

*   is optional

*   Type: `string` ([ArtikelIdTyp](artikelidtyp.md))

*   cannot be null

*   defined in: [Messstellenbetriebsabrechnungsdaten](artikelidtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArtikelIdTyp.schema.json#/properties/artikelIdTyp")

### artikelIdTyp Type

`string` ([ArtikelIdTyp](artikelidtyp.md))

### artikelIdTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"ARTIKELID"`        |             |
| `"GRUPPENARTIKELID"` |             |

## anzahl

anzahl

`anzahl`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-anzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/anzahl")

### anzahl Type

`integer`

## zuschlag

zuschlag

`zuschlag`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-zuschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/zuschlag")

### zuschlag Type

`number`

### zuschlag Constraints

**unknown format**: the value of this string must follow the format: `float`

## abschlag

abschlag

`abschlag`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten-properties-abschlag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Messstellenbetriebsabrechnungsdaten.schema.json#/properties/abschlag")

### abschlag Type

`number`

### abschlag Constraints

**unknown format**: the value of this string must follow the format: `float`
