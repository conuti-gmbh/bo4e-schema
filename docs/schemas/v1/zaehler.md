## Zaehler Type

`object` ([Zaehler](zaehler.md))

# Zaehler Properties

| Property                                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                       |
| :-------------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                     | `string` | Required | cannot be null | [Zaehler](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                       |
| [versionStruktur](#versionstruktur)                 | `string` | Required | cannot be null | [Zaehler](zaehler-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/versionStruktur")                |
| [zaehlernummer](#zaehlernummer)                     | `string` | Optional | cannot be null | [Zaehler](zaehler-properties-zaehlernummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/zaehlernummer")                    |
| [sparte](#sparte)                                   | `string` | Optional | cannot be null | [Zaehler](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                                    |
| [zaehlerauspraegung](#zaehlerauspraegung)           | `string` | Optional | cannot be null | [Zaehler](zaehlerauspraegung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zaehlerauspraegung.schema.json#/properties/zaehlerauspraegung")                |
| [zaehlertyp](#zaehlertyp)                           | `string` | Optional | cannot be null | [Zaehler](zaehlertyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zaehlertyp.schema.json#/properties/zaehlertyp")                                        |
| [tarifart](#tarifart)                               | `string` | Optional | cannot be null | [Zaehler](tarifart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tarifart.schema.json#/properties/tarifart")                                              |
| [zaehlerkonstante](#zaehlerkonstante)               | `number` | Optional | cannot be null | [Zaehler](zaehler-properties-zaehlerkonstante.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/zaehlerkonstante")              |
| [eichungBis](#eichungbis)                           | `string` | Optional | cannot be null | [Zaehler](zaehler-properties-eichungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/eichungBis")                          |
| [zaehlerhersteller](#zaehlerhersteller)             | `object` | Optional | cannot be null | [Zaehler](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/zaehlerhersteller")                     |
| [gateway](#gateway)                                 | `string` | Optional | cannot be null | [Zaehler](zaehler-properties-gateway.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/gateway")                                |
| [fernschaltung](#fernschaltung)                     | `string` | Optional | cannot be null | [Zaehler](fernschaltung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fernschaltung.schema.json#/properties/fernschaltung")                               |
| [messwerterfassung](#messwerterfassung)             | `string` | Optional | cannot be null | [Zaehler](messwerterfassung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Messwerterfassung.schema.json#/properties/messwerterfassung")                   |
| [zaehlertypspezifikation](#zaehlertypspezifikation) | `string` | Optional | cannot be null | [Zaehler](zaehlertypspezifikation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ZaehlertypSpezifikation.schema.json#/properties/zaehlertypspezifikation") |
| [befestigungsart](#befestigungsart)                 | `string` | Optional | cannot be null | [Zaehler](befestigungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Befestigungsart.schema.json#/properties/befestigungsart")                         |
| [zaehlergroesse](#zaehlergroesse)                   | `string` | Optional | cannot be null | [Zaehler](geraetemerkmal.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Geraetemerkmal.schema.json#/properties/zaehlergroesse")                            |
| [mengenumwertertyp](#mengenumwertertyp)             | `string` | Optional | cannot be null | [Zaehler](mengenumwertertyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengenumwertertyp.schema.json#/properties/mengenumwertertyp")                   |
| [volumenerfassung](#volumenerfassung)               | `string` | Optional | cannot be null | [Zaehler](volumenerfassung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Volumenerfassung.schema.json#/properties/volumenerfassung")                      |
| [serialnummer](#serialnummer)                       | `string` | Optional | cannot be null | [Zaehler](zaehler-properties-serialnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/serialnummer")                      |
| [geraetemerkmal](#geraetemerkmal)                   | `string` | Optional | cannot be null | [Zaehler](geraetemerkmal.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Geraetemerkmal.schema.json#/properties/geraetemerkmal")                            |
| [herstellungsdatum](#herstellungsdatum)             | `string` | Optional | cannot be null | [Zaehler](zaehler-properties-herstellungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/herstellungsdatum")            |
| [baujahr](#baujahr)                                 | `string` | Optional | cannot be null | [Zaehler](zaehler-properties-baujahr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/baujahr")                                |
| [messlokationsId](#messlokationsid)                 | `string` | Optional | cannot be null | [Zaehler](zaehler-properties-messlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/messlokationsId")                |
| [marktlokationsId](#marktlokationsid)               | `string` | Optional | cannot be null | [Zaehler](zaehler-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/marktlokationsId")              |
| [geraete](#geraete)                                 | `array`  | Optional | cannot be null | [Zaehler](zaehler-properties-geraete.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/geraete")                                |
| [zaehlwerke](#zaehlwerke)                           | `array`  | Optional | cannot be null | [Zaehler](zaehler-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/zaehlwerke")                          |
| [datenqualitaet](#datenqualitaet)                   | `string` | Optional | cannot be null | [Zaehler](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                            |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum)       | `object` | Optional | cannot be null | [Zaehler](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                   |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Zaehler](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"ZAEHLER"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## zaehlernummer



`zaehlernummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-zaehlernummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/zaehlernummer")

### zaehlernummer Type

`string`

## sparte



`sparte`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [Zaehler](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

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

## zaehlerauspraegung



`zaehlerauspraegung`

*   is optional

*   Type: `string` ([Zaehlerauspraegung](zaehlerauspraegung.md))

*   cannot be null

*   defined in: [Zaehler](zaehlerauspraegung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zaehlerauspraegung.schema.json#/properties/zaehlerauspraegung")

### zaehlerauspraegung Type

`string` ([Zaehlerauspraegung](zaehlerauspraegung.md))

### zaehlerauspraegung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"EINRICHTUNGSZAEHLER"`  |             |
| `"ZWEIRICHTUNGSZAEHLER"` |             |

## zaehlertyp



`zaehlertyp`

*   is optional

*   Type: `string` ([Zaehlertyp](zaehlertyp.md))

*   cannot be null

*   defined in: [Zaehler](zaehlertyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zaehlertyp.schema.json#/properties/zaehlertyp")

### zaehlertyp Type

`string` ([Zaehlertyp](zaehlertyp.md))

### zaehlertyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                              | Explanation |
| :--------------------------------- | :---------- |
| `"DREHSTROMZAEHLER"`               |             |
| `"BALGENGASZAEHLER"`               |             |
| `"DREHKOLBENZAEHLER"`              |             |
| `"SMARTMETER"`                     |             |
| `"LEISTUNGSZAEHLER"`               |             |
| `"MAXIMUMZAEHLER"`                 |             |
| `"TURBINENRADGASZAEHLER"`          |             |
| `"ULTRASCHALLGASZAEHLER"`          |             |
| `"WECHSELSTROMZAEHLER"`            |             |
| `"WIRBELGASZAEHLER"`               |             |
| `"MESSDATENREGISTRIERGERAET"`      |             |
| `"ELEKTRONISCHERHAUSHALTSZAEHLER"` |             |
| `"SONDERAUSSTATTUNG"`              |             |
| `"WASSERZAEHLER"`                  |             |
| `"MODERNEMESSEINRICHTUNG"`         |             |

## tarifart



`tarifart`

*   is optional

*   Type: `string` ([Tarifart](tarifart.md))

*   cannot be null

*   defined in: [Zaehler](tarifart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Tarifart.schema.json#/properties/tarifart")

### tarifart Type

`string` ([Tarifart](tarifart.md))

### tarifart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                 | Explanation |
| :-------------------- | :---------- |
| `"EINTARIF"`          |             |
| `"ZWEITARIF"`         |             |
| `"MEHRTARIF"`         |             |
| `"SMART_METER"`       |             |
| `"LEISTUNGSGEMESSEN"` |             |

## zaehlerkonstante



`zaehlerkonstante`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-zaehlerkonstante.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/zaehlerkonstante")

### zaehlerkonstante Type

`number`

### zaehlerkonstante Constraints

**unknown format**: the value of this string must follow the format: `float`

## eichungBis



`eichungBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-eichungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/eichungBis")

### eichungBis Type

`string`

### eichungBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## zaehlerhersteller



`zaehlerhersteller`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Zaehler](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/zaehlerhersteller")

### zaehlerhersteller Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## gateway



`gateway`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-gateway.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/gateway")

### gateway Type

`string`

## fernschaltung



`fernschaltung`

*   is optional

*   Type: `string` ([Fernschaltung](fernschaltung.md))

*   cannot be null

*   defined in: [Zaehler](fernschaltung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fernschaltung.schema.json#/properties/fernschaltung")

### fernschaltung Type

`string` ([Fernschaltung](fernschaltung.md))

### fernschaltung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"VORHANDEN"`       |             |
| `"NICHT_VORHANDEN"` |             |

## messwerterfassung



`messwerterfassung`

*   is optional

*   Type: `string` ([Messwerterfassung](messwerterfassung.md))

*   cannot be null

*   defined in: [Zaehler](messwerterfassung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Messwerterfassung.schema.json#/properties/messwerterfassung")

### messwerterfassung Type

`string` ([Messwerterfassung](messwerterfassung.md))

### messwerterfassung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                   | Explanation |
| :---------------------- | :---------- |
| `"FERNAUSLESBAR"`       |             |
| `"MANUELL_AUSGELESENE"` |             |

## zaehlertypspezifikation



`zaehlertypspezifikation`

*   is optional

*   Type: `string` ([ZaehlertypSpezifikation](zaehlertypspezifikation.md))

*   cannot be null

*   defined in: [Zaehler](zaehlertypspezifikation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ZaehlertypSpezifikation.schema.json#/properties/zaehlertypspezifikation")

### zaehlertypspezifikation Type

`string` ([ZaehlertypSpezifikation](zaehlertypspezifikation.md))

### zaehlertypspezifikation Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"EDL40"`         |             |
| `"EDL21"`         |             |
| `"SONSTIGER_EHZ"` |             |
| `"MME_STANDARD"`  |             |
| `"MME_MEDA"`      |             |

## befestigungsart



`befestigungsart`

*   is optional

*   Type: `string` ([Befestigungsart](befestigungsart.md))

*   cannot be null

*   defined in: [Zaehler](befestigungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Befestigungsart.schema.json#/properties/befestigungsart")

### befestigungsart Type

`string` ([Befestigungsart](befestigungsart.md))

### befestigungsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"STECKTECHNIK"` |             |
| `"DREIPUNKT"`    |             |
| `"HUTSCHIENE"`   |             |
| `"EINSTUTZEN"`   |             |
| `"ZWEISTUTZEN"`  |             |

## zaehlergroesse



`zaehlergroesse`

*   is optional

*   Type: `string` ([Geraetemerkmal](geraetemerkmal.md))

*   cannot be null

*   defined in: [Zaehler](geraetemerkmal.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Geraetemerkmal.schema.json#/properties/zaehlergroesse")

### zaehlergroesse Type

`string` ([Geraetemerkmal](geraetemerkmal.md))

### zaehlergroesse Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                        | Explanation |
| :--------------------------- | :---------- |
| `"EINTARIF"`                 |             |
| `"ZWEITARIF"`                |             |
| `"MEHRTARIF"`                |             |
| `"GAS_G2P5"`                 |             |
| `"GAS_G4"`                   |             |
| `"GAS_G6"`                   |             |
| `"GAS_G10"`                  |             |
| `"GAS_G16"`                  |             |
| `"GAS_G25"`                  |             |
| `"GAS_G40"`                  |             |
| `"GAS_G65"`                  |             |
| `"GAS_G100"`                 |             |
| `"GAS_G160"`                 |             |
| `"GAS_G250"`                 |             |
| `"GAS_G350"`                 |             |
| `"GAS_G400"`                 |             |
| `"GAS_G4000"`                |             |
| `"GAS_G650"`                 |             |
| `"GAS_G6500"`                |             |
| `"GAS_G1000"`                |             |
| `"GAS_G10000"`               |             |
| `"GAS_G12500"`               |             |
| `"GAS_G1600"`                |             |
| `"GAS_G16000"`               |             |
| `"GAS_G2500"`                |             |
| `"IMPULSGEBER_G4_G100"`      |             |
| `"IMPULSGEBER_G100"`         |             |
| `"MODEM_GSM"`                |             |
| `"MODEM_GPRS"`               |             |
| `"MODEM_FUNK"`               |             |
| `"MODEM_GSM_O_LG"`           |             |
| `"MODEM_GSM_M_LG"`           |             |
| `"MODEM_FESTNETZ"`           |             |
| `"MODEM_GPRS_M_LG"`          |             |
| `"PLC_COM"`                  |             |
| `"ETHERNET_KOM"`             |             |
| `"DSL_KOM"`                  |             |
| `"LTE_KOM"`                  |             |
| `"RUNDSTEUEREMPFAENGER"`     |             |
| `"TARIFSCHALTGERAET"`        |             |
| `"ZUSTANDS_MU"`              |             |
| `"TEMPERATUR_MU"`            |             |
| `"KOMPAKT_MU"`               |             |
| `"SYSTEM_MU"`                |             |
| `"UNBESTIMMT"`               |             |
| `"WASSER_MWZW"`              |             |
| `"WASSER_WZWW"`              |             |
| `"WASSER_WZ01"`              |             |
| `"WASSER_WZ02"`              |             |
| `"WASSER_WZ03"`              |             |
| `"WASSER_WZ04"`              |             |
| `"WASSER_WZ05"`              |             |
| `"WASSER_WZ06"`              |             |
| `"WASSER_WZ07"`              |             |
| `"WASSER_WZ08"`              |             |
| `"WASSER_WZ09"`              |             |
| `"WASSER_WZ10"`              |             |
| `"WASSER_VWZ04"`             |             |
| `"WASSER_VWZ05"`             |             |
| `"WASSER_VWZ06"`             |             |
| `"WASSER_VWZ07"`             |             |
| `"WASSER_VWZ10"`             |             |
| `"DICHTEMENGENUMWERTER"`     |             |
| `"TEMPERATURMENGENUMWERTER"` |             |
| `"ZUSTANDSMENGENUMWERTER"`   |             |
| `"BLOCKSTROMWANDLER"`        |             |
| `"MESSWANDLERSATZ_IMS_MME"`  |             |
| `"KOMBIMESSWANDLER"`         |             |
| `"SPANNUNGSWANDLER"`         |             |

## mengenumwertertyp



`mengenumwertertyp`

*   is optional

*   Type: `string` ([Mengenumwertertyp](mengenumwertertyp.md))

*   cannot be null

*   defined in: [Zaehler](mengenumwertertyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Mengenumwertertyp.schema.json#/properties/mengenumwertertyp")

### mengenumwertertyp Type

`string` ([Mengenumwertertyp](mengenumwertertyp.md))

### mengenumwertertyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                        | Explanation |
| :--------------------------- | :---------- |
| `"DICHTEMENGENUMWERTER"`     |             |
| `"TEMPERATURMENGENUMWERTER"` |             |
| `"ZUSTANDSMENGENUMWERTER"`   |             |

## volumenerfassung



`volumenerfassung`

*   is optional

*   Type: `string` ([Volumenerfassung](volumenerfassung.md))

*   cannot be null

*   defined in: [Zaehler](volumenerfassung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Volumenerfassung.schema.json#/properties/volumenerfassung")

### volumenerfassung Type

`string` ([Volumenerfassung](volumenerfassung.md))

### volumenerfassung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                            | Explanation |
| :------------------------------- | :---------- |
| `"HOCHFREQUENZSONDE"`            |             |
| `"KENNLINIENKORREKTUR"`          |             |
| `"SCHLEICHMENGENUNTERDRUECKUNG"` |             |

## serialnummer



`serialnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-serialnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/serialnummer")

### serialnummer Type

`string`

## geraetemerkmal



`geraetemerkmal`

*   is optional

*   Type: `string` ([Geraetemerkmal](geraetemerkmal.md))

*   cannot be null

*   defined in: [Zaehler](geraetemerkmal.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Geraetemerkmal.schema.json#/properties/geraetemerkmal")

### geraetemerkmal Type

`string` ([Geraetemerkmal](geraetemerkmal.md))

### geraetemerkmal Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                        | Explanation |
| :--------------------------- | :---------- |
| `"EINTARIF"`                 |             |
| `"ZWEITARIF"`                |             |
| `"MEHRTARIF"`                |             |
| `"GAS_G2P5"`                 |             |
| `"GAS_G4"`                   |             |
| `"GAS_G6"`                   |             |
| `"GAS_G10"`                  |             |
| `"GAS_G16"`                  |             |
| `"GAS_G25"`                  |             |
| `"GAS_G40"`                  |             |
| `"GAS_G65"`                  |             |
| `"GAS_G100"`                 |             |
| `"GAS_G160"`                 |             |
| `"GAS_G250"`                 |             |
| `"GAS_G350"`                 |             |
| `"GAS_G400"`                 |             |
| `"GAS_G4000"`                |             |
| `"GAS_G650"`                 |             |
| `"GAS_G6500"`                |             |
| `"GAS_G1000"`                |             |
| `"GAS_G10000"`               |             |
| `"GAS_G12500"`               |             |
| `"GAS_G1600"`                |             |
| `"GAS_G16000"`               |             |
| `"GAS_G2500"`                |             |
| `"IMPULSGEBER_G4_G100"`      |             |
| `"IMPULSGEBER_G100"`         |             |
| `"MODEM_GSM"`                |             |
| `"MODEM_GPRS"`               |             |
| `"MODEM_FUNK"`               |             |
| `"MODEM_GSM_O_LG"`           |             |
| `"MODEM_GSM_M_LG"`           |             |
| `"MODEM_FESTNETZ"`           |             |
| `"MODEM_GPRS_M_LG"`          |             |
| `"PLC_COM"`                  |             |
| `"ETHERNET_KOM"`             |             |
| `"DSL_KOM"`                  |             |
| `"LTE_KOM"`                  |             |
| `"RUNDSTEUEREMPFAENGER"`     |             |
| `"TARIFSCHALTGERAET"`        |             |
| `"ZUSTANDS_MU"`              |             |
| `"TEMPERATUR_MU"`            |             |
| `"KOMPAKT_MU"`               |             |
| `"SYSTEM_MU"`                |             |
| `"UNBESTIMMT"`               |             |
| `"WASSER_MWZW"`              |             |
| `"WASSER_WZWW"`              |             |
| `"WASSER_WZ01"`              |             |
| `"WASSER_WZ02"`              |             |
| `"WASSER_WZ03"`              |             |
| `"WASSER_WZ04"`              |             |
| `"WASSER_WZ05"`              |             |
| `"WASSER_WZ06"`              |             |
| `"WASSER_WZ07"`              |             |
| `"WASSER_WZ08"`              |             |
| `"WASSER_WZ09"`              |             |
| `"WASSER_WZ10"`              |             |
| `"WASSER_VWZ04"`             |             |
| `"WASSER_VWZ05"`             |             |
| `"WASSER_VWZ06"`             |             |
| `"WASSER_VWZ07"`             |             |
| `"WASSER_VWZ10"`             |             |
| `"DICHTEMENGENUMWERTER"`     |             |
| `"TEMPERATURMENGENUMWERTER"` |             |
| `"ZUSTANDSMENGENUMWERTER"`   |             |
| `"BLOCKSTROMWANDLER"`        |             |
| `"MESSWANDLERSATZ_IMS_MME"`  |             |
| `"KOMBIMESSWANDLER"`         |             |
| `"SPANNUNGSWANDLER"`         |             |

## herstellungsdatum



`herstellungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-herstellungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/herstellungsdatum")

### herstellungsdatum Type

`string`

### herstellungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## baujahr



> DTM+Z03

`baujahr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-baujahr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/baujahr")

### baujahr Type

`string`

## messlokationsId



`messlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-messlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/messlokationsId")

### messlokationsId Type

`string`

## marktlokationsId



`marktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/marktlokationsId")

### marktlokationsId Type

`string`

## geraete



`geraete`

*   is optional

*   Type: `object[]` ([Geraet](geraet.md))

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-geraete.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/geraete")

### geraete Type

`object[]` ([Geraet](geraet.md))

## zaehlwerke



`zaehlwerke`

*   is optional

*   Type: `object[]` ([Zaehlwerk](zaehlwerk.md))

*   cannot be null

*   defined in: [Zaehler](zaehler-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Zaehler.schema.json#/properties/zaehlwerke")

### zaehlwerke Type

`object[]` ([Zaehlwerk](zaehlwerk.md))

## datenqualitaet



`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Zaehler](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

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

*   defined in: [Zaehler](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))
