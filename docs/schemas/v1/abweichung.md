## Untitled object in undefined Type

`object` ([Details](abweichung.md))

# Untitled object in undefined Properties

| Property                                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                           |
| :------------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [abweichungsgrund](#abweichungsgrund)                   | `string` | Optional | cannot be null | [Untitled schema](abweichungsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Abweichungsgrund.schema.json#/properties/abweichungsgrund")                                  |
| [abweichungsgrundBemerkung](#abweichungsgrundbemerkung) | `string` | Optional | cannot be null | [Untitled schema](abweichung-properties-abweichungsgrundbemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/abweichungsgrundBemerkung") |
| [zugehoerigeRechnung](#zugehoerigerechnung)             | `string` | Optional | cannot be null | [Untitled schema](abweichung-properties-zugehoerigerechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/zugehoerigeRechnung")             |
| [abschlagsrechnungen](#abschlagsrechnungen)             | `array`  | Optional | cannot be null | [Untitled schema](abweichung-properties-abschlagsrechnungen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/abschlagsrechnungen")             |
| [abweichungsgrundCode](#abweichungsgrundcode)           | `string` | Optional | cannot be null | [Untitled schema](abweichung-properties-abweichungsgrundcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/abweichungsgrundCode")           |
| [abweichungsgrundCodeliste](#abweichungsgrundcodeliste) | `string` | Optional | cannot be null | [Untitled schema](abweichung-properties-abweichungsgrundcodeliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/abweichungsgrundCodeliste") |

## abweichungsgrund



`abweichungsgrund`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](abweichungsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Abweichungsgrund.schema.json#/properties/abweichungsgrund")

### abweichungsgrund Type

`string`

### abweichungsgrund Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                                          | Explanation |
| :--------------------------------------------------------------------------------------------- | :---------- |
| `"PREIS_RECHENREGEL_FALSCH"`                                                                   |             |
| `"FALSCHER_ABRECHNUNGSZEITRAUM"`                                                               |             |
| `"UNBEKANNTE_MARKTLOKATION_MESSLOKATION"`                                                      |             |
| `"SONSTIGER_ABWEICHUNGSGRUND"`                                                                 |             |
| `"DOPPELTE_RECHNUNG"`                                                                          |             |
| `"ABRECHNUNGSBEGINN_UNGLEICH_VERTRAGSBEGINN"`                                                  |             |
| `"ABRECHNUNGSENDE_UNGLEICH_VERTRAGSENDE"`                                                      |             |
| `"BETRAG_DER_ABSCHLAGSRECHNUNG_FALSCH"`                                                        |             |
| `"VORAUSBEZAHLTER_BETRAG_FALSCH"`                                                              |             |
| `"ARTIKEL_NICHT_VEREINBART"`                                                                   |             |
| `"NETZNUTZUNGSMESSWERTE_ENERGIEMENGEN_FEHLEN"`                                                 |             |
| `"RECHNUNGSNUMMER_BEREITS_ERHALTEN"`                                                           |             |
| `"NETZNUTZUNGSMESSWERTE_ENERGIEMENGEN_FALSCH"`                                                 |             |
| `"ZEITLICHE_MENGENANGABE_FEHLERHAFT"`                                                          |             |
| `"FALSCHER_BILANZIERUNGSBEGINN"`                                                               |             |
| `"FALSCHES_NETZNUTZUNGSENDE"`                                                                  |             |
| `"BILANZIERTE_MENGE_FEHLT"`                                                                    |             |
| `"BILANZIERTE_MENGE_FALSCH"`                                                                   |             |
| `"NETZNUTZUNGSABRECHNUNG_FEHLT"`                                                               |             |
| `"REVERSE_CHARGE_ANWENDUNG_FEHLT_ODER_FEHLERHAFT"`                                             |             |
| `"ALLOKATIONSLISTE_FEHLT"`                                                                     |             |
| `"MEHR_MINDERMENGE_FALSCH"`                                                                    |             |
| `"UNGUELTIGES_RECHNUNGSDATUM"`                                                                 |             |
| `"ZEITINTERVALL_DER_BILANZIERTEN_MENGE_INKONSISTENT"`                                          |             |
| `"RECHNUNGSEMPFAENGER_WIDERSPRICHT_DER_STEUERRECHTLICHEN_EINSCHAETZUNG_DES_RECHNUNGSSTELLERS"` |             |
| `"ANGEGEBENE_QUOTES_AN_MARKTLOKATION_NICHT_VORHANDEN"`                                         |             |
| `"RECHNUNGSABWICKLUNG_NICHT_VEREINBART"`                                                       |             |
| `"COMDIS_WIRD_ABGELEHNT"`                                                                      |             |

## abweichungsgrundBemerkung



`abweichungsgrundBemerkung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](abweichung-properties-abweichungsgrundbemerkung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/abweichungsgrundBemerkung")

### abweichungsgrundBemerkung Type

`string`

## zugehoerigeRechnung



`zugehoerigeRechnung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](abweichung-properties-zugehoerigerechnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/zugehoerigeRechnung")

### zugehoerigeRechnung Type

`string`

## abschlagsrechnungen



`abschlagsrechnungen`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Untitled schema](abweichung-properties-abschlagsrechnungen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/abschlagsrechnungen")

### abschlagsrechnungen Type

`string[]`

## abweichungsgrundCode



`abweichungsgrundCode`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](abweichung-properties-abweichungsgrundcode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/abweichungsgrundCode")

### abweichungsgrundCode Type

`string`

## abweichungsgrundCodeliste



`abweichungsgrundCodeliste`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Untitled schema](abweichung-properties-abweichungsgrundcodeliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Abweichung.schema.json#/properties/abweichungsgrundCodeliste")

### abweichungsgrundCodeliste Type

`string`
