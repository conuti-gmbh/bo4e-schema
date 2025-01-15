## Messlokation Type

`object` ([Messlokation](messlokation.md))

# Messlokation Properties

| Property                                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :------------------------------------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                     | `string`  | Required | cannot be null | [Messlokation](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                  |
| [versionStruktur](#versionstruktur)                                 | `string`  | Required | cannot be null | [Messlokation](messlokation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/versionStruktur")                                 |
| [messlokationsId](#messlokationsid)                                 | `string`  | Optional | cannot be null | [Messlokation](messlokation-properties-messlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/messlokationsId")                                 |
| [sparte](#sparte)                                                   | `string`  | Optional | cannot be null | [Messlokation](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                                                               |
| [energierichtung](#energierichtung)                                 | `string`  | Optional | cannot be null | [Messlokation](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")                                                    |
| [netzebenemessung](#netzebenemessung)                               | `string`  | Optional | cannot be null | [Messlokation](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/netzebenemessung")                                                               |
| [messgebietNr](#messgebietnr)                                       | `string`  | Optional | cannot be null | [Messlokation](messlokation-properties-messgebietnr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/messgebietNr")                                       |
| [grundzustaendigerMSBCodeNr](#grundzustaendigermsbcodenr)           | `string`  | Optional | cannot be null | [Messlokation](messlokation-properties-grundzustaendigermsbcodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/grundzustaendigerMSBCodeNr")           |
| [messadresse](#messadresse)                                         | `object`  | Optional | cannot be null | [Messlokation](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/messadresse")                                                                         |
| [bilanzierungsmethode](#bilanzierungsmethode)                       | `string`  | Optional | cannot be null | [Messlokation](bilanzierungsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bilanzierungsmethode.schema.json#/properties/bilanzierungsmethode")                                     |
| [abrechnungmessstellenbetriebnna](#abrechnungmessstellenbetriebnna) | `boolean` | Optional | cannot be null | [Messlokation](messlokation-properties-abrechnungmessstellenbetriebnna.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/abrechnungmessstellenbetriebnna") |
| [gasqualitaet](#gasqualitaet)                                       | `string`  | Optional | cannot be null | [Messlokation](gasqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gasqualitaet.schema.json#/properties/gasqualitaet")                                                             |
| [verlustfaktor](#verlustfaktor)                                     | `number`  | Optional | cannot be null | [Messlokation](messlokation-properties-verlustfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/verlustfaktor")                                     |
| [betriebszustand](#betriebszustand)                                 | `string`  | Optional | cannot be null | [Messlokation](betriebszustand.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Betriebszustand.schema.json#/properties/betriebszustand")                                                    |
| [ablesekartenempfaenger](#ablesekartenempfaenger)                   | `object`  | Optional | cannot be null | [Messlokation](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/ablesekartenempfaenger")                                           |
| [referenzMarktlokationsId](#referenzmarktlokationsid)               | `string`  | Optional | cannot be null | [Messlokation](messlokation-properties-referenzmarktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/referenzMarktlokationsId")               |
| [verwendungsumfang](#verwendungsumfang)                             | `string`  | Optional | cannot be null | [Messlokation](verwendungsumfang.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verwendungsumfang.schema.json#/properties/verwendungsumfang")                                              |
| [zukuenftigerMeldepunkt](#zukuenftigermeldepunkt)                   | `boolean` | Optional | cannot be null | [Messlokation](messlokation-properties-zukuenftigermeldepunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/zukuenftigerMeldepunkt")                   |
| [lokationszuordnung](#lokationszuordnung)                           | `string`  | Optional | cannot be null | [Messlokation](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")                                           |
| [beteiligterMarktpartner](#beteiligtermarktpartner)                 | `object`  | Optional | cannot be null | [Messlokation](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/beteiligterMarktpartner")                                              |
| [geraete](#geraete)                                                 | `array`   | Optional | cannot be null | [Messlokation](messlokation-properties-geraete.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/geraete")                                                 |
| [messdienstleistung](#messdienstleistung)                           | `array`   | Optional | cannot be null | [Messlokation](messlokation-properties-messdienstleistung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/messdienstleistung")                           |
| [messlokationszaehler](#messlokationszaehler)                       | `array`   | Optional | cannot be null | [Messlokation](messlokation-properties-messlokationszaehler.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/messlokationszaehler")                       |
| [zaehlwerke](#zaehlwerke)                                           | `array`   | Optional | cannot be null | [Messlokation](messlokation-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/zaehlwerke")                                           |
| [marktrollen](#marktrollen)                                         | `array`   | Optional | cannot be null | [Messlokation](messlokation-properties-marktrollen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/marktrollen")                                         |
| [datenqualitaet](#datenqualitaet)                                   | `string`  | Optional | cannot be null | [Messlokation](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                                       |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum)                       | `object`  | Optional | cannot be null | [Messlokation](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                                              |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Messlokation](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"MESSLOKATION"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## messlokationsId

Die Messlokations-Identifikation. Das ist die frühere Zählpunktbezeichnung,
z.B. DE 47108151234567

`messlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-messlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/messlokationsId")

### messlokationsId Type

`string`

## sparte

Strom oder Gas.

`sparte`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [Messlokation](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

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

## energierichtung



`energierichtung`

*   is optional

*   Type: `string` ([Energierichtung](energierichtung.md))

*   cannot be null

*   defined in: [Messlokation](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")

### energierichtung Type

`string` ([Energierichtung](energierichtung.md))

### energierichtung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"AUSSP"` |             |
| `"EINSP"` |             |

## netzebenemessung



`netzebenemessung`

*   is optional

*   Type: `string` ([Netzebene](netzebene.md))

*   cannot be null

*   defined in: [Messlokation](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/netzebenemessung")

### netzebenemessung Type

`string` ([Netzebene](netzebene.md))

### netzebenemessung Constraints

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

## messgebietNr

Die Nummer des Messgebietes in der ene't-Datenbank.

`messgebietNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-messgebietnr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/messgebietNr")

### messgebietNr Type

`string`

## grundzustaendigerMSBCodeNr

Codenummer des grundzuständigen Messstellenbetreibers, der für diese
Messlokation zuständig ist.( Dieser ist immer dann Messstellenbetreiber, wenn
kein anderer MSB die Einrichtungen an der Messlokation betreibt.)

`grundzustaendigerMSBCodeNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-grundzustaendigermsbcodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/grundzustaendigerMSBCodeNr")

### grundzustaendigerMSBCodeNr Type

`string`

## messadresse

Die Adresse, an der die Messeinrichtungen zu finden sind.( Nur angeben, wenn
diese von der Adresse der Marktlokation abweicht.)
Achtung: Es darf immer nur eine Art der Ortsangabe vorhanden sein (entweder
eine Adresse oder eine GeoKoordinate oder eine Katasteradresse.

`messadresse`

*   is optional

*   Type: `object` ([Adresse](adresse.md))

*   cannot be null

*   defined in: [Messlokation](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/messadresse")

### messadresse Type

`object` ([Adresse](adresse.md))

## bilanzierungsmethode

Bilanzierungsmethode

`bilanzierungsmethode`

*   is optional

*   Type: `string` ([Bilanzierungsmethode](bilanzierungsmethode.md))

*   cannot be null

*   defined in: [Messlokation](bilanzierungsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bilanzierungsmethode.schema.json#/properties/bilanzierungsmethode")

### bilanzierungsmethode Type

`string` ([Bilanzierungsmethode](bilanzierungsmethode.md))

### bilanzierungsmethode Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"RLM"`           |             |
| `"SLP"`           |             |
| `"TLP_GEMEINSAM"` |             |
| `"TLP_GETRENNT"`  |             |
| `"PAUSCHAL"`      |             |
| `"IMS"`           |             |

## abrechnungmessstellenbetriebnna

Dieser Wert ist true, falls die Abrechnungs des Messstellenbetriebs die Netznutzungsabrechnung enthält. false
andernfalls

`abrechnungmessstellenbetriebnna`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-abrechnungmessstellenbetriebnna.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/abrechnungmessstellenbetriebnna")

### abrechnungmessstellenbetriebnna Type

`boolean`

## gasqualitaet

gasqualitaet für EDIFACT mapping

`gasqualitaet`

*   is optional

*   Type: `string` ([Gasqualitaet](gasqualitaet.md))

*   cannot be null

*   defined in: [Messlokation](gasqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gasqualitaet.schema.json#/properties/gasqualitaet")

### gasqualitaet Type

`string` ([Gasqualitaet](gasqualitaet.md))

### gasqualitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"H_GAS"` |             |
| `"L_GAS"` |             |

## verlustfaktor

verlustfaktor für EDIFACT mapping

`verlustfaktor`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-verlustfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/verlustfaktor")

### verlustfaktor Type

`number`

### verlustfaktor Constraints

**unknown format**: the value of this string must follow the format: `float`

## betriebszustand



`betriebszustand`

*   is optional

*   Type: `string` ([Betriebszustand](betriebszustand.md))

*   cannot be null

*   defined in: [Messlokation](betriebszustand.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Betriebszustand.schema.json#/properties/betriebszustand")

### betriebszustand Type

`string` ([Betriebszustand](betriebszustand.md))

### betriebszustand Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                         | Explanation |
| :---------------------------- | :---------- |
| `"GESPERRT_NICHT_ENTSPERREN"` |             |
| `"GESPERRT"`                  |             |
| `"REGELBETRIEB"`              |             |

## ablesekartenempfaenger



`ablesekartenempfaenger`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Messlokation](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/ablesekartenempfaenger")

### ablesekartenempfaenger Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## referenzMarktlokationsId



`referenzMarktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-referenzmarktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/referenzMarktlokationsId")

### referenzMarktlokationsId Type

`string`

## verwendungsumfang



`verwendungsumfang`

*   is optional

*   Type: `string` ([Verwendungsumfang](verwendungsumfang.md))

*   cannot be null

*   defined in: [Messlokation](verwendungsumfang.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verwendungsumfang.schema.json#/properties/verwendungsumfang")

### verwendungsumfang Type

`string` ([Verwendungsumfang](verwendungsumfang.md))

### verwendungsumfang Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                 | Explanation |
| :------------------------------------ | :---------- |
| `"MESSLOKATION_PROZESSUAL_BEHANDELT"` |             |
| `"MESSLOKATION_LOKATIONSBUENDEL"`     |             |

## zukuenftigerMeldepunkt



`zukuenftigerMeldepunkt`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-zukuenftigermeldepunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/zukuenftigerMeldepunkt")

### zukuenftigerMeldepunkt Type

`boolean`

## lokationszuordnung



`lokationszuordnung`

*   is optional

*   Type: `string` ([Lokationszuordnung](lokationszuordnung.md))

*   cannot be null

*   defined in: [Messlokation](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")

### lokationszuordnung Type

`string` ([Lokationszuordnung](lokationszuordnung.md))

### lokationszuordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"UNVERAENDERT"` |             |
| `"BEGINNT"`      |             |
| `"ENDET"`        |             |

## beteiligterMarktpartner



`beteiligterMarktpartner`

*   is optional

*   Type: `object` ([Marktteilnehmer](marktteilnehmer.md))

*   cannot be null

*   defined in: [Messlokation](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/beteiligterMarktpartner")

### beteiligterMarktpartner Type

`object` ([Marktteilnehmer](marktteilnehmer.md))

## geraete

Liste der Geräte, die zu diesem Zähler gehören.

`geraete`

*   is optional

*   Type: `object[]` ([Geraet](geraet.md))

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-geraete.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/geraete")

### geraete Type

`object[]` ([Geraet](geraet.md))

## messdienstleistung

Liste der Messdienstleistungen, die zu dieser Messstelle gehört.

`messdienstleistung`

*   is optional

*   Type: `object[]` ([Dienstleistung](dienstleistung.md))

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-messdienstleistung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/messdienstleistung")

### messdienstleistung Type

`object[]` ([Dienstleistung](dienstleistung.md))

## messlokationszaehler

Zähler, die zu dieser Messlokation gehören. Details

`messlokationszaehler`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-messlokationszaehler.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/messlokationszaehler")

### messlokationszaehler Type

`string[]`

## zaehlwerke

Die Zählwerke des Zählers.

`zaehlwerke`

*   is optional

*   Type: `object[]` ([Zaehlwerk](zaehlwerk.md))

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/zaehlwerke")

### zaehlwerke Type

`object[]` ([Zaehlwerk](zaehlwerk.md))

## marktrollen

marktrollen für EDIFACT mapping

`marktrollen`

*   is optional

*   Type: `object[]` ([Marktteilnehmer](marktteilnehmer.md))

*   cannot be null

*   defined in: [Messlokation](messlokation-properties-marktrollen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Messlokation.schema.json#/properties/marktrollen")

### marktrollen Type

`object[]` ([Marktteilnehmer](marktteilnehmer.md))

## datenqualitaet



`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Messlokation](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

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

*   defined in: [Messlokation](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))
