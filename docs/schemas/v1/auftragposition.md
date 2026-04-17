## AuftragPosition Type

`object` ([AuftragPosition](auftragposition.md))

# AuftragPosition Properties

| Property                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                               |
| :-------------------------------------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [positionsnummer](#positionsnummer)                 | `integer` | Optional | cannot be null | [AuftragPosition](auftragposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/positionsnummer")               |
| [positionsnummerAngebot](#positionsnummerangebot)   | `string`  | Optional | cannot be null | [AuftragPosition](auftragposition-properties-positionsnummerangebot.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/positionsnummerAngebot") |
| [energieerfassung](#energieerfassung)               | `string`  | Optional | cannot be null | [AuftragPosition](energieerfassung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energieerfassung.schema.json#/properties/energieerfassung")                                      |
| [artikelnummer](#artikelnummer)                     | `string`  | Optional | cannot be null | [AuftragPosition](bdewartikelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BDEWArtikelnummer.schema.json#/properties/artikelnummer")                                       |
| [positionsbetrag](#positionsbetrag)                 | `string`  | Optional | cannot be null | [AuftragPosition](auftragposition-properties-positionsbetrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/positionsbetrag")               |
| [startdatum](#startdatum)                           | `string`  | Optional | cannot be null | [AuftragPosition](auftragposition-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/startdatum")                         |
| [enddatum](#enddatum)                               | `string`  | Optional | cannot be null | [AuftragPosition](auftragposition-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/enddatum")                             |
| [istBestand](#istbestand)                           | `string`  | Optional | cannot be null | [AuftragPosition](auftragposition-properties-istbestand.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/istBestand")                         |
| [obiskennzahl](#obiskennzahl)                       | `string`  | Optional | cannot be null | [AuftragPosition](auftragposition-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/obiskennzahl")                     |
| [anfragegrund](#anfragegrund)                       | `string`  | Optional | cannot be null | [AuftragPosition](anfragegrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Anfragegrund.schema.json#/properties/anfragegrund")                                                  |
| [allgemeineInformationen](#allgemeineinformationen) | `object`  | Optional | cannot be null | [AuftragPosition](allgemeineinformationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AllgemeineInformationen.schema.json#/properties/allgemeineInformationen")                  |
| [infoAbweichung](#infoabweichung)                   | `object`  | Optional | cannot be null | [AuftragPosition](infoabweichung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/InfoAbweichung.schema.json#/properties/infoAbweichung")                                             |
| [definitionsTyp](#definitionstyp)                   | `string`  | Optional | cannot be null | [AuftragPosition](definitionstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DefinitionsTyp.schema.json#/properties/definitionsTyp")                                            |
| [lokationsId](#lokationsid)                         | `string`  | Optional | cannot be null | [AuftragPosition](auftragposition-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/lokationsId")                       |
| [zaehlwerk](#zaehlwerk)                             | `integer` | Optional | cannot be null | [AuftragPosition](auftragposition-properties-zaehlwerk.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/zaehlwerk")                           |

## positionsnummer

Positionsnummer

`positionsnummer`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/positionsnummer")

### positionsnummer Type

`integer`

## positionsnummerAngebot

laufende Positionsnummer des Angebot

`positionsnummerAngebot`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-positionsnummerangebot.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/positionsnummerAngebot")

### positionsnummerAngebot Type

`string`

## energieerfassung

Energieerfassung

`energieerfassung`

*   is optional

*   Type: `string` ([Energieerfassung](energieerfassung.md))

*   cannot be null

*   defined in: [AuftragPosition](energieerfassung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energieerfassung.schema.json#/properties/energieerfassung")

### energieerfassung Type

`string` ([Energieerfassung](energieerfassung.md))

### energieerfassung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"SEPARAT_ERFASSEN"`       |             |
| `"NICHT_SEPARAT_ERFASSEN"` |             |

## artikelnummer

BDEW Artikelnummer

`artikelnummer`

*   is optional

*   Type: `string` ([BDEWArtikelnummer](bdewartikelnummer.md))

*   cannot be null

*   defined in: [AuftragPosition](bdewartikelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BDEWArtikelnummer.schema.json#/properties/artikelnummer")

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

## positionsbetrag

Betrag der Position

`positionsbetrag`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-positionsbetrag.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/positionsbetrag")

### positionsbetrag Type

`string`

## startdatum

startdatum

`startdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/startdatum")

### startdatum Type

`string`

### startdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## enddatum

enddatum

`enddatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/enddatum")

### enddatum Type

`string`

### enddatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## istBestand

istBestand

`istBestand`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-istbestand.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/istBestand")

### istBestand Type

`string`

## obiskennzahl

Obis-Kennzahl

`obiskennzahl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-obiskennzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/obiskennzahl")

### obiskennzahl Type

`string`

## anfragegrund

Anfragegrund

`anfragegrund`

*   is optional

*   Type: `string` ([Anfragegrund](anfragegrund.md))

*   cannot be null

*   defined in: [AuftragPosition](anfragegrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Anfragegrund.schema.json#/properties/anfragegrund")

### anfragegrund Type

`string` ([Anfragegrund](anfragegrund.md))

### anfragegrund Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                             | Explanation |
| :-------------------------------- | :---------- |
| `"ABGRENZUNG_VON_ENERGIEMENGEN"`  |             |
| `"ABGRENZUNG"`                    |             |
| `"WECHSELEREIGNIS"`               |             |
| `"ZWISCHENABLESUNG"`              |             |
| `"DIREKTER_VERTRAG_MSB_AN"`       |             |
| `"DIREKTER_VERTRAG_MSB_ANN"`      |             |
| `"AENDERUNG_IM_LOKATIONSBUENDEL"` |             |
| `"NEUKONFIGURATION"`              |             |
| `"KONFIGURATION_UNVERAENDERT"`    |             |

## allgemeineInformationen



`allgemeineInformationen`

*   is optional

*   Type: `object` ([AllgemeineInformationen](allgemeineinformationen.md))

*   cannot be null

*   defined in: [AuftragPosition](allgemeineinformationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AllgemeineInformationen.schema.json#/properties/allgemeineInformationen")

### allgemeineInformationen Type

`object` ([AllgemeineInformationen](allgemeineinformationen.md))

## infoAbweichung



`infoAbweichung`

*   is optional

*   Type: `object` ([InfoAbweichung](infoabweichung.md))

*   cannot be null

*   defined in: [AuftragPosition](infoabweichung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/InfoAbweichung.schema.json#/properties/infoAbweichung")

### infoAbweichung Type

`object` ([InfoAbweichung](infoabweichung.md))

## definitionsTyp

DefinitionsTyp

`definitionsTyp`

*   is optional

*   Type: `string` ([DefinitionsTyp](definitionstyp.md))

*   cannot be null

*   defined in: [AuftragPosition](definitionstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/DefinitionsTyp.schema.json#/properties/definitionsTyp")

### definitionsTyp Type

`string` ([DefinitionsTyp](definitionstyp.md))

### definitionsTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"ZAEHLZEIT"`       |             |
| `"SCHALTZEIT"`      |             |
| `"LEISTUNGSKURVEN"` |             |

## lokationsId

lokationsId

`lokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/lokationsId")

### lokationsId Type

`string`

## zaehlwerk

Zaehlwerk

`zaehlwerk`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [AuftragPosition](auftragposition-properties-zaehlwerk.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AuftragPosition.schema.json#/properties/zaehlwerk")

### zaehlwerk Type

`integer`
