## Handelsunstimmigkeitsbegruendung Type

`object` ([Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung.md))

# Handelsunstimmigkeitsbegruendung Properties

| Property                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                            |
| :------------------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [richtigkeit](#richtigkeit)                 | `string` | Optional | cannot be null | [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsrichtigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Handelsunstimmigkeitsrichtigkeit.schema.json#/properties/richtigkeit")                                       |
| [referenzDar](#referenzdar)                 | `string` | Optional | cannot be null | [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-referenzdar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/referenzDar")                 |
| [referenznummer](#referenznummer)           | `string` | Optional | cannot be null | [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-referenznummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/referenznummer")           |
| [bestaetigungDar](#bestaetigungdar)         | `string` | Optional | cannot be null | [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-bestaetigungdar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/bestaetigungDar")         |
| [anerkennungsmeldung](#anerkennungsmeldung) | `string` | Optional | cannot be null | [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-anerkennungsmeldung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/anerkennungsmeldung") |
| [grund](#grund)                             | `string` | Optional | cannot be null | [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Handelsunstimmigkeitsgrund.schema.json#/properties/grund")                                                         |
| [hinweis](#hinweis)                         | `string` | Optional | cannot be null | [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-hinweis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/hinweis")                         |
| [referenzen](#referenzen)                   | `array`  | Optional | can be null    | [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-referenzen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/referenzen")                   |

## richtigkeit

Handelsunstimmigkeitsrichtigkeit

`richtigkeit`

*   is optional

*   Type: `string` ([Handelsunstimmigkeitsrichtigkeit](handelsunstimmigkeitsrichtigkeit.md))

*   cannot be null

*   defined in: [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsrichtigkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Handelsunstimmigkeitsrichtigkeit.schema.json#/properties/richtigkeit")

### richtigkeit Type

`string` ([Handelsunstimmigkeitsrichtigkeit](handelsunstimmigkeitsrichtigkeit.md))

### richtigkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"MSCONS"` |             |
| `"UTILMD"` |             |
| `"INVOIC"` |             |
| `"ORDERS"` |             |
| `"PRICAT"` |             |
| `"IFTSTA"` |             |
| `"ORDCHG"` |             |

## referenzDar

Referenzierte Datenaustauschreferenz

`referenzDar`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-referenzdar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/referenzDar")

### referenzDar Type

`string`

## referenznummer

Referenznummer der Nachricht

`referenznummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-referenznummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/referenznummer")

### referenznummer Type

`string`

## bestaetigungDar

bestätigte Datenaustauschreferenz

`bestaetigungDar`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-bestaetigungdar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/bestaetigungDar")

### bestaetigungDar Type

`string`

## anerkennungsmeldung

Nachrichtennummer aus der Anerkennungsmeldung (APERAK)

`anerkennungsmeldung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-anerkennungsmeldung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/anerkennungsmeldung")

### anerkennungsmeldung Type

`string`

## grund

Handelsunstimmigkeitsgrund

`grund`

*   is optional

*   Type: `string` ([Handelsunstimmigkeitsgrund](handelsunstimmigkeitsgrund.md))

*   cannot be null

*   defined in: [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Handelsunstimmigkeitsgrund.schema.json#/properties/grund")

### grund Type

`string` ([Handelsunstimmigkeitsgrund](handelsunstimmigkeitsgrund.md))

### grund Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                      | Explanation |
| :------------------------------------------------------------------------- | :---------- |
| `"ANMELDUNG_BESTAETIGT"`                                                   |             |
| `"ABRECHNUNGSBEGINN_GLEICH_BESTAETIGTEM_VERTRAGSBEGINN"`                   |             |
| `"ABRECHNUNGSENDE_GLEICH_BESTAETIGTEM_VERTRAGSENDE"`                       |             |
| `"NN_MSCONS_UEBERSENDET"`                                                  |             |
| `"RICHTIGE_MESSWERTE_ENERGIEMENGEN_UEBERSENDET"`                           |             |
| `"SONSTIGES_SIEHE_BEGRUENDUNG"`                                            |             |
| `"GUELTIGES_PREISBLATT_VERSENDET"`                                         |             |
| `"GUELTIGER_SPERRAUFTRAG_VORHANDEN"`                                       |             |
| `"KORREKTE_ARTIKEL_ID_IN_RECHNUNG"`                                        |             |
| `"KORREKTER_PREIS_ZU_GUELTIGEM_PREISBLATT_IN_RECHNUNG"`                    |             |
| `"RECHNUNG_KORREKT_A05"`                                                   |             |
| `"RECHNUNG_KORREKT_A10"`                                                   |             |
| `"RECHNUNG_KORREKT_A11"`                                                   |             |
| `"GUELTIGES_PREISBLATT_FRISTGERECHT_VERSENDET"`                            |             |
| `"GUELTIGE_RECHNUNG_VORHANDEN"`                                            |             |
| `"ARTIKEL_ID_FUER_VERZUGSKOSTEN_VERWENDET"`                                |             |
| `"KORREKTER_PREIS_IN_RECHNUNG_ABGERECHNET"`                                |             |
| `"GUELTIGES_PREISBLATT_BLINDARBEIT_VERSENDET"`                             |             |
| `"KORREKTE_ARTIKEL_ID_IST_ANGEGEBEN"`                                      |             |
| `"RECHNUNG_BREGRUENDET_KORREKT"`                                           |             |
| `"KORREKTE_ARTIKEL_ID_FUER_ABRECHNUNG_STORNIERTER_SPERRAUFTRAG_ANGEGEBEN"` |             |
| `"ABRECHNUNG_BLINDARBEIT_SPARTE_GAS_NICHT_RELEVANT"`                       |             |
| `"SONSTIGES"`                                                              |             |

## hinweis

Hinweis zum Grund

`hinweis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-hinweis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/hinweis")

### hinweis Type

`string`

## referenzen

Referenzen auf vorherige Nachrichten

`referenzen`

*   is optional

*   Type: `string[]`

*   can be null

*   defined in: [Handelsunstimmigkeitsbegruendung](handelsunstimmigkeitsbegruendung-properties-referenzen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Handelsunstimmigkeitsbegruendung.schema.json#/properties/referenzen")

### referenzen Type

`string[]`
