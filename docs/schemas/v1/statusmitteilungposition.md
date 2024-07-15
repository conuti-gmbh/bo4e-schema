## StatusmitteilungPosition Type

`object` ([StatusmitteilungPosition](statusmitteilungposition.md))

# StatusmitteilungPosition Properties

| Property                                                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                      |
| :------------------------------------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [positionsnummer](#positionsnummer)                           | `integer` | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/positionsnummer")                           |
| [bearbeitungsdatum](#bearbeitungsdatum)                       | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-bearbeitungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/bearbeitungsdatum")                       |
| [verwendungAb](#verwendungab)                                 | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/verwendungAb")                                 |
| [verwendungBis](#verwendungbis)                               | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/verwendungBis")                               |
| [enddatum](#enddatum)                                         | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/enddatum")                                         |
| [auftragsstatus](#auftragsstatus)                             | `string`  | Optional | cannot be null | [StatusmitteilungPosition](auftragsstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Auftragsstatus.schema.json#/properties/auftragsstatus")                                                                          |
| [statusanlass](#statusanlass)                                 | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusanlass.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Statusanlass.schema.json#/properties/statusanlass")                                                                                |
| [antwortstatus](#antwortstatus)                               | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-antwortstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/antwortstatus")                               |
| [fehlerbeschreibung](#fehlerbeschreibung)                     | `object`  | Optional | cannot be null | [StatusmitteilungPosition](fehlerbeschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Fehlerbeschreibung.schema.json#/properties/fehlerbeschreibung")                                                               |
| [begruendung](#begruendung)                                   | `object`  | Optional | cannot be null | [StatusmitteilungPosition](begruendung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Begruendung.schema.json#/properties/begruendung")                                                                                    |
| [lokationsId](#lokationsid)                                   | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/lokationsId")                                   |
| [referenzMelo](#referenzmelo)                                 | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-referenzmelo.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/referenzMelo")                                 |
| [allgemeineInformationen](#allgemeineinformationen)           | `object`  | Optional | cannot be null | [StatusmitteilungPosition](allgemeineinformationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AllgemeineInformationen.schema.json#/properties/allgemeineInformationen")                                                |
| [statusVeraenderungsZeitpunkt](#statusveraenderungszeitpunkt) | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-statusveraenderungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/statusVeraenderungsZeitpunkt") |
| [auftragsStatusListe](#auftragsstatusliste)                   | `array`   | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-auftragsstatusliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/auftragsStatusListe")                   |

## positionsnummer



`positionsnummer`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/positionsnummer")

### positionsnummer Type

`integer`

## bearbeitungsdatum



`bearbeitungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-bearbeitungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/bearbeitungsdatum")

### bearbeitungsdatum Type

`string`

### bearbeitungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## verwendungAb



`verwendungAb`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-verwendungab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/verwendungAb")

### verwendungAb Type

`string`

### verwendungAb Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## verwendungBis



`verwendungBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-verwendungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/verwendungBis")

### verwendungBis Type

`string`

### verwendungBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## enddatum



`enddatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-enddatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/enddatum")

### enddatum Type

`string`

### enddatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## auftragsstatus



`auftragsstatus`

*   is optional

*   Type: `string` ([Auftragsstatus](auftragsstatus.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](auftragsstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Auftragsstatus.schema.json#/properties/auftragsstatus")

### auftragsstatus Type

`string` ([Auftragsstatus](auftragsstatus.md))

### auftragsstatus Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                     | Explanation |
| :------------------------------------------------------------------------ | :---------- |
| `"GESCHEITERT"`                                                           |             |
| `"ERFOLGREICH"`                                                           |             |
| `"LIEFERUNG_GEPLANT"`                                                     |             |
| `"GEPLANT"`                                                               |             |
| `"ZUGESTIMMT"`                                                            |             |
| `"WIDERSPROCHEN"`                                                         |             |
| `"STOERUNGSFREI"`                                                         |             |
| `"GESTOERT"`                                                              |             |
| `"FESTGESTELLTE_STOERUNG"`                                                |             |
| `"VERMUTETE_STOERUNG"`                                                    |             |
| `"ABGELEHNT"`                                                             |             |
| `"BEENDET"`                                                               |             |
| `"ANTWORT_DRITTER"`                                                       |             |
| `"BESTAETIGT"`                                                            |             |
| `"UMGESETZT"`                                                             |             |
| `"ENFG_STROMSPEICHER_UND_VERLUSTENERGIE"`                                 |             |
| `"ENFG_ELEKTRISCH_ANGETRIEBENE_WAERMEPUMPEN"`                             |             |
| `"ENFG_UMLAGEERHEBUNG_BEI_ANLAGEN_ZUR_VERSTROMUNG_VON_KUPPELGASEN"`       |             |
| `"ENFG_HERSTELLUNG_VON_GRUENEN_WASSERSTOFF"`                              |             |
| `"ENFG_STROMKOSTENINTENSIVE_UNTERNEHMEN"`                                 |             |
| `"ENFG_HERSTELLUNG_VON_WASSERSTOFF_IN_STROMKOSTENINTENSIVEN_UNTERNEHMEN"` |             |
| `"ENFG_SCHIENENBAHNEN"`                                                   |             |
| `"ENFG_ELEKTRISCHE_BETRIEBENE_BUSSEN_IM_LINIENVERKEHR"`                   |             |
| `"ENFG_LANDSTROMANLAGEN"`                                                 |             |

## statusanlass



`statusanlass`

*   is optional

*   Type: `string` ([Statusanlass](statusanlass.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusanlass.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Statusanlass.schema.json#/properties/statusanlass")

### statusanlass Type

`string` ([Statusanlass](statusanlass.md))

### statusanlass Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                | Explanation |
| :----------------------------------- | :---------- |
| `"KOMMUNIKATIONSSTOERUNG"`           |             |
| `"STATUS_GERAETEWECHSEL"`            |             |
| `"MESSEINRICHTUNG_GESTOERT_DEFEKT"`  |             |
| `"KEINE_STOERUNG_FESTSTELLBAR"`      |             |
| `"STOERUNGSBEHEBUNG_NICHT_MOEGLICH"` |             |
| `"REPARATUR_OHNE_GERAETEWECHSEL"`    |             |

## antwortstatus



`antwortstatus`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-antwortstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/antwortstatus")

### antwortstatus Type

`string`

## fehlerbeschreibung



`fehlerbeschreibung`

*   is optional

*   Type: `object` ([Fehlerbeschreibung](fehlerbeschreibung.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](fehlerbeschreibung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Fehlerbeschreibung.schema.json#/properties/fehlerbeschreibung")

### fehlerbeschreibung Type

`object` ([Fehlerbeschreibung](fehlerbeschreibung.md))

## begruendung



`begruendung`

*   is optional

*   Type: `object` ([Begruendung](begruendung.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](begruendung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Begruendung.schema.json#/properties/begruendung")

### begruendung Type

`object` ([Begruendung](begruendung.md))

## lokationsId



`lokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/lokationsId")

### lokationsId Type

`string`

## referenzMelo



`referenzMelo`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-referenzmelo.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/referenzMelo")

### referenzMelo Type

`string`

## allgemeineInformationen



`allgemeineInformationen`

*   is optional

*   Type: `object` ([AllgemeineInformationen](allgemeineinformationen.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](allgemeineinformationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AllgemeineInformationen.schema.json#/properties/allgemeineInformationen")

### allgemeineInformationen Type

`object` ([AllgemeineInformationen](allgemeineinformationen.md))

## statusVeraenderungsZeitpunkt



`statusVeraenderungsZeitpunkt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-statusveraenderungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/statusVeraenderungsZeitpunkt")

### statusVeraenderungsZeitpunkt Type

`string`

### statusVeraenderungsZeitpunkt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## auftragsStatusListe



`auftragsStatusListe`

*   is optional

*   Type: `string[]` ([Auftragsstatus](auftragsstatus.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-auftragsstatusliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/auftragsStatusListe")

### auftragsStatusListe Type

`string[]` ([Auftragsstatus](auftragsstatus.md))
