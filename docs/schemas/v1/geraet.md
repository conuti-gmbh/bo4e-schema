## Geraet Type

`object` ([Geraet](geraet.md))

# Geraet Properties

| Property                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                  |
| :---------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [geraetetyp](#geraetetyp)                       | `string` | Optional | cannot be null | [Geraet](geraetetyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Geraetetyp.schema.json#/properties/geraetetyp")                                    |
| [bezeichnung](#bezeichnung)                     | `string` | Optional | cannot be null | [Geraet](geraet-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraet.schema.json#/properties/bezeichnung")                     |
| [geraetenummer](#geraetenummer)                 | `string` | Optional | cannot be null | [Geraet](geraet-properties-geraetenummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraet.schema.json#/properties/geraetenummer")                 |
| [geraetereferenz](#geraetereferenz)             | `string` | Optional | cannot be null | [Geraet](geraet-properties-geraetereferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraet.schema.json#/properties/geraetereferenz")             |
| [geraeteeigenschaften](#geraeteeigenschaften)   | `object` | Optional | cannot be null | [Geraet](geraeteeigenschaften.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraeteeigenschaften.schema.json#/properties/geraeteeigenschaften")       |
| [volumenerfassung](#volumenerfassung)           | `string` | Optional | cannot be null | [Geraet](volumenerfassung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Volumenerfassung.schema.json#/properties/volumenerfassung")                  |
| [weitereGeraetenummern](#weiteregeraetenummern) | `array`  | Optional | cannot be null | [Geraet](geraet-properties-weiteregeraetenummern.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraet.schema.json#/properties/weitereGeraetenummern") |

## geraetetyp



`geraetetyp`

*   is optional

*   Type: `string` ([Geraetetyp](geraetetyp.md))

*   cannot be null

*   defined in: [Geraet](geraetetyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Geraetetyp.schema.json#/properties/geraetetyp")

### geraetetyp Type

`string` ([Geraetetyp](geraetetyp.md))

### geraetetyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                               | Explanation |
| :---------------------------------- | :---------- |
| `"WECHSELSTROMZAEHLER"`             |             |
| `"DREHSTROMZAEHLER"`                |             |
| `"ZWEIRICHTUNGSZAEHLER"`            |             |
| `"RLM_ZAEHLER"`                     |             |
| `"IMS_ZAEHLER"`                     |             |
| `"BALGENGASZAEHLER"`                |             |
| `"MAXIMUMZAEHLER"`                  |             |
| `"MULTIPLEXANLAGE"`                 |             |
| `"PAUSCHALANLAGE"`                  |             |
| `"VERSTAERKERANLAGE"`               |             |
| `"SUMMATIONSGERAET"`                |             |
| `"IMPULSGEBER"`                     |             |
| `"EDL_21_ZAEHLERAUFSATZ"`           |             |
| `"VIER_QUADRANTEN_LASTGANGZAEHLER"` |             |
| `"MENGENUMWERTER"`                  |             |
| `"STROMWANDLER"`                    |             |
| `"SPANNUNGSWANDLER"`                |             |
| `"DATENLOGGER"`                     |             |
| `"KOMMUNIKATIONSANSCHLUSS"`         |             |
| `"MODEM"`                           |             |
| `"TELEKOMMUNIKATIONSEINRICHTUNG"`   |             |
| `"KOMMUNIKATIONSEINRICHTUNG"`       |             |
| `"DREHKOLBENGASZAEHLER"`            |             |
| `"TURBINENRADGASZAEHLER"`           |             |
| `"ULTRASCHALLZAEHLER"`              |             |
| `"WIRBELGASZAEHLER"`                |             |
| `"MODERNE_MESSEINRICHTUNG"`         |             |
| `"ELEKTRONISCHER_HAUSHALTSZAEHLER"` |             |
| `"STEUEREINRICHTUNG"`               |             |
| `"TECHNISCHESTEUEREINRICHTUNG"`     |             |
| `"TARIFSCHALTGERAET"`               |             |
| `"RUNDSTEUEREMPFAENGER"`            |             |
| `"OPTIONALE_ZUS_ZAEHLEINRICHTUNG"`  |             |
| `"MESSWANDLERSATZ_IMS_MME"`         |             |
| `"KOMBIMESSWANDLER_IMS_MME"`        |             |
| `"TARIFSCHALTGERAET_IMS_MME"`       |             |
| `"RUNDSTEUEREMPFAENGER_IMS_MME"`    |             |
| `"TEMPERATUR_KOMPENSATION"`         |             |
| `"HOECHSTBELASTUNGS_ANZEIGER"`      |             |
| `"SONSTIGES_GERAET"`                |             |
| `"SMARTMETERGATEWAY"`               |             |
| `"STEUERBOX"`                       |             |
| `"BLOCKSTROMWANDLER"`               |             |
| `"KOMBIMESSWANDLER"`                |             |
| `"MODEM_GSM"`                       |             |
| `"ETHERNET_KOM"`                    |             |
| `"PLC_COM"`                         |             |
| `"MODEM_FESTNETZ"`                  |             |
| `"DSL_KOM"`                         |             |
| `"LTE_KOM"`                         |             |
| `"DICHTEMENGENUMWERTER"`            |             |
| `"TEMPERATURMENGENUMWERTER"`        |             |
| `"ZUSTANDSMENGENUMWERTER"`          |             |
| `"MESSDATENREGISTRIERGERAET"`       |             |
| `"WANDLER"`                         |             |

## bezeichnung



`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geraet](geraet-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraet.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`

## geraetenummer



`geraetenummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geraet](geraet-properties-geraetenummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraet.schema.json#/properties/geraetenummer")

### geraetenummer Type

`string`

## geraetereferenz



`geraetereferenz`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geraet](geraet-properties-geraetereferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraet.schema.json#/properties/geraetereferenz")

### geraetereferenz Type

`string`

## geraeteeigenschaften



`geraeteeigenschaften`

*   is optional

*   Type: `object` ([Geraeteeigenschaften](geraeteeigenschaften.md))

*   cannot be null

*   defined in: [Geraet](geraeteeigenschaften.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraeteeigenschaften.schema.json#/properties/geraeteeigenschaften")

### geraeteeigenschaften Type

`object` ([Geraeteeigenschaften](geraeteeigenschaften.md))

## volumenerfassung



`volumenerfassung`

*   is optional

*   Type: `string` ([Volumenerfassung](volumenerfassung.md))

*   cannot be null

*   defined in: [Geraet](volumenerfassung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Volumenerfassung.schema.json#/properties/volumenerfassung")

### volumenerfassung Type

`string` ([Volumenerfassung](volumenerfassung.md))

### volumenerfassung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                            | Explanation |
| :------------------------------- | :---------- |
| `"HOCHFREQUENZSONDE"`            |             |
| `"KENNLINIENKORREKTUR"`          |             |
| `"SCHLEICHMENGENUNTERDRUECKUNG"` |             |

## weitereGeraetenummern



`weitereGeraetenummern`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Geraet](geraet-properties-weiteregeraetenummern.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geraet.schema.json#/properties/weitereGeraetenummern")

### weitereGeraetenummern Type

`string[]`
