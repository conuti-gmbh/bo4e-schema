## Dienstleistung Type

`object` ([Dienstleistung](dienstleistung.md))

# Dienstleistung Properties

| Property                                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                      |
| :---------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [dienstleistungstyp](#dienstleistungstyp) | `string` | Optional | cannot be null | [Dienstleistung](dienstleistungstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Dienstleistungstyp.schema.json#/properties/dienstleistungstyp")        |
| [bezeichnung](#bezeichnung)               | `string` | Optional | cannot be null | [Dienstleistung](dienstleistung-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Dienstleistung.schema.json#/properties/bezeichnung") |

## dienstleistungstyp

Eindeutige Nummer der Dienstleistung. Details Dienstleistungstyp

`dienstleistungstyp`

*   is optional

*   Type: `string` ([Dienstleistungstyp](dienstleistungstyp.md))

*   cannot be null

*   defined in: [Dienstleistung](dienstleistungstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Dienstleistungstyp.schema.json#/properties/dienstleistungstyp")

### dienstleistungstyp Type

`string` ([Dienstleistungstyp](dienstleistungstyp.md))

### dienstleistungstyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                           | Explanation |
| :---------------------------------------------- | :---------- |
| `"DATENBEREITSTELLUNG_TAEGLICH"`                |             |
| `"DATENBEREITSTELLUNG_WOECHENTLICH"`            |             |
| `"DATENBEREITSTELLUNG_MONATLICH"`               |             |
| `"DATENBEREITSTELLUNG_JAEHRLICH"`               |             |
| `"DATENBEREITSTELLUNG_HISTORISCHE_LG"`          |             |
| `"DATENBEREITSTELLUNG_STUENDLICH"`              |             |
| `"DATENBEREITSTELLUNG_VIERTELJAEHRLICH"`        |             |
| `"DATENBEREITSTELLUNG_HALBJAEHRLICH"`           |             |
| `"DATENBEREITSTELLUNG_MONATLICH_ZUSAETZLICH"`   |             |
| `"DATENBEREITSTELLUNG_EINMALIG"`                |             |
| `"AUSLESUNG_2X_TAEGLICH_FERNAUSLESUNG"`         |             |
| `"AUSLESUNG_TAEGLICH_FERNAUSLESUNG"`            |             |
| `"AUSLESUNG_LGK_MANUELL_MSB"`                   |             |
| `"AUSLESUNG_MONATLICH_SLP_FERNAUSLESUNG"`       |             |
| `"AUSLESUNG_JAEHRLICH_SLP_FERNAUSLESUNG"`       |             |
| `"AUSLESUNG_MDE_SLP"`                           |             |
| `"ABLESUNG_MONATLICH_SLP"`                      |             |
| `"ABLESUNG_VIERTELJAEHRLICH_SLP"`               |             |
| `"ABLESUNG_HALBJAEHRLICH_SLP"`                  |             |
| `"ABLESUNG_JAEHRLICH_SLP"`                      |             |
| `"AUSLESUNG_SLP_FERNAUSLESUNG"`                 |             |
| `"ABLESUNG_SLP_ZUSAETZLICH_MSB"`                |             |
| `"ABLESUNG_SLP_ZUSAETZLICH_KUNDE"`              |             |
| `"AUSLESUNG_LGK_FERNAUSLESUNG_ZUSAETZLICH_MSB"` |             |
| `"AUSLESUNG_MOATLICH_FERNAUSLESUNG"`            |             |
| `"AUSLESUNG_STUENDLICH_FERNAUSLESUNG"`          |             |
| `"ABLESUNG_MONATLICH_LGK"`                      |             |
| `"AUSLESUNG_TEMERATURMENGENUMWERTER"`           |             |
| `"AUSLESUNG_ZUSTANDSMENGENUMWERTER"`            |             |
| `"AUSLESUNG_SYSTEMMENGENUMWERTER"`              |             |
| `"AUSLESUNG_VORGANG_SLP"`                       |             |
| `"AUSLESUUNG_KOMPAKTMENGENUMWERTER"`            |             |
| `"AUSLESUNG_MDE_LGK"`                           |             |
| `"SPERRUNG_SLP"`                                |             |
| `"ENTSPERRUNG_SLP"`                             |             |
| `"SPERRUNG_RLM"`                                |             |
| `"ENTSPERRUNG_RLM"`                             |             |
| `"MAHNKOSTEN"`                                  |             |
| `"INKASSOKOSTEN"`                               |             |

## bezeichnung

Bezeichnung der Dienstleistung.

`bezeichnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Dienstleistung](dienstleistung-properties-bezeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Dienstleistung.schema.json#/properties/bezeichnung")

### bezeichnung Type

`string`
