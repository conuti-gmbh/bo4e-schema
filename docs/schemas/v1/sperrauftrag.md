## Sperrauftrag Type

`object` ([Sperrauftrag](sperrauftrag.md))

# Sperrauftrag Properties

| Property                                                                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                            |
| :------------------------------------------------------------------------ | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [boTyp](#botyp)                                                           | `string`  | Required | cannot be null | [Sperrauftrag](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                       |
| [versionStruktur](#versionstruktur)                                       | `string`  | Required | cannot be null | [Sperrauftrag](sperrauftrag-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Sperraufrag.schema.json#/properties/versionStruktur")                                       |
| [treffpunkt](#treffpunkt)                                                 | `object`  | Optional | cannot be null | [Sperrauftrag](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/treffpunkt")                                                                               |
| [sperrauftragsart](#sperrauftragsart)                                     | `string`  | Optional | cannot be null | [Sperrauftrag](sperrauftragsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrauftragsart.schema.json#/properties/sperrauftragsart")                                                      |
| [sperrauftragsstatus](#sperrauftragsstatus)                               | `string`  | Optional | cannot be null | [Sperrauftrag](auftragsstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Auftragsstatus.schema.json#/properties/sperrauftragsstatus")                                                       |
| [sperrauftragsablehngrund](#sperrauftragsablehngrund)                     | `string`  | Optional | cannot be null | [Sperrauftrag](sperrauftragsablehngrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrauftragsablehngrund.schema.json#/properties/sperrauftragsablehngrund")                              |
| [sperrauftragsverhinderungsgrund](#sperrauftragsverhinderungsgrund)       | `string`  | Optional | cannot be null | [Sperrauftrag](sperrauftragsverhinderungsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrauftragsverhinderungsgrund.schema.json#/properties/sperrauftragsverhinderungsgrund")         |
| [zaehlernummer](#zaehlernummer)                                           | `string`  | Optional | cannot be null | [Sperrauftrag](sperrauftrag-properties-zaehlernummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Sperraufrag.schema.json#/properties/zaehlernummer")                                           |
| [istVomGerichtsvollzieherAngeordnet](#istvomgerichtsvollzieherangeordnet) | `boolean` | Optional | cannot be null | [Sperrauftrag](sperrauftrag-properties-istvomgerichtsvollzieherangeordnet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Sperraufrag.schema.json#/properties/istVomGerichtsvollzieherAngeordnet") |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Sperrauftrag](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"SPERRAUFTRAG"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Sperrauftrag](sperrauftrag-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Sperraufrag.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## treffpunkt



`treffpunkt`

*   is optional

*   Type: `object` ([Adresse](adresse.md))

*   cannot be null

*   defined in: [Sperrauftrag](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/treffpunkt")

### treffpunkt Type

`object` ([Adresse](adresse.md))

## sperrauftragsart

Sperrauftragsart

`sperrauftragsart`

*   is optional

*   Type: `string` ([Sperrauftragsart](sperrauftragsart.md))

*   cannot be null

*   defined in: [Sperrauftrag](sperrauftragsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrauftragsart.schema.json#/properties/sperrauftragsart")

### sperrauftragsart Type

`string` ([Sperrauftragsart](sperrauftragsart.md))

### sperrauftragsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"SPERREN"`    |             |
| `"ENTSPERREN"` |             |

## sperrauftragsstatus

Auftragsstatus

`sperrauftragsstatus`

*   is optional

*   Type: `string` ([Auftragsstatus](auftragsstatus.md))

*   cannot be null

*   defined in: [Sperrauftrag](auftragsstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Auftragsstatus.schema.json#/properties/sperrauftragsstatus")

### sperrauftragsstatus Type

`string` ([Auftragsstatus](auftragsstatus.md))

### sperrauftragsstatus Constraints

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

## sperrauftragsablehngrund

Sperrauftragsablehngrund

`sperrauftragsablehngrund`

*   is optional

*   Type: `string` ([Sperrauftragsablehngrund](sperrauftragsablehngrund.md))

*   cannot be null

*   defined in: [Sperrauftrag](sperrauftragsablehngrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrauftragsablehngrund.schema.json#/properties/sperrauftragsablehngrund")

### sperrauftragsablehngrund Type

`string` ([Sperrauftragsablehngrund](sperrauftragsablehngrund.md))

### sperrauftragsablehngrund Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                    | Explanation |
| :--------------------------------------- | :---------- |
| `"DUPLIKAT"`                             |             |
| `"FALSCHER_MSB"`                         |             |
| `"FALSCHE_SPANNUNGSEBENE"`               |             |
| `"WEITERE_MALO_BETROFFEN"`               |             |
| `"ANDERER_ABLEHNGRUND"`                  |             |
| `"FRISTVERLETZUNG_TERMINGEBUNDEN"`       |             |
| `"FRISTVERLETZUNG_NICHT_TERMINGEBUNDEN"` |             |
| `"ANDERER_FEHLER"`                       |             |
| `"LIEGT_BEREITS_VOR"`                    |             |
| `"ANDERER_ZUKUENFTIGER_LIEFERANT"`       |             |
| `"BESTAETIGTER_LIEFERBEGINN"`            |             |

## sperrauftragsverhinderungsgrund

Sperrauftragsverhinderungsgrund

`sperrauftragsverhinderungsgrund`

*   is optional

*   Type: `string` ([Sperrauftragsverhinderungsgrund](sperrauftragsverhinderungsgrund.md))

*   cannot be null

*   defined in: [Sperrauftrag](sperrauftragsverhinderungsgrund.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrauftragsverhinderungsgrund.schema.json#/properties/sperrauftragsverhinderungsgrund")

### sperrauftragsverhinderungsgrund Type

`string` ([Sperrauftragsverhinderungsgrund](sperrauftragsverhinderungsgrund.md))

### sperrauftragsverhinderungsgrund Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                       | Explanation |
| :------------------------------------------ | :---------- |
| `"RECHTLICHER_GRUND_FEHLT"`                 |             |
| `"AKTIVE_ZUTRITTSVERWEIGERUNG"`             |             |
| `"PASSIVE_ZUTRITTSVERWEIGERUNG"`            |             |
| `"ANDERER_VERHINDERUNGSGRUND"`              |             |
| `"TATSAECHLICHER_VERHINDERUNGSGRUND"`       |             |
| `"TECHNISCHER_VERHINDERUNGSGRUND"`          |             |
| `"ANSCHLUSSNUTZER_WURDE_NICHT_ANGETROFFEN"` |             |

## zaehlernummer

Die Nummer des zu sperrenden Zählers

`zaehlernummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Sperrauftrag](sperrauftrag-properties-zaehlernummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Sperraufrag.schema.json#/properties/zaehlernummer")

### zaehlernummer Type

`string`

## istVomGerichtsvollzieherAngeordnet

True, falls die Sperrung vom Gerichtsvollzieher angeordnet ist.

`istVomGerichtsvollzieherAngeordnet`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Sperrauftrag](sperrauftrag-properties-istvomgerichtsvollzieherangeordnet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Sperraufrag.schema.json#/properties/istVomGerichtsvollzieherAngeordnet")

### istVomGerichtsvollzieherAngeordnet Type

`boolean`
