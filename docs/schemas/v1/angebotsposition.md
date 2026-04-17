## Angebotsposition Type

`object` ([Angebotsposition](angebotsposition.md))

# Angebotsposition Properties

| Property                                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :------------------------------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [positionsbezeichung](#positionsbezeichung)             | `string`  | Optional | cannot be null | [Angebotsposition](angebotsposition-properties-positionsbezeichung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/positionsbezeichung")             |
| [positionsmenge](#positionsmenge)                       | `object`  | Optional | cannot be null | [Angebotsposition](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/positionsmenge")                                                                       |
| [positionspreis](#positionspreis)                       | `array`   | Optional | can be null    | [Angebotsposition](angebotsposition-properties-positionspreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/positionspreis")                       |
| [positionsbetrag](#positionsbetrag)                     | `object`  | Optional | cannot be null | [Angebotsposition](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/positionsbetrag")                                                                    |
| [preisschluesselstamm](#preisschluesselstamm)           | `string`  | Optional | cannot be null | [Angebotsposition](angebotsposition-properties-preisschluesselstamm.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/preisschluesselstamm")           |
| [artikelnummer](#artikelnummer)                         | `string`  | Optional | cannot be null | [Angebotsposition](bdewartikelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BDEWArtikelnummer.schema.json#/properties/artikelnummer")                                               |
| [artikelId](#artikelid)                                 | `array`   | Optional | can be null    | [Angebotsposition](angebotsposition-properties-artikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/artikelId")                                 |
| [anbietbar](#anbietbar)                                 | `boolean` | Optional | cannot be null | [Angebotsposition](angebotsposition-properties-anbietbar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/anbietbar")                                 |
| [freitext](#freitext)                                   | `string`  | Optional | cannot be null | [Angebotsposition](angebotsposition-properties-freitext.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/freitext")                                   |
| [verweisKatalognummer](#verweiskatalognummer)           | `object`  | Optional | cannot be null | [Angebotsposition](katalogverweis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Katalogverweis.schema.json#/properties/verweisKatalognummer")                                               |
| [beteiligterMarktpartner](#beteiligtermarktpartner)     | `object`  | Optional | cannot be null | [Angebotsposition](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/beteiligterMarktpartner")                                           |
| [referenzMarktlokationsIds](#referenzmarktlokationsids) | `array`   | Optional | can be null    | [Angebotsposition](angebotsposition-properties-referenzmarktlokationsids.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/referenzMarktlokationsIds") |

## positionsbezeichung

Bezeichnung der Position

`positionsbezeichung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Angebotsposition](angebotsposition-properties-positionsbezeichung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/positionsbezeichung")

### positionsbezeichung Type

`string`

## positionsmenge

Menge der Position

`positionsmenge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Angebotsposition](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/positionsmenge")

### positionsmenge Type

`object` ([Menge](menge.md))

## positionspreis

Preisangabe zur Position

`positionspreis`

*   is optional

*   Type: `object[]` ([Preis](preis.md))

*   can be null

*   defined in: [Angebotsposition](angebotsposition-properties-positionspreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/positionspreis")

### positionspreis Type

`object[]` ([Preis](preis.md))

## positionsbetrag

Betrag der Postition

`positionsbetrag`

*   is optional

*   Type: `object` ([Betrag](betrag.md))

*   cannot be null

*   defined in: [Angebotsposition](betrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Betrag.schema.json#/properties/positionsbetrag")

### positionsbetrag Type

`object` ([Betrag](betrag.md))

## preisschluesselstamm

Preisschlüsselstamm

`preisschluesselstamm`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Angebotsposition](angebotsposition-properties-preisschluesselstamm.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/preisschluesselstamm")

### preisschluesselstamm Type

`string`

## artikelnummer

BDEW Artikelnummer

`artikelnummer`

*   is optional

*   Type: `string` ([BDEWArtikelnummer](bdewartikelnummer.md))

*   cannot be null

*   defined in: [Angebotsposition](bdewartikelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BDEWArtikelnummer.schema.json#/properties/artikelnummer")

### artikelnummer Type

`string` ([BDEWArtikelnummer](bdewartikelnummer.md))

### artikelnummer Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                          | Explanation |
| :--------------------------------------------- | :---------- |
| `"LEISTUNG"`                                   |             |
| `"LEISTUNG_PAUSCHAL"`                          |             |
| `"GRUNDPREIS"`                                 |             |
| `"REGELENERGIE_ARBEIT"`                        |             |
| `"REGELENERGIE_LEISTUNG"`                      |             |
| `"NOTSTROMLIEFERUNG_ARBEIT"`                   |             |
| `"NOTSTROMLIEFERUNG_LEISTUNG"`                 |             |
| `"RESERVENETZKAPAZITAET"`                      |             |
| `"RESERVELEISTUNG"`                            |             |
| `"ZUSAETZLICHE_ABLESUNG"`                      |             |
| `"PRUEFGEBUEHREN_AUSSERPLANMAESSIG"`           |             |
| `"WIRKARBEIT"`                                 |             |
| `"SINGULAER_GENUTZTE_BETRIEBSMITTEL"`          |             |
| `"ABGABE_KWKG"`                                |             |
| `"ABSCHLAG"`                                   |             |
| `"KONZESSIONSABGABE"`                          |             |
| `"ENTGELT_FERNAUSLESUNG"`                      |             |
| `"UNTERMESSUNG"`                               |             |
| `"BLINDMEHRARBEIT"`                            |             |
| `"ENTGELT_ABRECHNUNG"`                         |             |
| `"SPERRKOSTEN"`                                |             |
| `"ENTSPERRKOSTEN"`                             |             |
| `"MAHNKOSTEN"`                                 |             |
| `"MEHR_MINDERMENGEN"`                          |             |
| `"INKASSOKOSTEN"`                              |             |
| `"BLINDMEHRLEISTUNG"`                          |             |
| `"ENTGELT_MESSUNG_ABLESUNG"`                   |             |
| `"ENTGELT_EINBAU_BETRIEB_WARTUNG_MESSTECHNIK"` |             |
| `"AUSGLEICHSENERGIE"`                          |             |
| `"AUSGLEICHSENERGIE_UNTERDECKUNG"`             |             |
| `"ZAEHLEINRICHTUNG"`                           |             |
| `"WANDLER_MENGENUMWERTER"`                     |             |
| `"KOMMUNIKATIONSEINRICHTUNG"`                  |             |
| `"TECHNISCHE_STEUEREINRICHTUNG"`               |             |
| `"PARAGRAF_19_STROM_NEV_UMLAGE"`               |             |
| `"BEFESTIGUNGSEINRICHTUNG"`                    |             |
| `"OFFSHORE_HAFTUNGSUMLAGE"`                    |             |
| `"FIXE_ARBEITSENTGELTKOMPONENTE"`              |             |
| `"FIXE_LEISTUNGSENTGELTKOMPONENTE"`            |             |
| `"UMLAGE_ABSCHALTBARE_LASTEN"`                 |             |
| `"MEHRMENGE"`                                  |             |
| `"MINDERMENGE"`                                |             |
| `"ENERGIESTEUER"`                              |             |
| `"SMARTMETER_GATEWAY"`                         |             |
| `"STEUERBOX"`                                  |             |
| `"MSB_INKL_MESSUNG"`                           |             |
| `"ZUSATZDIENSTLEISTUNG_PARAGRAPH_35_2_1_MSBG"` |             |
| `"ZUSATZDIENSTLEISTUNG_PARAGRAPH_35_2_2_MSBG"` |             |
| `"ZUSATZDIENSTLEISTUNG_PARAGRAPH_35_2_3_MSBG"` |             |
| `"ZUSATZDIENSTLEISTUNG_PARAGRAPH_35_2_4_MSBG"` |             |
| `"ZUSATZDIENSTLEISTUNG_PARAGRAPH_35_2_5_MSBG"` |             |
| `"ZUSATZDIENSTLEISTUNG_PARAGRAPH_35_3_MSBG"`   |             |
| `"ENTGELT_KAPAZITAETEN"`                       |             |

## artikelId

ArtikelId gem. BDEW

`artikelId`

*   is optional

*   Type: `string[]`

*   can be null

*   defined in: [Angebotsposition](angebotsposition-properties-artikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/artikelId")

### artikelId Type

`string[]`

## anbietbar



`anbietbar`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Angebotsposition](angebotsposition-properties-anbietbar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/anbietbar")

### anbietbar Type

`boolean`

## freitext

Zusätzliche Informationen (für allgemeine Hinweise)

`freitext`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Angebotsposition](angebotsposition-properties-freitext.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/freitext")

### freitext Type

`string`

## verweisKatalognummer

APF Verweis auf Katalognummer

`verweisKatalognummer`

*   is optional

*   Type: `object` ([Katalogverweis](katalogverweis.md))

*   cannot be null

*   defined in: [Angebotsposition](katalogverweis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Katalogverweis.schema.json#/properties/verweisKatalognummer")

### verweisKatalognummer Type

`object` ([Katalogverweis](katalogverweis.md))

## beteiligterMarktpartner

Beteiligter Marktpartner

`beteiligterMarktpartner`

*   is optional

*   Type: `object` ([Marktteilnehmer](marktteilnehmer.md))

*   cannot be null

*   defined in: [Angebotsposition](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/beteiligterMarktpartner")

### beteiligterMarktpartner Type

`object` ([Marktteilnehmer](marktteilnehmer.md))

## referenzMarktlokationsIds

Referenz auf ID weiterer Marktlokationen

`referenzMarktlokationsIds`

*   is optional

*   Type: `string[]`

*   can be null

*   defined in: [Angebotsposition](angebotsposition-properties-referenzmarktlokationsids.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Angebotsposition.schema.json#/properties/referenzMarktlokationsIds")

### referenzMarktlokationsIds Type

`string[]`
