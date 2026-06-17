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
| [auftragsStatusListe](#auftragsstatusliste)                   | `array`   | Optional | can be null    | [StatusmitteilungPosition](statusmitteilungposition-properties-auftragsstatusliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/auftragsStatusListe")                   |
| [lokationsTyp](#lokationstyp)                                 | `string`  | Optional | cannot be null | [StatusmitteilungPosition](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")                                                                                |
| [statusObjekt](#statusobjekt)                                 | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusobjekt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Statusobjekt.schema.json#/properties/statusObjekt")                                                                                |
| [antwortstatusCodeliste](#antwortstatuscodeliste)             | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-antwortstatuscodeliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/antwortstatusCodeliste")             |
| [vorgangsreferenznummer](#vorgangsreferenznummer)             | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-vorgangsreferenznummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/vorgangsreferenznummer")             |
| [mitteilungsnummer](#mitteilungsnummer)                       | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-mitteilungsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/mitteilungsnummer")                       |
| [anfragereferenznummer](#anfragereferenznummer)               | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-anfragereferenznummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/anfragereferenznummer")               |
| [fertigstellungsdatum](#fertigstellungsdatum)                 | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-fertigstellungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/fertigstellungsdatum")                 |
| [lieferdatum](#lieferdatum)                                   | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-lieferdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/lieferdatum")                                   |
| [sendungsposition](#sendungsposition)                         | `integer` | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-sendungsposition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/sendungsposition")                         |
| [gueltigAb](#gueltigab)                                       | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-gueltigab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/gueltigAb")                                       |
| [referenzMalo](#referenzmalo)                                 | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-referenzmalo.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/referenzMalo")                                 |
| [referenzPreisschluesselstamm](#referenzpreisschluesselstamm) | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-referenzpreisschluesselstamm.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/referenzPreisschluesselstamm") |
| [referenzArtikelID](#referenzartikelid)                       | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-referenzartikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/referenzArtikelID")                       |
| [startdatum](#startdatum)                                     | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/startdatum")                                     |
| [angebotsnummer](#angebotsnummer)                             | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-angebotsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/angebotsnummer")                             |
| [anfrageReferenz](#anfragereferenz)                           | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-anfragereferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/anfrageReferenz")                           |
| [vertragsende](#vertragsende)                                 | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-vertragsende.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/vertragsende")                                 |
| [ansichtSender](#ansichtsender)                               | `array`   | Optional | can be null    | [StatusmitteilungPosition](statusmitteilungposition-properties-ansichtsender.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/ansichtSender")                               |
| [gueltigkeitsZeitspanne](#gueltigkeitszeitspanne)             | `string`  | Optional | cannot be null | [StatusmitteilungPosition](statusmitteilungposition-properties-gueltigkeitszeitspanne.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/gueltigkeitsZeitspanne")             |
| [privilegierteEnergiemenge](#privilegierteenergiemenge)       | `object`  | Optional | cannot be null | [StatusmitteilungPosition](zeitintervallmenge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZeitintervallMenge.schema.json#/properties/privilegierteEnergiemenge")                                                        |

## positionsnummer

positionsnummer

`positionsnummer`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-positionsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/positionsnummer")

### positionsnummer Type

`integer`

## bearbeitungsdatum

bearbeitungsdatum

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

verwendungAb

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

verwendungBis

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

enddatum

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

Auftragsstatus

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
| `"AENDERUNG_DER_DATEN"`                                                   |             |
| `"KEINE_AENDERUNG_DER_DATEN"`                                             |             |

## statusanlass

Statusanlass

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

antwortstatus

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

lokationsId

`lokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-lokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/lokationsId")

### lokationsId Type

`string`

## referenzMelo

referenzMelo

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

statusVeraenderungsZeitpunkt

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

auftragsStatusListe

`auftragsStatusListe`

*   is optional

*   Type: `string[]` ([Auftragsstatus](auftragsstatus.md))

*   can be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-auftragsstatusliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/auftragsStatusListe")

### auftragsStatusListe Type

`string[]` ([Auftragsstatus](auftragsstatus.md))

## lokationsTyp

Gibt an, ob es sich um eine Markt- oder Messlokation handelt

`lokationsTyp`

*   is optional

*   Type: `string` ([Lokationstyp](lokationstyp.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](lokationstyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationstyp.schema.json#/properties/lokationsTyp")

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
| `"STEUERBARE_RESSOURCE"` |             |
| `"TRANCHE"`              |             |

## statusObjekt

Statusobjekt

`statusObjekt`

*   is optional

*   Type: `string` ([Statusobjekt](statusobjekt.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusobjekt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Statusobjekt.schema.json#/properties/statusObjekt")

### statusObjekt Type

`string` ([Statusobjekt](statusobjekt.md))

### statusObjekt Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                             | Explanation |
| :-------------------------------- | :---------- |
| `"MSBWECHSEL"`                    |             |
| `"UMBAUMELO"`                     |             |
| `"ERSTEINBAUIMS"`                 |             |
| `"ERSTEINBAUMME"`                 |             |
| `"GERAET"`                        |             |
| `"ANGEBOTANFRAGE"`                |             |
| `"STATUSBESTELLUNG"`              |             |
| `"LIEFERSCHEIN"`                  |             |
| `"SPERREN"`                       |             |
| `"ENTSPERREN"`                    |             |
| `"PRIVILEGIERUNG_NACH_ENFG"`      |             |
| `"VERAENDERUNGSSTATUS_DER_DATEN"` |             |
| `"TURNUSAUSLESUNG"`               |             |

## antwortstatusCodeliste

antwortstatusCodeliste

`antwortstatusCodeliste`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-antwortstatuscodeliste.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/antwortstatusCodeliste")

### antwortstatusCodeliste Type

`string`

## vorgangsreferenznummer

vorgangsreferenznummer

`vorgangsreferenznummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-vorgangsreferenznummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/vorgangsreferenznummer")

### vorgangsreferenznummer Type

`string`

## mitteilungsnummer

mitteilungsnummer

`mitteilungsnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-mitteilungsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/mitteilungsnummer")

### mitteilungsnummer Type

`string`

## anfragereferenznummer

anfragereferenznummer

`anfragereferenznummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-anfragereferenznummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/anfragereferenznummer")

### anfragereferenznummer Type

`string`

## fertigstellungsdatum

fertigstellungsdatum

`fertigstellungsdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-fertigstellungsdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/fertigstellungsdatum")

### fertigstellungsdatum Type

`string`

### fertigstellungsdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## lieferdatum

lieferdatum

`lieferdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-lieferdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/lieferdatum")

### lieferdatum Type

`string`

## sendungsposition

sendungsposition

`sendungsposition`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-sendungsposition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/sendungsposition")

### sendungsposition Type

`integer`

## gueltigAb

gueltigAb

`gueltigAb`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-gueltigab.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/gueltigAb")

### gueltigAb Type

`string`

### gueltigAb Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## referenzMalo

referenzMalo

`referenzMalo`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-referenzmalo.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/referenzMalo")

### referenzMalo Type

`string`

## referenzPreisschluesselstamm

referenzPreisschluesselstamm

`referenzPreisschluesselstamm`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-referenzpreisschluesselstamm.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/referenzPreisschluesselstamm")

### referenzPreisschluesselstamm Type

`string`

## referenzArtikelID

referenzArtikelID

`referenzArtikelID`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-referenzartikelid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/referenzArtikelID")

### referenzArtikelID Type

`string`

## startdatum

startdatum

`startdatum`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-startdatum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/startdatum")

### startdatum Type

`string`

### startdatum Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## angebotsnummer

angebotsnummer

`angebotsnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-angebotsnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/angebotsnummer")

### angebotsnummer Type

`string`

## anfrageReferenz

anfrageReferenz

`anfrageReferenz`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-anfragereferenz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/anfrageReferenz")

### anfrageReferenz Type

`string`

## vertragsende

vertragsende

`vertragsende`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-vertragsende.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/vertragsende")

### vertragsende Type

`string`

### vertragsende Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## ansichtSender

ansichtSender

`ansichtSender`

*   is optional

*   Type: `object[]` ([AnsichtSender](ansichtsender.md))

*   can be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-ansichtsender.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/ansichtSender")

### ansichtSender Type

`object[]` ([AnsichtSender](ansichtsender.md))

## gueltigkeitsZeitspanne

gueltigkeitsZeitspanne

`gueltigkeitsZeitspanne`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [StatusmitteilungPosition](statusmitteilungposition-properties-gueltigkeitszeitspanne.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/StatusmitteilungPosition.schema.json#/properties/gueltigkeitsZeitspanne")

### gueltigkeitsZeitspanne Type

`string`

## privilegierteEnergiemenge



`privilegierteEnergiemenge`

*   is optional

*   Type: `object` ([ZeitintervallMenge](zeitintervallmenge.md))

*   cannot be null

*   defined in: [StatusmitteilungPosition](zeitintervallmenge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/ZeitintervallMenge.schema.json#/properties/privilegierteEnergiemenge")

### privilegierteEnergiemenge Type

`object` ([ZeitintervallMenge](zeitintervallmenge.md))
