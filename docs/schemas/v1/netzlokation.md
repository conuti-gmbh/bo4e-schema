## Netzlokation Type

`object` ([Netzlokation](netzlokation.md))

# Netzlokation Properties

| Property                                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                             |
| :---------------------------------------------------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                             | `string`  | Required | cannot be null | [Netzlokation](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                        |
| [versionStruktur](#versionstruktur)                         | `string`  | Required | cannot be null | [Netzlokation](netzlokation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/versionStruktur")                       |
| [netzlokationsId](#netzlokationsid)                         | `string`  | Optional | cannot be null | [Netzlokation](netzlokation-properties-netzlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/netzlokationsId")                       |
| [sparte](#sparte)                                           | `string`  | Optional | cannot be null | [Netzlokation](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                                                     |
| [netzanschlussleistung](#netzanschlussleistung)             | `string`  | Optional | cannot be null | [Netzlokation](netzlokation-properties-netzanschlussleistung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/netzanschlussleistung")           |
| [grundzustaendigerMSBCodeNr](#grundzustaendigermsbcodenr)   | `string`  | Optional | cannot be null | [Netzlokation](netzlokation-properties-grundzustaendigermsbcodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/grundzustaendigerMSBCodeNr") |
| [steuerkanal](#steuerkanal)                                 | `boolean` | Optional | cannot be null | [Netzlokation](netzlokation-properties-steuerkanal.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/steuerkanal")                               |
| [lokationszuordnung](#lokationszuordnung)                   | `string`  | Optional | cannot be null | [Netzlokation](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")                                 |
| [produktdatenRelevanteRolle](#produktdatenrelevanterolle)   | `string`  | Optional | cannot be null | [Netzlokation](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/produktdatenRelevanteRolle")                                         |
| [auftraggebenderMarktpartner](#auftraggebendermarktpartner) | `object`  | Optional | cannot be null | [Netzlokation](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/auftraggebenderMarktpartner")                                |
| [konfigurationsprodukt](#konfigurationsprodukt)             | `string`  | Optional | cannot be null | [Netzlokation](netzlokation-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/konfigurationsprodukt")           |
| [keinKonfigurationsprodukt](#keinkonfigurationsprodukt)     | `boolean` | Optional | cannot be null | [Netzlokation](netzlokation-properties-keinkonfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/keinKonfigurationsprodukt")   |
| [leistungskurvendefinition](#leistungskurvendefinition)     | `string`  | Optional | cannot be null | [Netzlokation](netzlokation-properties-leistungskurvendefinition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/leistungskurvendefinition")   |
| [marktrollen](#marktrollen)                                 | `array`   | Optional | cannot be null | [Netzlokation](netzlokation-properties-marktrollen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/marktrollen")                               |
| [zaehlwerke](#zaehlwerke)                                   | `array`   | Optional | cannot be null | [Netzlokation](netzlokation-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/zaehlwerke")                                 |
| [abrechnungsdaten](#abrechnungsdaten)                       | `array`   | Optional | cannot be null | [Netzlokation](netzlokation-properties-abrechnungsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/abrechnungsdaten")                     |
| [datenqualitaet](#datenqualitaet)                           | `string`  | Optional | cannot be null | [Netzlokation](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                             |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum)               | `object`  | Optional | cannot be null | [Netzlokation](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                                    |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Netzlokation](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

### boTyp Type

`string` ([BOTyp](botyp.md))

### boTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                           | Explanation |
| :------------------------------ | :---------- |
| `"ANSPRECHPARTNER"`             |             |
| `"AVIS"`                        |             |
| `"ENERGIEMENGE"`                |             |
| `"GESCHAEFTSOBJEKT"`            |             |
| `"GESCHAEFTSPARTNER"`           |             |
| `"MARKTLOKATION"`               |             |
| `"MARKTTEILNEHMER"`             |             |
| `"MESSLOKATION"`                |             |
| `"ZAEHLER"`                     |             |
| `"KOSTEN"`                      |             |
| `"TARIF"`                       |             |
| `"PREISBLATT"`                  |             |
| `"PREISBLATTNETZNUTZUNG"`       |             |
| `"PREISBLATTMESSUNG"`           |             |
| `"PREISBLATTUMLAGEN"`           |             |
| `"PREISBLATTDIENSTLEISTUNG"`    |             |
| `"PREISBLATTKONZESSIONSABGABE"` |             |
| `"ZEITREIHE"`                   |             |
| `"LASTGANG"`                    |             |
| `"HANDELSUNSTIMMIGKEIT"`        |             |
| `"ANFRAGE"`                     |             |
| `"AUFTRAG"`                     |             |
| `"STATUSMITTEILUNG"`            |             |
| `"BERECHNUNGSFORMEL"`           |             |
| `"RECHNUNG"`                    |             |
| `"BILANZIERUNG"`                |             |
| `"NETZNUTZUNGSVERTRAG"`         |             |
| `"MESSSTELLENBETRIEBSVERTRAG"`  |             |
| `"ENERGIELIEFERVERTRAG"`        |             |
| `"SPERRAUFTRAG"`                |             |
| `"ANGEBOT"`                     |             |
| `"TRANCHE"`                     |             |
| `"KOMMUNIKATIONSDATEN"`         |             |
| `"ZAEHLZEITDEFINITION"`         |             |
| `"SCHALTZEITDEFINITION"`        |             |
| `"LEISTUNGSKURVENDEFINITION"`   |             |
| `"NETZLOKATION"`                |             |
| `"STEUERBARE_RESSOURCE"`        |             |
| `"TECHNISCHE_RESSOURCE"`        |             |
| `"AD_HOC_STEUERKANAL"`          |             |
| `"LOKATIONSBUENDEL"`            |             |
| `"WERTE_NACH_TYP2"`             |             |
| `"REKLAMATION"`                 |             |
| `"STATUSBERICHT"`               |             |
| `"VERTRAG"`                     |             |
| `"BILANZKREIS"`                 |             |
| `"VERWENDUNGSZEITRAUM"`         |             |
| `"TARIFINFO"`                   |             |

### boTyp Default Value

The default value is:

```json
"NETZLOKATION"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## netzlokationsId



`netzlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-netzlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/netzlokationsId")

### netzlokationsId Type

`string`

## sparte



`sparte`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [Netzlokation](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

### sparte Type

`string` ([Sparte](sparte.md))

### sparte Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"STROM"`      |             |
| `"GAS"`        |             |
| `"FERNWAERME"` |             |
| `"NAHWAERME"`  |             |
| `"WASSER"`     |             |
| `"ABWASSER"`   |             |

## netzanschlussleistung



`netzanschlussleistung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-netzanschlussleistung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/netzanschlussleistung")

### netzanschlussleistung Type

`string`

## grundzustaendigerMSBCodeNr



`grundzustaendigerMSBCodeNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-grundzustaendigermsbcodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/grundzustaendigerMSBCodeNr")

### grundzustaendigerMSBCodeNr Type

`string`

## steuerkanal



`steuerkanal`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-steuerkanal.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/steuerkanal")

### steuerkanal Type

`boolean`

## lokationszuordnung



`lokationszuordnung`

*   is optional

*   Type: `string` ([Lokationszuordnung](lokationszuordnung.md))

*   cannot be null

*   defined in: [Netzlokation](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")

### lokationszuordnung Type

`string` ([Lokationszuordnung](lokationszuordnung.md))

### lokationszuordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"UNVERAENDERT"` |             |
| `"BEGINNT"`      |             |
| `"ENDET"`        |             |

## produktdatenRelevanteRolle



`produktdatenRelevanteRolle`

*   is optional

*   Type: `string` ([Marktrolle](marktrolle.md))

*   cannot be null

*   defined in: [Netzlokation](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/produktdatenRelevanteRolle")

### produktdatenRelevanteRolle Type

`string` ([Marktrolle](marktrolle.md))

### produktdatenRelevanteRolle Constraints

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
| `"BKO"`             |             |
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

## auftraggebenderMarktpartner



`auftraggebenderMarktpartner`

*   is optional

*   Type: `object` ([Marktteilnehmer](marktteilnehmer.md))

*   cannot be null

*   defined in: [Netzlokation](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/auftraggebenderMarktpartner")

### auftraggebenderMarktpartner Type

`object` ([Marktteilnehmer](marktteilnehmer.md))

## konfigurationsprodukt



`konfigurationsprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/konfigurationsprodukt")

### konfigurationsprodukt Type

`string`

## keinKonfigurationsprodukt



`keinKonfigurationsprodukt`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-keinkonfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/keinKonfigurationsprodukt")

### keinKonfigurationsprodukt Type

`boolean`

## leistungskurvendefinition



`leistungskurvendefinition`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-leistungskurvendefinition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/leistungskurvendefinition")

### leistungskurvendefinition Type

`string`

## marktrollen



`marktrollen`

*   is optional

*   Type: `object[]` ([Marktteilnehmer](marktteilnehmer.md))

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-marktrollen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/marktrollen")

### marktrollen Type

`object[]` ([Marktteilnehmer](marktteilnehmer.md))

## zaehlwerke



`zaehlwerke`

*   is optional

*   Type: `object[]` ([Zaehlwerk](zaehlwerk.md))

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/zaehlwerke")

### zaehlwerke Type

`object[]` ([Zaehlwerk](zaehlwerk.md))

## abrechnungsdaten



`abrechnungsdaten`

*   is optional

*   Type: `object[]` ([Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten.md))

*   cannot be null

*   defined in: [Netzlokation](netzlokation-properties-abrechnungsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Netzlokation.schema.json#/properties/abrechnungsdaten")

### abrechnungsdaten Type

`object[]` ([Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten.md))

## datenqualitaet



`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Netzlokation](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

### datenqualitaet Type

`string` ([Datenqualitaet](datenqualitaet.md))

### datenqualitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                    | Explanation |
| :--------------------------------------- | :---------- |
| `"ERWARTETE_DATEN"`                      |             |
| `"IM_SYSTEM_VORHANDENE_DATEN"`           |             |
| `"INFORMATIVE_DATEN"`                    |             |
| `"GUELTIGE_DATEN"`                       |             |
| `"KEINE_DATEN"`                          |             |
| `"IM_SYSTEM_KEINE_DATEN_VORHANDEN"`      |             |
| `"KEINE_DATEN_ERWARTET"`                 |             |
| `"DIFFERENZ_DATEN"`                      |             |
| `"DIFFERENZ_ERWARTETE_DATEN"`            |             |
| `"DIFFERENZ_IM_SYSTEM_VORHANDENE_DATEN"` |             |

## gueltigkeitszeitraum



`gueltigkeitszeitraum`

*   is optional

*   Type: `object` ([Zeitraum](zeitraum.md))

*   cannot be null

*   defined in: [Netzlokation](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))
