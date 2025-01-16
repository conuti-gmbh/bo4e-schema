## Vertrag Type

`object` ([Vertrag](vertrag.md))

# Vertrag Properties

| Property                                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                              |
| :-------------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                               | `string`  | Required | cannot be null | [Vertrag](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                              |
| [versionStruktur](#versionstruktur)           | `string`  | Required | cannot be null | [Vertrag](vertrag-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/versionStruktur")       |
| [sparte](#sparte)                             | `string`  | Optional | cannot be null | [Vertrag](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                           |
| [vertragsart](#vertragsart)                   | `string`  | Optional | cannot be null | [Vertrag](vertrag-properties-vertragsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragsart")               |
| [vertragsnummer](#vertragsnummer)             | `string`  | Optional | cannot be null | [Vertrag](vertrag-properties-vertragsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragsnummer")         |
| [beschreibung](#beschreibung)                 | `string`  | Optional | cannot be null | [Vertrag](vertrag-properties-beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/beschreibung")             |
| [lokationsId](#lokationsid)                   | `string`  | Optional | cannot be null | [Vertrag](vertrag-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/lokationsId")               |
| [lokationsTyp](#lokationstyp)                 | `string`  | Optional | cannot be null | [Vertrag](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")                         |
| [vertragsstatus](#vertragsstatus)             | `string`  | Optional | cannot be null | [Vertrag](vertragstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Vertragstatus.schema.json#/properties/vertragsstatus")                     |
| [vertragsbeginn](#vertragsbeginn)             | `string`  | Optional | cannot be null | [Vertrag](vertrag-properties-vertragsbeginn.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragsbeginn")         |
| [vertragsende](#vertragsende)                 | `string`  | Optional | cannot be null | [Vertrag](vertrag-properties-vertragsende.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragsende")             |
| [gemeinderabatt](#gemeinderabatt)             | `integer` | Optional | cannot be null | [Vertrag](vertrag-properties-gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/gemeinderabatt")         |
| [vertragskonditionen](#vertragskonditionen)   | `object`  | Optional | cannot be null | [Vertrag](vertragskonditionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/vertragskonditionen")     |
| [korrespondenzpartner](#korrespondenzpartner) | `object`  | Optional | cannot be null | [Vertrag](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/korrespondenzpartner")         |
| [abrechnungUeberNna](#abrechnunguebernna)     | `boolean` | Optional | cannot be null | [Vertrag](vertrag-properties-abrechnunguebernna.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/abrechnungUeberNna") |
| [datenqualitaet](#datenqualitaet)             | `string`  | Optional | cannot be null | [Vertrag](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                   |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum) | `object`  | Optional | cannot be null | [Vertrag](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                          |
| [vertragspartner1](#vertragspartner1)         | `array`   | Optional | cannot be null | [Vertrag](vertrag-properties-vertragspartner1.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragspartner1")     |
| [vertragspartner2](#vertragspartner2)         | `array`   | Optional | cannot be null | [Vertrag](vertrag-properties-vertragspartner2.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragspartner2")     |
| [enFG](#enfg)                                 | `array`   | Optional | cannot be null | [Vertrag](vertrag-properties-enfg.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/enFG")                             |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Vertrag](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"VERTRAG"
```

## versionStruktur

obligatory version of the BO4E definition. Currently hard coded to 1

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## sparte

Sparte

`sparte`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [Vertrag](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

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

## vertragsart

Hier ist festgelegt, um welche Art von Vertrag es sich handelt. Z.B. Netznutzungvertrag. Details siehe ENUM
Vertragsart

`vertragsart`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-vertragsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragsart")

### vertragsart Type

`string`

## vertragsnummer

Eine im Verwendungskontext eindeutige Nummer für den Vertrag

`vertragsnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-vertragsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragsnummer")

### vertragsnummer Type

`string`

## beschreibung

Freitext zur Beschreibung der Konditionen, z.B. "Standardkonditionen Gas"

`beschreibung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-beschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/beschreibung")

### beschreibung Type

`string`

## lokationsId

lokationsId

`lokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/lokationsId")

### lokationsId Type

`string`

## lokationsTyp

Lokationstyp

`lokationsTyp`

*   is optional

*   Type: `string` ([Lokationstyp](lokationstyp.md))

*   cannot be null

*   defined in: [Vertrag](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")

### lokationsTyp Type

`string` ([Lokationstyp](lokationstyp.md))

### lokationsTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"MALO"`                 |             |
| `"MELO"`                 |             |
| `"NELO"`                 |             |
| `"TECHNISCHE_RESSOURCE"` |             |

## vertragsstatus

Vertragstatus

`vertragsstatus`

*   is optional

*   Type: `string` ([Vertragstatus](vertragstatus.md))

*   cannot be null

*   defined in: [Vertrag](vertragstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Vertragstatus.schema.json#/properties/vertragsstatus")

### vertragsstatus Type

`string` ([Vertragstatus](vertragstatus.md))

### vertragsstatus Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"IN_ARBEIT"`    |             |
| `"UEBERMITTELT"` |             |
| `"ANGENOMMEN"`   |             |
| `"AKTIV"`        |             |
| `"ABGELEHNT"`    |             |
| `"WIDERRUFEN"`   |             |
| `"STORNIERT"`    |             |
| `"GEKUENDIGT"`   |             |
| `"BEENDET"`      |             |

## vertragsbeginn

Gibt an, wann der Vertrag beginnt.

`vertragsbeginn`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-vertragsbeginn.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragsbeginn")

### vertragsbeginn Type

`string`

### vertragsbeginn Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## vertragsende

Gibt an, wann der Vertrag (voraussichtlich) endet oder beendet wurde.

`vertragsende`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-vertragsende.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragsende")

### vertragsende Type

`string`

### vertragsende Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## gemeinderabatt

gemeinderabatt für EDIFACT mapping.

`gemeinderabatt`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-gemeinderabatt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/gemeinderabatt")

### gemeinderabatt Type

`integer`

## vertragskonditionen

Festlegungen zu Laufzeiten und Kündigungsfristen. Details siehe COM Vertragskonditionen

`vertragskonditionen`

*   is optional

*   Type: `object` ([Vertragskonditionen](vertragskonditionen.md))

*   cannot be null

*   defined in: [Vertrag](vertragskonditionen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Vertragskonditionen.schema.json#/properties/vertragskonditionen")

### vertragskonditionen Type

`object` ([Vertragskonditionen](vertragskonditionen.md))

## korrespondenzpartner

korrespondenzpartner für EDIFACT mapping

`korrespondenzpartner`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Vertrag](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/korrespondenzpartner")

### korrespondenzpartner Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## abrechnungUeberNna

abrechnungUeberNna

`abrechnungUeberNna`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-abrechnunguebernna.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/abrechnungUeberNna")

### abrechnungUeberNna Type

`boolean`

## datenqualitaet

Datenqualitaet

`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Vertrag](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

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

*   defined in: [Vertrag](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))

## vertragspartner1

Der "erstgenannte" Vertragspartner. In der Regel der Aussteller des Vertrags. Beispiel: "Vertrag zwischen
Vertagspartner 1 ..." Siehe BO Geschaeftspartner

`vertragspartner1`

*   is optional

*   Type: `object[]` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-vertragspartner1.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragspartner1")

### vertragspartner1 Type

`object[]` ([Geschaeftspartner](geschaeftspartner.md))

## vertragspartner2

Der "zweitgenannte" Vertragspartner. In der Regel der Empfänger des Vertrags. Beispiel "Vertrag zwischen
Vertagspartner 1 und Vertragspartner 2". Siehe BO Geschaeftspartner

`vertragspartner2`

*   is optional

*   Type: `object[]` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-vertragspartner2.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/vertragspartner2")

### vertragspartner2 Type

`object[]` ([Geschaeftspartner](geschaeftspartner.md))

## enFG

enFG

`enFG`

*   is optional

*   Type: `object[]` ([EnFG](enfg.md))

*   cannot be null

*   defined in: [Vertrag](vertrag-properties-enfg.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Vertrag.schema.json#/properties/enFG")

### enFG Type

`object[]` ([EnFG](enfg.md))
