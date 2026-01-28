## Preisposition Type

`object` ([Preisposition](preisposition.md))

# Preisposition Properties

| Property                                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                     |
| :---------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [berechnungsmethode](#berechnungsmethode)       | `string`  | Optional | cannot be null | [Preisposition](kalkulationsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Kalkulationsmethode.schema.json#/properties/berechnungsmethode")                      |
| [leistungstyp](#leistungstyp)                   | `string`  | Optional | cannot be null | [Preisposition](leistungstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Leistungstyp.schema.json#/properties/leistungstyp")                                          |
| [leistungsbezeichnung](#leistungsbezeichnung)   | `string`  | Optional | cannot be null | [Preisposition](leistungsbezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Leistungsbezeichnung.schema.json#/properties/leistungsbezeichnung")                  |
| [preiseinheit](#preiseinheit)                   | `string`  | Optional | cannot be null | [Preisposition](waehrungseinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waehrungseinheit.schema.json#/properties/preiseinheit")                                  |
| [bezugsgroesse](#bezugsgroesse)                 | `string`  | Optional | cannot be null | [Preisposition](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/bezugsgroesse")                                       |
| [zeitbasis](#zeitbasis)                         | `string`  | Optional | cannot be null | [Preisposition](zeiteinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeiteinheit.schema.json#/properties/zeitbasis")                                               |
| [tarifzeit](#tarifzeit)                         | `string`  | Optional | cannot be null | [Preisposition](tarifzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tarifzeit.schema.json#/properties/tarifzeit")                                                   |
| [bdewArtikelnummer](#bdewartikelnummer)         | `string`  | Optional | cannot be null | [Preisposition](bdewartikelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BDEWArtikelnummer.schema.json#/properties/bdewArtikelnummer")                           |
| [zonungsgroesse](#zonungsgroesse)               | `string`  | Optional | cannot be null | [Preisposition](bemessungsgroesse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bemessungsgroesse.schema.json#/properties/zonungsgroesse")                              |
| [preisschluesselstamm](#preisschluesselstamm)   | `string`  | Optional | cannot be null | [Preisposition](preisposition-properties-preisschluesselstamm.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/preisschluesselstamm") |
| [positionsnummer](#positionsnummer)             | `integer` | Optional | cannot be null | [Preisposition](preisposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/positionsnummer")           |
| [messebene](#messebene)                         | `string`  | Optional | cannot be null | [Preisposition](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/messebene")                                                   |
| [beschreibung](#beschreibung)                   | `string`  | Optional | cannot be null | [Preisposition](preisposition-properties-beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/beschreibung")                 |
| [beschreibungsformat](#beschreibungsformat)     | `string`  | Optional | cannot be null | [Preisposition](beschreibungsformat.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Beschreibungsformat.schema.json#/properties/beschreibungsformat")                     |
| [verarbeitungszeitraum](#verarbeitungszeitraum) | `object`  | Optional | cannot be null | [Preisposition](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/verarbeitungszeitraum")                                          |
| [artikelId](#artikelid)                         | `string`  | Optional | cannot be null | [Preisposition](preisposition-properties-artikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/artikelId")                       |
| [zu\_abschlaege](#zu_abschlaege)                | `array`   | Optional | can be null    | [Preisposition](preisposition-properties-zu_abschlaege.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/zu_abschlaege")               |
| [preisstaffeln](#preisstaffeln)                 | `array`   | Optional | can be null    | [Preisposition](preisposition-properties-preisstaffeln.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/preisstaffeln")               |

## berechnungsmethode

Auflistung der verschiedenen Berechnungsmethoden für ein Preisblatt

`berechnungsmethode`

*   is optional

*   Type: `string` ([Kalkulationsmethode](kalkulationsmethode.md))

*   cannot be null

*   defined in: [Preisposition](kalkulationsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Kalkulationsmethode.schema.json#/properties/berechnungsmethode")

### berechnungsmethode Type

`string` ([Kalkulationsmethode](kalkulationsmethode.md))

### berechnungsmethode Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                      | Explanation |
| :------------------------------------------------------------------------- | :---------- |
| `"KEINE"`                                                                  |             |
| `"STAFFELN"`                                                               |             |
| `"ZONEN"`                                                                  |             |
| `"VORZONEN_GP"`                                                            |             |
| `"SIGMOID"`                                                                |             |
| `"BLINDARBEIT_GT_50_PROZENT"`                                              |             |
| `"BLINDARBEIT_GT_40_PROZENT"`                                              |             |
| `"AP_GP_ZONEN"`                                                            |             |
| `"LP_INSTALL_LEISTUNG"`                                                    |             |
| `"AP_TRANSPORT_ODER_VERTEILNETZ"`                                          |             |
| `"AP_TRANSPORT_ODER_VERTEILNETZ_ORTSVERTEILNETZ_SIGMOID"`                  |             |
| `"LP_JAHRESVERBRAUCH"`                                                     |             |
| `"LP_TRANSPORT_ODER_VERTEILNETZ"`                                          |             |
| `"LP_TRANSPORT_ODER_VERTEILNETZ_ORTSVERTEILNETZ_SIGMOID"`                  |             |
| `"FUNKTIONEN"`                                                             |             |
| `"VERBRAUCH_UEBER_SLP_GRENZE_FUNKTIONSBEZOGEN_WEITERE_BERECHNUNG_ALS_LGK"` |             |

## leistungstyp

Leistungstyp

`leistungstyp`

*   is optional

*   Type: `string` ([Leistungstyp](leistungstyp.md))

*   cannot be null

*   defined in: [Preisposition](leistungstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Leistungstyp.schema.json#/properties/leistungstyp")

### leistungstyp Type

`string` ([Leistungstyp](leistungstyp.md))

### leistungstyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                               | Explanation |
| :---------------------------------- | :---------- |
| `"ARBEITSPREIS_WIRKARBEIT"`         |             |
| `"LEISTUNGSPREIS_WIRKLEISTUNG"`     |             |
| `"ARBEITSPREIS_BLINDARBEIT_IND"`    |             |
| `"ARBEITSPREIS_BLINDARBEIT_KAP"`    |             |
| `"GRUNDPREIS"`                      |             |
| `"MEHRMINDERMENGE"`                 |             |
| `"MESSSTELLENBETRIEB"`              |             |
| `"MESSDIENSTLEISTUNG"`              |             |
| `"MESSDIENSTLEISTUNG_INKL_MESSUNG"` |             |
| `"ABRECHNUNG"`                      |             |
| `"KONZESSIONS_ABGABE"`              |             |
| `"KWK_UMLAGE"`                      |             |
| `"OFFSHORE_UMLAGE"`                 |             |
| `"ABLAV_UMLAGE"`                    |             |
| `"REGELENERGIE_UMLAGE"`             |             |
| `"BILANZIERUNG_UMLAGE"`             |             |
| `"AUSLESUNG_ZUSAETZLICH"`           |             |
| `"ABLESUNG_ZUSAETZLICH"`            |             |
| `"ABRECHNUNG_ZUSAETZLICH"`          |             |
| `"SPERRUNG"`                        |             |
| `"ENTSPERRUNG"`                     |             |
| `"MAHNKOSTEN"`                      |             |
| `"INKASSOKOSTEN"`                   |             |

## leistungsbezeichnung

Leistungsbezeichnung

`leistungsbezeichnung`

*   is optional

*   Type: `string` ([Leistungsbezeichnung](leistungsbezeichnung.md))

*   cannot be null

*   defined in: [Preisposition](leistungsbezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Leistungsbezeichnung.schema.json#/properties/leistungsbezeichnung")

### leistungsbezeichnung Type

`string` ([Leistungsbezeichnung](leistungsbezeichnung.md))

### leistungsbezeichnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                               | Explanation |
| :---------------------------------- | :---------- |
| `"POG_VERBRAUCH_IMS_UEBER_100K"`    |             |
| `"POG_VERBRAUCH_IMS_50K_BIS_100K"`  |             |
| `"POG_VERBRAUCH_IMS_20K_BIS_50K"`   |             |
| `"POG_VERBRAUCH_IMS_10K_BIS_20K"`   |             |
| `"POG_VERBRAUCH_IMS_UNTERBRECHBAR"` |             |
| `"POG_VERBRAUCH_IMS_6K_BIS_10K"`    |             |
| `"POG_ERZEUGUNG_IMS_7_BIS_15"`      |             |
| `"POG_ERZEUGUNG_IMS_15_BIS_30"`     |             |
| `"POG_ERZEUGUNG_IMS_30_BIS_100"`    |             |
| `"POG_ERZEUGUNG_IMS_UEBER_100"`     |             |
| `"POG_MME"`                         |             |
| `"POG_VERBRAUCH_IMS_4K_BIS_6K"`     |             |
| `"POG_VERBRAUCH_IMS_3K_BIS_4K"`     |             |
| `"POG_VERBRAUCH_IMS_2K_BIS_3K"`     |             |
| `"POG_VERBRAUCH_IMS_0_BIS_2K"`      |             |
| `"POG_ERZEUGUNG_IMS_OPTIONAL"`      |             |
| `"ZUSATZLEISTUNG"`                  |             |

## preiseinheit

Waehrungseinheit

`preiseinheit`

*   is optional

*   Type: `string` ([Waehrungseinheit](waehrungseinheit.md))

*   cannot be null

*   defined in: [Preisposition](waehrungseinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waehrungseinheit.schema.json#/properties/preiseinheit")

### preiseinheit Type

`string` ([Waehrungseinheit](waehrungseinheit.md))

### preiseinheit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"EUR"` |             |
| `"CT"`  |             |

## bezugsgroesse

Einheit: Messgrößen, die per Messung oder Vorgabe ermittelt werden können

`bezugsgroesse`

*   is optional

*   Type: `string` ([Mengeneinheit](mengeneinheit.md))

*   cannot be null

*   defined in: [Preisposition](mengeneinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengeneinheit.schema.json#/properties/bezugsgroesse")

### bezugsgroesse Type

`string` ([Mengeneinheit](mengeneinheit.md))

### bezugsgroesse Constraints

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
| `"Z16"`        |             |
| `"KWT"`        |             |

## zeitbasis

Zeiteinheit

`zeitbasis`

*   is optional

*   Type: `string` ([Zeiteinheit](zeiteinheit.md))

*   cannot be null

*   defined in: [Preisposition](zeiteinheit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeiteinheit.schema.json#/properties/zeitbasis")

### zeitbasis Type

`string` ([Zeiteinheit](zeiteinheit.md))

### zeitbasis Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"SEKUNDE"`        |             |
| `"MINUTE"`         |             |
| `"STUNDE"`         |             |
| `"VIERTEL_STUNDE"` |             |
| `"TAG"`            |             |
| `"WOCHE"`          |             |
| `"MONAT"`          |             |
| `"QUARTAL"`        |             |
| `"HALBJAHR"`       |             |
| `"JAHR"`           |             |

## tarifzeit

Tarifzeit

`tarifzeit`

*   is optional

*   Type: `string` ([Tarifzeit](tarifzeit.md))

*   cannot be null

*   defined in: [Preisposition](tarifzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tarifzeit.schema.json#/properties/tarifzeit")

### tarifzeit Type

`string` ([Tarifzeit](tarifzeit.md))

### tarifzeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"TZ_STANDARD"` |             |
| `"TZ_HT"`       |             |
| `"TZ_NT"`       |             |

## bdewArtikelnummer

BDEW Artikelnummer

`bdewArtikelnummer`

*   is optional

*   Type: `string` ([BDEWArtikelnummer](bdewartikelnummer.md))

*   cannot be null

*   defined in: [Preisposition](bdewartikelnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BDEWArtikelnummer.schema.json#/properties/bdewArtikelnummer")

### bdewArtikelnummer Type

`string` ([BDEWArtikelnummer](bdewartikelnummer.md))

### bdewArtikelnummer Constraints

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

## zonungsgroesse

Zur Abbildung von Messgrössen und zur Verwendung in energiewirtschaftlichen Berechnungen.

`zonungsgroesse`

*   is optional

*   Type: `string` ([Bemessungsgroesse](bemessungsgroesse.md))

*   cannot be null

*   defined in: [Preisposition](bemessungsgroesse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bemessungsgroesse.schema.json#/properties/zonungsgroesse")

### zonungsgroesse Type

`string` ([Bemessungsgroesse](bemessungsgroesse.md))

### zonungsgroesse Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                 | Explanation |
| :-------------------- | :---------- |
| `"WIRKARBEIT_EL"`     |             |
| `"LEISTUNG_EL"`       |             |
| `"BLINDARBEIT_KAP"`   |             |
| `"BLINDARBEIT_IND"`   |             |
| `"BLINDLEISTUNG_KAP"` |             |
| `"BLINDLEISTUNG_IND"` |             |
| `"WIRKARBEIT_TH"`     |             |
| `"LEISTUNG_TH"`       |             |
| `"VOLUMEN"`           |             |
| `"VOLUMENSTROM"`      |             |
| `"BENUTZUNGSDAUER"`   |             |
| `"ANZAHL"`            |             |

## preisschluesselstamm

Preisschlüsselstamm>

`preisschluesselstamm`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Preisposition](preisposition-properties-preisschluesselstamm.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/preisschluesselstamm")

### preisschluesselstamm Type

`string`

## positionsnummer

Fortlaufende Nummer für die Preisposition

`positionsnummer`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Preisposition](preisposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/positionsnummer")

### positionsnummer Type

`integer`

## messebene

Netzebene

`messebene`

*   is optional

*   Type: `string` ([Netzebene](netzebene.md))

*   cannot be null

*   defined in: [Preisposition](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/messebene")

### messebene Type

`string` ([Netzebene](netzebene.md))

### messebene Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"NSP"`          |             |
| `"MSP"`          |             |
| `"HSP"`          |             |
| `"HSS"`          |             |
| `"MSP_NSP_UMSP"` |             |
| `"HSP_MSP_UMSP"` |             |
| `"HSS_HSP_UMSP"` |             |
| `"HD"`           |             |
| `"MD"`           |             |
| `"ND"`           |             |

## beschreibung

Produkt-/Leistungsbeschreibung, wenn IMD+X vorhanden Vgl. PRICAT IMD 7008

`beschreibung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Preisposition](preisposition-properties-beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/beschreibung")

### beschreibung Type

`string`

## beschreibungsformat

Beschreibungsformat der Produktbeschreibung

`beschreibungsformat`

*   is optional

*   Type: `string` ([Beschreibungsformat](beschreibungsformat.md))

*   cannot be null

*   defined in: [Preisposition](beschreibungsformat.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Beschreibungsformat.schema.json#/properties/beschreibungsformat")

### beschreibungsformat Type

`string` ([Beschreibungsformat](beschreibungsformat.md))

### beschreibungsformat Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"CODE"`             |             |
| `"FREIER_TEXT"`      |             |
| `"TEILSTRUKTURIERT"` |             |

## verarbeitungszeitraum

Verarbeitungszeitraum. Details Zeitraum

`verarbeitungszeitraum`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Preisposition](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/verarbeitungszeitraum")

### verarbeitungszeitraum Type

`object` ([Zeitraum](zeitraum.md))

## artikelId

Die genauen Bedeutungen der einzelnen Artikel-IDs sind in der EDI\@Energy Codeliste der Artikelnummern
und Artikel-IDs zu finden, die in der Spalte "PRICAT Codeverwendung" ein X haben

`artikelId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Preisposition](preisposition-properties-artikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/artikelId")

### artikelId Type

`string`

## zu\_abschlaege

Zuschläge oder Abschläge auf die Position.

`zu_abschlaege`

*   is optional

*   Type: `object[]` ([PositionsAufAbschlag](positionsaufabschlag.md))

*   can be null

*   defined in: [Preisposition](preisposition-properties-zu_abschlaege.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/zu_abschlaege")

### zu\_abschlaege Type

`object[]` ([PositionsAufAbschlag](positionsaufabschlag.md))

## preisstaffeln

Preisstaffeln, die zu dieser Preisposition gehören. Details Preisstaffel

`preisstaffeln`

*   is optional

*   Type: `object[]` ([Preisstaffel](preisstaffel.md))

*   can be null

*   defined in: [Preisposition](preisposition-properties-preisstaffeln.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Preisposition.schema.json#/properties/preisstaffeln")

### preisstaffeln Type

`object[]` ([Preisstaffel](preisstaffel.md))
