## Statusmitteilung Type

`object` ([Statusmitteilung](statusmitteilung.md))

# Statusmitteilung Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                   |
| :---------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                     | `string` | Required | cannot be null | [Statusmitteilung](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                          |
| [versionStruktur](#versionstruktur) | `string` | Required | cannot be null | [Statusmitteilung](statusmitteilung-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusmitteilung.schema.json#/properties/versionStruktur") |
| [statusObjekt](#statusobjekt)       | `string` | Optional | cannot be null | [Statusmitteilung](statusobjekt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Statusobjekt.schema.json#/properties/statusObjekt")                                     |
| [statusanlass](#statusanlass)       | `string` | Optional | cannot be null | [Statusmitteilung](status.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Status.schema.json#/properties/statusanlass")                                                 |
| [auftragsstatus](#auftragsstatus)   | `string` | Optional | cannot be null | [Statusmitteilung](auftragsstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Auftragsstatus.schema.json#/properties/auftragsstatus")                               |
| [positionsdaten](#positionsdaten)   | `array`  | Optional | cannot be null | [Statusmitteilung](statusmitteilung-properties-positionsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusmitteilung.schema.json#/properties/positionsdaten")   |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Statusmitteilung](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"STATUSMITTEILUNG"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Statusmitteilung](statusmitteilung-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusmitteilung.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## statusObjekt



`statusObjekt`

*   is optional

*   Type: `string` ([Statusobjekt](statusobjekt.md))

*   cannot be null

*   defined in: [Statusmitteilung](statusobjekt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Statusobjekt.schema.json#/properties/statusObjekt")

### statusObjekt Type

`string` ([Statusobjekt](statusobjekt.md))

### statusObjekt Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                        | Explanation |
| :--------------------------- | :---------- |
| `"MSBWECHSEL"`               |             |
| `"UMBAUMELO"`                |             |
| `"ERSTEINBAUIMS"`            |             |
| `"ERSTEINBAUMME"`            |             |
| `"GERAET"`                   |             |
| `"ANGEBOTANFRAGE"`           |             |
| `"STATUSBESTELLUNG"`         |             |
| `"LIEFERSCHEIN"`             |             |
| `"SPERREN"`                  |             |
| `"ENTSPERREN"`               |             |
| `"PRIVILEGIERUNG_NACH_ENFG"` |             |

## statusanlass



`statusanlass`

*   is optional

*   Type: `string` ([Status](status.md))

*   cannot be null

*   defined in: [Statusmitteilung](status.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Status.schema.json#/properties/statusanlass")

### statusanlass Type

`string` ([Status](status.md))

### statusanlass Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                                                        | Explanation |
| :------------------------------------------------------------------------------------------- | :---------- |
| `"KUNDENSELBSTABLESUNG"`                                                                     |             |
| `"LEERSTAND"`                                                                                |             |
| `"REALER_ZAEHLERUEBERLAUF_GEPRUEFT"`                                                         |             |
| `"PLAUSIBEL_WG_KONTROLLABLESUNG"`                                                            |             |
| `"PLAUSIBEL_WG_KUNDENHINWEIS"`                                                               |             |
| `"AUSTAUSCH_DES_ERSATZWERTES"`                                                               |             |
| `"RECHENWERT"`                                                                               |             |
| `"BASIS_MME"`                                                                                |             |
| `"VERGLEICHSMESSUNG_GEEICHT"`                                                                |             |
| `"VERGLEICHSMESSUNG_NICHT_GEEICHT"`                                                          |             |
| `"MESSWERTNACHBILDUNG_AUS_GEEICHTEN_WERTEN"`                                                 |             |
| `"MESSWERTNACHBILDUNG_AUS_NICHT_GEEICHTEN_WERTEN"`                                           |             |
| `"INTERPOLATION"`                                                                            |             |
| `"HALTEWERT"`                                                                                |             |
| `"BILANZIERUNG_NETZABSCHNITT"`                                                               |             |
| `"HISTORISCHE_MESSWERTE"`                                                                    |             |
| `"STATISTISCHE_METHODE"`                                                                     |             |
| `"AUFTEILUNG"`                                                                               |             |
| `"VERWENDUNG_VON_WERTEN_DES_STOERMENGENZAEHLWERKS"`                                          |             |
| `"UMGANGS_UND_KORREKTURMENGEN"`                                                              |             |
| `"ANGABEN_MESSLOKATION"`                                                                     |             |
| `"KEIN_ZUGANG"`                                                                              |             |
| `"KOMMUNIKATIONSSTOERUNG"`                                                                   |             |
| `"NETZAUSFALL"`                                                                              |             |
| `"SPANNUNGSAUSFALL"`                                                                         |             |
| `"STATUS_GERAETEWECHSEL"`                                                                    |             |
| `"KALIBRIERUNG"`                                                                             |             |
| `"GERAET_ARBEITET_AUSSERHALB_DER_BETRIEBSBEDINGUNGEN"`                                       |             |
| `"MESSEINRICHTUNG_GESTOERT_DEFEKT"`                                                          |             |
| `"UNSICHERHEIT_MESSUNG"`                                                                     |             |
| `"BERUECKSICHTIGUNG_STOERMENGENZAEHLWERK"`                                                   |             |
| `"MENGENUMWERTUNG_VOLLSTAENDIG"`                                                             |             |
| `"UHRZEIT_GESTELLT_SYNCHRONISATION"`                                                         |             |
| `"MESSWERT_UNPLAUSIBEL"`                                                                     |             |
| `"FALSCHER_WANDLERFAKTOR"`                                                                   |             |
| `"FEHLERHAFTE_ABLESUNG"`                                                                     |             |
| `"AENDERUNG_DER_BERECHNUNG"`                                                                 |             |
| `"UMBAU_DER_MESSLOKATION"`                                                                   |             |
| `"DATENBEARBEITUNGSFEHLER"`                                                                  |             |
| `"BRENNWERTKORREKTUR"`                                                                       |             |
| `"Z_ZAHL_KORREKTUR"`                                                                         |             |
| `"STOERUNG_DEFEKT_MESSEINRICHTUNG"`                                                          |             |
| `"AENDERUNG_TARIFSCHALTZEITEN"`                                                              |             |
| `"TARIFSCHALTGERAET_DEFEKT"`                                                                 |             |
| `"IMPULSWERTIGKEIT_NICHT_AUSREICHEND"`                                                       |             |
| `"ENERGIEMENGE_IN_UNGEMESSENEM_ZEITINTERVALL"`                                               |             |
| `"ENERGIEMENGE_AUS_DEM_UNGEPAIRTEN_ZEITINTERVALL"`                                           |             |
| `"WARTUNGSARBEITEN_AN_GEEICHTEM_MESSGERAET"`                                                 |             |
| `"GESTOERTE_WERTE"`                                                                          |             |
| `"WARTUNGSARBEITEN_AN_EICHRECHTSKONFORMEN_MESSGERAETEN"`                                     |             |
| `"KONSISTENZ_UND_SYNCHRONPRUEFUNG"`                                                          |             |
| `"GRUND_ANGABEN_MESSLOKATION"`                                                               |             |
| `"ANFORDERUNG_IN_DIE_VERGANGENHEIT_ZUM_ANGEFORDERTEN_ZEITPUNKT_LIEGT_KEIN_WERT_VOR"`         |             |
| `"UMSTELLUNG_GASQUALITAET"`                                                                  |             |
| `"ZAEHLERSTAND_ZUM_BEGINN_DER_ANGEGEBENEN_ENERGIEMENGE_VORHANDEN_UND_KOMMUNIZIERT"`          |             |
| `"ZAEHLERSTAND_ZUM_ENDE_DER_ANGEGEBENEN_ENERGIEMENGE_VORHANDEN_UND_KOMMUNIZIERT"`            |             |
| `"ZAEHLERSTAND_ZUM_BEGINN_DER_ANGEGEBENEN_ENERGIEMENGE_NICHT_VORHANDEN_DA_MENGENABGRENZUNG"` |             |
| `"ZAEHLERSTAND_ZUM_ENDE_DER_ANGEGEBENEN_ENERGIEMENGE_NICHT_VORHANDEN_DA_MENGENABGRENZUNG"`   |             |
| `"GESCHEITERT"`                                                                              |             |
| `"AUSGEBAUT"`                                                                                |             |

## auftragsstatus



`auftragsstatus`

*   is optional

*   Type: `string` ([Auftragsstatus](auftragsstatus.md))

*   cannot be null

*   defined in: [Statusmitteilung](auftragsstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Auftragsstatus.schema.json#/properties/auftragsstatus")

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

## positionsdaten



`positionsdaten`

*   is optional

*   Type: `object[]` ([StatusmitteilungPosition](statusmitteilungposition.md))

*   cannot be null

*   defined in: [Statusmitteilung](statusmitteilung-properties-positionsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Statusmitteilung.schema.json#/properties/positionsdaten")

### positionsdaten Type

`object[]` ([StatusmitteilungPosition](statusmitteilungposition.md))
