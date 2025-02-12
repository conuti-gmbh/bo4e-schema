## TechnischeRessource Type

`object` ([TechnischeRessource](technischeressource.md))

# TechnischeRessource Properties

| Property                                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                    |
| :---------------------------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                             | `string`  | Required | cannot be null | [TechnischeRessource](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                        |
| [versionStruktur](#versionstruktur)                         | `string`  | Required | cannot be null | [TechnischeRessource](technischeressource-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/versionStruktur")                         |
| [ressourcenId](#ressourcenid)                               | `string`  | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-ressourcenid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/ressourcenId")                               |
| [sparte](#sparte)                                           | `string`  | Optional | cannot be null | [TechnischeRessource](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                                                                     |
| [lokationszuordnung](#lokationszuordnung)                   | `string`  | Optional | cannot be null | [TechnischeRessource](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")                                                 |
| [referenzMesslokation](#referenzmesslokation)               | `string`  | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-referenzmesslokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/referenzMesslokation")               |
| [referenzMarktlokation](#referenzmarktlokation)             | `string`  | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-referenzmarktlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/referenzMarktlokation")             |
| [referenzNetzlokation](#referenznetzlokation)               | `string`  | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-referenznetzlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/referenzNetzlokation")               |
| [referenzSteuerbareRessource](#referenzsteuerbareressource) | `string`  | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-referenzsteuerbareressource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/referenzSteuerbareRessource") |
| [nennleistung](#nennleistung)                               | `object`  | Optional | cannot be null | [TechnischeRessource](nennleistung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Nennleistung.schema.json#/properties/nennleistung")                                                                    |
| [speicherkapazitaet](#speicherkapazitaet)                   | `number`  | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-speicherkapazitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/speicherkapazitaet")                   |
| [verbrauchsart](#verbrauchsart)                             | `string`  | Optional | cannot be null | [TechnischeRessource](verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsart.schema.json#/properties/verbrauchsart")                                                                |
| [waermenutzung](#waermenutzung)                             | `string`  | Optional | cannot be null | [TechnischeRessource](waermenutzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waermenutzung.schema.json#/properties/waermenutzung")                                                                |
| [artEMobilitaet](#artemobilitaet)                           | `string`  | Optional | cannot be null | [TechnischeRessource](artemobilitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArtEmobilitaet.schema.json#/properties/artEMobilitaet")                                                             |
| [erzeugungsart](#erzeugungsart)                             | `string`  | Optional | cannot be null | [TechnischeRessource](erzeugungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Erzeugungsart.schema.json#/properties/erzeugungsart")                                                                |
| [speicherart](#speicherart)                                 | `string`  | Optional | cannot be null | [TechnischeRessource](speicherart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Speicherart.schema.json#/properties/speicherart")                                                                      |
| [enwg](#enwg)                                               | `boolean` | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-enwg.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/enwg")                                               |
| [inbetriebsetzungsdatum](#inbetriebsetzungsdatum)           | `string`  | Optional | cannot be null | [TechnischeRessource](inbetriebsetzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Inbetriebsetzung.schema.json#/properties/inbetriebsetzungsdatum")                                                 |
| [einordnung](#einordnung)                                   | `string`  | Optional | cannot be null | [TechnischeRessource](ressourcewechselmoeglichkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/RessourceWechselmoeglichkeit.schema.json#/properties/einordnung")                                     |
| [weitereEinrichtung](#weitereeinrichtung)                   | `boolean` | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-weitereeinrichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/weitereEinrichtung")                   |
| [art](#art)                                                 | `string`  | Optional | cannot be null | [TechnischeRessource](technischeressourceart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/TechnischeRessourceArt.schema.json#/properties/art")                                                        |
| [datenqualitaet](#datenqualitaet)                           | `string`  | Optional | cannot be null | [TechnischeRessource](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                                             |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum)               | `object`  | Optional | cannot be null | [TechnischeRessource](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                                                    |
| [erforderlicheProdukte](#erforderlicheprodukte)             | `array`   | Optional | cannot be null | [TechnischeRessource](technischeressource-properties-erforderlicheprodukte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/erforderlicheProdukte")             |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [TechnischeRessource](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"TECHNISCHE_RESSOURCE"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## ressourcenId

ressourcenId

`ressourcenId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-ressourcenid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/ressourcenId")

### ressourcenId Type

`string`

## sparte

Sparte

`sparte`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [TechnischeRessource](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

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

## lokationszuordnung

Lokationszuordnung

`lokationszuordnung`

*   is optional

*   Type: `string` ([Lokationszuordnung](lokationszuordnung.md))

*   cannot be null

*   defined in: [TechnischeRessource](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")

### lokationszuordnung Type

`string` ([Lokationszuordnung](lokationszuordnung.md))

### lokationszuordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"UNVERAENDERT"` |             |
| `"BEGINNT"`      |             |
| `"ENDET"`        |             |

## referenzMesslokation

referenzMesslokation

`referenzMesslokation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-referenzmesslokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/referenzMesslokation")

### referenzMesslokation Type

`string`

## referenzMarktlokation

referenzMarktlokation

`referenzMarktlokation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-referenzmarktlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/referenzMarktlokation")

### referenzMarktlokation Type

`string`

## referenzNetzlokation

referenzNetzlokation

`referenzNetzlokation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-referenznetzlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/referenzNetzlokation")

### referenzNetzlokation Type

`string`

## referenzSteuerbareRessource

referenzSteuerbareRessource

`referenzSteuerbareRessource`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-referenzsteuerbareressource.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/referenzSteuerbareRessource")

### referenzSteuerbareRessource Type

`string`

## nennleistung



`nennleistung`

*   is optional

*   Type: `object` ([Nennleistung](nennleistung.md))

*   cannot be null

*   defined in: [TechnischeRessource](nennleistung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Nennleistung.schema.json#/properties/nennleistung")

### nennleistung Type

`object` ([Nennleistung](nennleistung.md))

## speicherkapazitaet

Speicherkapazität
Beispiel: QTY+Z42:100:KWH'

`speicherkapazitaet`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-speicherkapazitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/speicherkapazitaet")

### speicherkapazitaet Type

`number`

### speicherkapazitaet Constraints

**unknown format**: the value of this string must follow the format: `float`

## verbrauchsart

Verbrauchsart

`verbrauchsart`

*   is optional

*   Type: `string` ([Verbrauchsart](verbrauchsart.md))

*   cannot be null

*   defined in: [TechnischeRessource](verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsart.schema.json#/properties/verbrauchsart")

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

## waermenutzung

Waermenutzung

`waermenutzung`

*   is optional

*   Type: `string` ([Waermenutzung](waermenutzung.md))

*   cannot be null

*   defined in: [TechnischeRessource](waermenutzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Waermenutzung.schema.json#/properties/waermenutzung")

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

## artEMobilitaet

ArtEmobilitaet

`artEMobilitaet`

*   is optional

*   Type: `string` ([ArtEmobilitaet](artemobilitaet.md))

*   cannot be null

*   defined in: [TechnischeRessource](artemobilitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ArtEmobilitaet.schema.json#/properties/artEMobilitaet")

### artEMobilitaet Type

`string` ([ArtEmobilitaet](artemobilitaet.md))

### artEMobilitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value  | Explanation |
| :----- | :---------- |
| `"WB"` |             |
| `"LS"` |             |
| `"LP"` |             |

## erzeugungsart

Auflistung der Erzeugungsarten von Energie.

`erzeugungsart`

*   is optional

*   Type: `string` ([Erzeugungsart](erzeugungsart.md))

*   cannot be null

*   defined in: [TechnischeRessource](erzeugungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Erzeugungsart.schema.json#/properties/erzeugungsart")

### erzeugungsart Type

`string` ([Erzeugungsart](erzeugungsart.md))

### erzeugungsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"EEG"`                    |             |
| `"KWK"`                    |             |
| `"EEG_DV"`                 |             |
| `"KWK_DV"`                 |             |
| `"WIND"`                   |             |
| `"SOLAR"`                  |             |
| `"KERNKRAFT"`              |             |
| `"WASSER"`                 |             |
| `"GEOTHERMIE"`             |             |
| `"BIOMASSE"`               |             |
| `"KOHLE"`                  |             |
| `"GAS"`                    |             |
| `"SONSTIGE"`               |             |
| `"SONSTIGE_EEG"`           |             |
| `"SONSTIGE_ERZEUGUNGSART"` |             |

## speicherart

Speicherart

`speicherart`

*   is optional

*   Type: `string` ([Speicherart](speicherart.md))

*   cannot be null

*   defined in: [TechnischeRessource](speicherart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Speicherart.schema.json#/properties/speicherart")

### speicherart Type

`string` ([Speicherart](speicherart.md))

### speicherart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"WASSERSTOFFSPEICHER"`  |             |
| `"PUMPSPEICHER"`         |             |
| `"BATTERIESPEICHER"`     |             |
| `"SONSTIGE_SPEICHERART"` |             |

## enwg

enwg

`enwg`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-enwg.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/enwg")

### enwg Type

`boolean`

## inbetriebsetzungsdatum

Inbetriebsetzung

`inbetriebsetzungsdatum`

*   is optional

*   Type: `string` ([Inbetriebsetzung](inbetriebsetzung.md))

*   cannot be null

*   defined in: [TechnischeRessource](inbetriebsetzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Inbetriebsetzung.schema.json#/properties/inbetriebsetzungsdatum")

### inbetriebsetzungsdatum Type

`string` ([Inbetriebsetzung](inbetriebsetzung.md))

### inbetriebsetzungsdatum Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                          | Explanation |
| :----------------------------- | :---------- |
| `"INBETRIEBSETZUNG_NACH_2023"` |             |
| `"INBETRIEBSETZUNG_VOR_2024"`  |             |

## einordnung

RessourceWechselmoeglichkeit

`einordnung`

*   is optional

*   Type: `string` ([RessourceWechselmoeglichkeit](ressourcewechselmoeglichkeit.md))

*   cannot be null

*   defined in: [TechnischeRessource](ressourcewechselmoeglichkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/RessourceWechselmoeglichkeit.schema.json#/properties/einordnung")

### einordnung Type

`string` ([RessourceWechselmoeglichkeit](ressourcewechselmoeglichkeit.md))

### einordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                          | Explanation |
| :--------------------------------------------- | :---------- |
| `"WECHSELMOEGLICHKEIT_EINMALIG_NOCH_MOEGLICH"` |             |
| `"WECHSELMOEGLICHKEIT_NICHT_MOEGLICH"`         |             |
| `"BEFRISTET_OHNE_WECHSELMOEGLICHKEIT"`         |             |
| `"WECHSEL_WURDE_DURCHGEFUEHRT"`                |             |

## weitereEinrichtung

weitereEinrichtung

`weitereEinrichtung`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-weitereeinrichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/weitereEinrichtung")

### weitereEinrichtung Type

`boolean`

## art

TechnischeRessourceArt

`art`

*   is optional

*   Type: `string` ([TechnischeRessourceArt](technischeressourceart.md))

*   cannot be null

*   defined in: [TechnischeRessource](technischeressourceart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/TechnischeRessourceArt.schema.json#/properties/art")

### art Type

`string` ([TechnischeRessourceArt](technischeressourceart.md))

### art Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"STROMERZEUGUNG"` |             |
| `"STROMVERBRAUCH"` |             |
| `"SPEICHER"`       |             |

## datenqualitaet

Datenqualitaet

`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [TechnischeRessource](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

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

*   defined in: [TechnischeRessource](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))

## erforderlicheProdukte

erforderlicheProdukte

`erforderlicheProdukte`

*   is optional

*   Type: `object[]` ([Produkt](produkt.md))

*   cannot be null

*   defined in: [TechnischeRessource](technischeressource-properties-erforderlicheprodukte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/TechnischeRessource.schema.json#/properties/erforderlicheProdukte")

### erforderlicheProdukte Type

`object[]` ([Produkt](produkt.md))
