## Marktlokation Type

`object` ([Marktlokation](marktlokation.md))

# Marktlokation Properties

| Property                                                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                  |
| :-------------------------------------------------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [boTyp](#botyp)                                                             | `string`  | Required | cannot be null | [Marktlokation](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                            |
| [versionStruktur](#versionstruktur)                                         | `string`  | Required | cannot be null | [Marktlokation](marktlokation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/versionStruktur")                                         |
| [marktlokationsId](#marktlokationsid)                                       | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/marktlokationsId")                                       |
| [sparte](#sparte)                                                           | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/sparte")                                                           |
| [energierichtung](#energierichtung)                                         | `string`  | Optional | cannot be null | [Marktlokation](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")                                                              |
| [bilanzierungsmethode](#bilanzierungsmethode)                               | `string`  | Optional | cannot be null | [Marktlokation](bilanzierungsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bilanzierungsmethode.schema.json#/properties/bilanzierungsmethode")                                               |
| [verbrauchsart](#verbrauchsart)                                             | `string`  | Optional | cannot be null | [Marktlokation](verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsart.schema.json#/properties/verbrauchsart")                                                                    |
| [unterbrechbar](#unterbrechbar)                                             | `boolean` | Optional | cannot be null | [Marktlokation](marktlokation-properties-unterbrechbar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/unterbrechbar")                                             |
| [netzebene](#netzebene)                                                     | `string`  | Optional | cannot be null | [Marktlokation](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/netzebene")                                                                                |
| [umspannung](#umspannung)                                                   | `string`  | Optional | cannot be null | [Marktlokation](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/umspannung")                                                                               |
| [netzbetreiberCodeNr](#netzbetreibercodenr)                                 | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-netzbetreibercodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/netzbetreiberCodeNr")                                 |
| [gebietTyp](#gebiettyp)                                                     | `string`  | Optional | cannot be null | [Marktlokation](gebiettyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gebiettyp.schema.json#/properties/gebietTyp")                                                                                |
| [netzgebietNr](#netzgebietnr)                                               | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-netzgebietnr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/netzgebietNr")                                               |
| [bilanzierungsgebiet](#bilanzierungsgebiet)                                 | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-bilanzierungsgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/bilanzierungsgebiet")                                 |
| [grundversorgerCodeNr](#grundversorgercodenr)                               | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-grundversorgercodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/grundversorgerCodeNr")                               |
| [gasqualitaet](#gasqualitaet)                                               | `string`  | Optional | cannot be null | [Marktlokation](gasqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gasqualitaet.schema.json#/properties/gasqualitaet")                                                                       |
| [endkunde](#endkunde)                                                       | `object`  | Optional | cannot be null | [Marktlokation](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/endkunde")                                                                   |
| [lokationsadresse](#lokationsadresse)                                       | `object`  | Optional | cannot be null | [Marktlokation](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/lokationsadresse")                                                                              |
| [katasterinformation](#katasterinformation)                                 | `object`  | Optional | cannot be null | [Marktlokation](katasteradresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Katasteradresse.schema.json#/properties/katasterinformation")                                                           |
| [regelzone](#regelzone)                                                     | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-regelzone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/regelzone")                                                     |
| [marktgebiet](#marktgebiet)                                                 | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-marktgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/marktgebiet")                                                 |
| [zeitreihentyp](#zeitreihentyp)                                             | `string`  | Optional | cannot be null | [Marktlokation](zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeitreihentyp.schema.json#/properties/zeitreihentyp")                                                                    |
| [messtechnischeEinordnung](#messtechnischeeinordnung)                       | `string`  | Optional | cannot be null | [Marktlokation](messtechnischeeinordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MesstechnischeEinordnung.schema.json#/properties/messtechnischeEinordnung")                                   |
| [sperrstatus](#sperrstatus)                                                 | `string`  | Optional | cannot be null | [Marktlokation](sperrstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrstatus.schema.json#/properties/sperrstatus")                                                                          |
| [referenzMarktlokationsId](#referenzmarktlokationsid)                       | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-referenzmarktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/referenzMarktlokationsId")                       |
| [versorgungsart](#versorgungsart)                                           | `string`  | Optional | cannot be null | [Marktlokation](versorgungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Versorgungsart.schema.json#/properties/versorgungsart")                                                                 |
| [eigentuemer](#eigentuemer)                                                 | `object`  | Optional | cannot be null | [Marktlokation](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/eigentuemer")                                                                |
| [hausverwalter](#hausverwalter)                                             | `object`  | Optional | cannot be null | [Marktlokation](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/hausverwalter")                                                              |
| [verguetungEmpfaenger](#verguetungempfaenger)                               | `string`  | Optional | cannot be null | [Marktlokation](verguetungempfaenger.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/VerguetungEmpfaenger.schema.json#/properties/verguetungEmpfaenger")                                               |
| [statusErzeugendeMalo](#statuserzeugendemalo)                               | `string`  | Optional | cannot be null | [Marktlokation](statuserzeugendemarktlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/StatusErzeugendeMarktlokation.schema.json#/properties/statusErzeugendeMalo")                             |
| [fernsteuerbarkeit](#fernsteuerbarkeit)                                     | `string`  | Optional | cannot be null | [Marktlokation](fernsteuerbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fernsteuerbarkeit.schema.json#/properties/fernsteuerbarkeit")                                                        |
| [foerderungsLand](#foerderungsland)                                         | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-foerderungsland.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/foerderungsLand")                                         |
| [redispatch](#redispatch)                                                   | `boolean` | Optional | cannot be null | [Marktlokation](marktlokation-properties-redispatch.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/redispatch")                                                   |
| [zukuenftigerMeldepunkt](#zukuenftigermeldepunkt)                           | `boolean` | Optional | cannot be null | [Marktlokation](marktlokation-properties-zukuenftigermeldepunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/zukuenftigerMeldepunkt")                           |
| [lokationszuordnung](#lokationszuordnung)                                   | `string`  | Optional | cannot be null | [Marktlokation](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")                                                     |
| [konfigurationsprodukt](#konfigurationsprodukt)                             | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/konfigurationsprodukt")                             |
| [leistungskurvendefinition](#leistungskurvendefinition)                     | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-leistungskurvendefinition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/leistungskurvendefinition")                     |
| [produktdatenRelevanteRolle](#produktdatenrelevanterolle)                   | `string`  | Optional | cannot be null | [Marktlokation](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/produktdatenRelevanteRolle")                                                             |
| [beteiligterMarktpartner](#beteiligtermarktpartner)                         | `object`  | Optional | cannot be null | [Marktlokation](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/beteiligterMarktpartner")                                                        |
| [modulNetzentgelte](#modulnetzentgelte)                                     | `string`  | Optional | cannot be null | [Marktlokation](modulnetzentgelte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ModulNetzentgelte.schema.json#/properties/modulNetzentgelte")                                                        |
| [datenqualitaet](#datenqualitaet)                                           | `string`  | Optional | cannot be null | [Marktlokation](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                                                 |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum)                               | `object`  | Optional | cannot be null | [Marktlokation](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                                                        |
| [marktrollen](#marktrollen)                                                 | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-marktrollen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/marktrollen")                                                 |
| [zaehlwerke](#zaehlwerke)                                                   | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/zaehlwerke")                                                   |
| [zaehlwerkeBeteiligteMarktrolle](#zaehlwerkebeteiligtemarktrolle)           | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-zaehlwerkebeteiligtemarktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/zaehlwerkeBeteiligteMarktrolle")           |
| [verbrauchsmenge](#verbrauchsmenge)                                         | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-verbrauchsmenge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/verbrauchsmenge")                                         |
| [zugehoerigeMesslokationen](#zugehoerigemesslokationen)                     | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-zugehoerigemesslokationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/zugehoerigeMesslokationen")                     |
| [netznutzungsabrechnungsdaten](#netznutzungsabrechnungsdaten)               | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-netznutzungsabrechnungsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/netznutzungsabrechnungsdaten")               |
| [messstellenbetriebsabrechnungsdaten](#messstellenbetriebsabrechnungsdaten) | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-messstellenbetriebsabrechnungsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/messstellenbetriebsabrechnungsdaten") |
| [energieherkunft](#energieherkunft)                                         | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-energieherkunft.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/energieherkunft")                                         |
| [erforderlichesProduktpaket](#erforderlichesproduktpaket)                   | `array`   | Optional | cannot be null | [Marktlokation](marktlokation-properties-erforderlichesproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/erforderlichesProduktpaket")                   |
| [geokoordinaten](#geokoordinaten)                                           | `object`  | Optional | cannot be null | [Marktlokation](geokoordinaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/geokoordinaten")                                                                  |
| [paketId](#paketid)                                                         | `string`  | Optional | cannot be null | [Marktlokation](marktlokation-properties-paketid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/paketId")                                                         |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Marktlokation](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"MARKTLOKATION"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## marktlokationsId



`marktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-marktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/marktlokationsId")

### marktlokationsId Type

`string`

## sparte



`sparte`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/sparte")

### sparte Type

`string`

## energierichtung



`energierichtung`

*   is optional

*   Type: `string` ([Energierichtung](energierichtung.md))

*   cannot be null

*   defined in: [Marktlokation](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")

### energierichtung Type

`string` ([Energierichtung](energierichtung.md))

### energierichtung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"AUSSP"` |             |
| `"EINSP"` |             |

## bilanzierungsmethode



`bilanzierungsmethode`

*   is optional

*   Type: `string` ([Bilanzierungsmethode](bilanzierungsmethode.md))

*   cannot be null

*   defined in: [Marktlokation](bilanzierungsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bilanzierungsmethode.schema.json#/properties/bilanzierungsmethode")

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

## verbrauchsart



`verbrauchsart`

*   is optional

*   Type: `string` ([Verbrauchsart](verbrauchsart.md))

*   cannot be null

*   defined in: [Marktlokation](verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Verbrauchsart.schema.json#/properties/verbrauchsart")

### verbrauchsart Type

`string` ([Verbrauchsart](verbrauchsart.md))

### verbrauchsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"KL"`   |             |
| `"W"`    |             |
| `"EMOB"` |             |
| `"SB"`   |             |
| `"SW"`   |             |
| `"WK"`   |             |

## unterbrechbar



`unterbrechbar`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-unterbrechbar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/unterbrechbar")

### unterbrechbar Type

`boolean`

## netzebene



`netzebene`

*   is optional

*   Type: `string` ([Netzebene](netzebene.md))

*   cannot be null

*   defined in: [Marktlokation](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/netzebene")

### netzebene Type

`string` ([Netzebene](netzebene.md))

### netzebene Constraints

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

## umspannung



`umspannung`

*   is optional

*   Type: `string` ([Netzebene](netzebene.md))

*   cannot be null

*   defined in: [Marktlokation](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/umspannung")

### umspannung Type

`string` ([Netzebene](netzebene.md))

### umspannung Constraints

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

## netzbetreiberCodeNr



`netzbetreiberCodeNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-netzbetreibercodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/netzbetreiberCodeNr")

### netzbetreiberCodeNr Type

`string`

## gebietTyp



`gebietTyp`

*   is optional

*   Type: `string` ([Gebiettyp](gebiettyp.md))

*   cannot be null

*   defined in: [Marktlokation](gebiettyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gebiettyp.schema.json#/properties/gebietTyp")

### gebietTyp Type

`string` ([Gebiettyp](gebiettyp.md))

### gebietTyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"REGELZONE"`              |             |
| `"MARKTGEBIET"`            |             |
| `"BILANZIERUNGSGEBIET"`    |             |
| `"VERTEILNETZ"`            |             |
| `"TRANSPORTNETZ"`          |             |
| `"REGIONALNETZ"`           |             |
| `"AREALNETZ"`              |             |
| `"GRUNDVERSORGUNGSGEBIET"` |             |
| `"VERSORGUNGSGEBIET"`      |             |

## netzgebietNr



`netzgebietNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-netzgebietnr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/netzgebietNr")

### netzgebietNr Type

`string`

## bilanzierungsgebiet



`bilanzierungsgebiet`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-bilanzierungsgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/bilanzierungsgebiet")

### bilanzierungsgebiet Type

`string`

## grundversorgerCodeNr



`grundversorgerCodeNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-grundversorgercodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/grundversorgerCodeNr")

### grundversorgerCodeNr Type

`string`

## gasqualitaet



`gasqualitaet`

*   is optional

*   Type: `string` ([Gasqualitaet](gasqualitaet.md))

*   cannot be null

*   defined in: [Marktlokation](gasqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gasqualitaet.schema.json#/properties/gasqualitaet")

### gasqualitaet Type

`string` ([Gasqualitaet](gasqualitaet.md))

### gasqualitaet Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"H_GAS"` |             |
| `"L_GAS"` |             |

## endkunde



`endkunde`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Marktlokation](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/endkunde")

### endkunde Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## lokationsadresse



`lokationsadresse`

*   is optional

*   Type: `object` ([Adresse](adresse.md))

*   cannot be null

*   defined in: [Marktlokation](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/lokationsadresse")

### lokationsadresse Type

`object` ([Adresse](adresse.md))

## katasterinformation



`katasterinformation`

*   is optional

*   Type: `object` ([Katasteradresse](katasteradresse.md))

*   cannot be null

*   defined in: [Marktlokation](katasteradresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Katasteradresse.schema.json#/properties/katasterinformation")

### katasterinformation Type

`object` ([Katasteradresse](katasteradresse.md))

## regelzone



`regelzone`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-regelzone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/regelzone")

### regelzone Type

`string`

## marktgebiet



`marktgebiet`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-marktgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/marktgebiet")

### marktgebiet Type

`string`

## zeitreihentyp



`zeitreihentyp`

*   is optional

*   Type: `string` ([Zeitreihentyp](zeitreihentyp.md))

*   cannot be null

*   defined in: [Marktlokation](zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeitreihentyp.schema.json#/properties/zeitreihentyp")

### zeitreihentyp Type

`string` ([Zeitreihentyp](zeitreihentyp.md))

### zeitreihentyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"EGS"`     |             |
| `"LGS"`     |             |
| `"NZR"`     |             |
| `"SES"`     |             |
| `"SLS"`     |             |
| `"TES"`     |             |
| `"TLS"`     |             |
| `"SLS_TLS"` |             |
| `"SES_TES"` |             |

## messtechnischeEinordnung



`messtechnischeEinordnung`

*   is optional

*   Type: `string` ([MesstechnischeEinordnung](messtechnischeeinordnung.md))

*   cannot be null

*   defined in: [Marktlokation](messtechnischeeinordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MesstechnischeEinordnung.schema.json#/properties/messtechnischeEinordnung")

### messtechnischeEinordnung Type

`string` ([MesstechnischeEinordnung](messtechnischeeinordnung.md))

### messtechnischeEinordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"IMS"`           |             |
| `"KME_MME"`       |             |
| `"KEINE_MESSUNG"` |             |

## sperrstatus



`sperrstatus`

*   is optional

*   Type: `string` ([Sperrstatus](sperrstatus.md))

*   cannot be null

*   defined in: [Marktlokation](sperrstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrstatus.schema.json#/properties/sperrstatus")

### sperrstatus Type

`string` ([Sperrstatus](sperrstatus.md))

### sperrstatus Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"ENTSPERRT"` |             |
| `"GESPERRT"`  |             |

## referenzMarktlokationsId



`referenzMarktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-referenzmarktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/referenzMarktlokationsId")

### referenzMarktlokationsId Type

`string`

## versorgungsart



`versorgungsart`

*   is optional

*   Type: `string` ([Versorgungsart](versorgungsart.md))

*   cannot be null

*   defined in: [Marktlokation](versorgungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Versorgungsart.schema.json#/properties/versorgungsart")

### versorgungsart Type

`string` ([Versorgungsart](versorgungsart.md))

### versorgungsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                 | Explanation |
| :-------------------- | :---------- |
| `"ERSATZVERSORGUNG"`  |             |
| `"GRUNDVERSORGUNG"`   |             |
| `"ERSATZBELIEFERUNG"` |             |

## eigentuemer



`eigentuemer`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Marktlokation](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/eigentuemer")

### eigentuemer Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## hausverwalter



`hausverwalter`

*   is optional

*   Type: `object` ([Geschaeftspartner](geschaeftspartner.md))

*   cannot be null

*   defined in: [Marktlokation](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/hausverwalter")

### hausverwalter Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## verguetungEmpfaenger



`verguetungEmpfaenger`

*   is optional

*   Type: `string` ([VerguetungEmpfaenger](verguetungempfaenger.md))

*   cannot be null

*   defined in: [Marktlokation](verguetungempfaenger.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/VerguetungEmpfaenger.schema.json#/properties/verguetungEmpfaenger")

### verguetungEmpfaenger Type

`string` ([VerguetungEmpfaenger](verguetungempfaenger.md))

### verguetungEmpfaenger Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"KUNDE"`     |             |
| `"LIEFERANT"` |             |

## statusErzeugendeMalo



`statusErzeugendeMalo`

*   is optional

*   Type: `string` ([StatusErzeugendeMarktlokation](statuserzeugendemarktlokation.md))

*   cannot be null

*   defined in: [Marktlokation](statuserzeugendemarktlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/StatusErzeugendeMarktlokation.schema.json#/properties/statusErzeugendeMalo")

### statusErzeugendeMalo Type

`string` ([StatusErzeugendeMarktlokation](statuserzeugendemarktlokation.md))

### statusErzeugendeMalo Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                                  | Explanation |
| :----------------------------------------------------- | :---------- |
| `"EINSPEISEVERGUETUNG_PARAGRAPH_37"`                   |             |
| `"GEFOERDERTE_DIREKTVERMARKTUNG"`                      |             |
| `"SONSTIGE_DIREKTVERMARKTUNG"`                         |             |
| `"VERMARKTUNG_OHNE_GESETZL_VERGUETUNG"`                |             |
| `"KWKG_VERGUETUNG"`                                    |             |
| `"EINSPEISEVERGUETUNG_PARAGRAPH_38_AUSFALLVERGUETUNG"` |             |

## fernsteuerbarkeit



`fernsteuerbarkeit`

*   is optional

*   Type: `string` ([Fernsteuerbarkeit](fernsteuerbarkeit.md))

*   cannot be null

*   defined in: [Marktlokation](fernsteuerbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fernsteuerbarkeit.schema.json#/properties/fernsteuerbarkeit")

### fernsteuerbarkeit Type

`string` ([Fernsteuerbarkeit](fernsteuerbarkeit.md))

### fernsteuerbarkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                             | Explanation |
| :-------------------------------- | :---------- |
| `"TECHNISCH_NICHT_FERNSTEUERBAR"` |             |
| `"TECHNISCH_FERNSTEUERBAR"`       |             |
| `"DURCH_LF_FERNSTEUERBAR"`        |             |

## foerderungsLand



`foerderungsLand`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-foerderungsland.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/foerderungsLand")

### foerderungsLand Type

`string`

## redispatch



`redispatch`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-redispatch.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/redispatch")

### redispatch Type

`boolean`

## zukuenftigerMeldepunkt



`zukuenftigerMeldepunkt`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-zukuenftigermeldepunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/zukuenftigerMeldepunkt")

### zukuenftigerMeldepunkt Type

`boolean`

## lokationszuordnung



`lokationszuordnung`

*   is optional

*   Type: `string` ([Lokationszuordnung](lokationszuordnung.md))

*   cannot be null

*   defined in: [Marktlokation](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")

### lokationszuordnung Type

`string` ([Lokationszuordnung](lokationszuordnung.md))

### lokationszuordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"UNVERAENDERT"` |             |
| `"BEGINNT"`      |             |
| `"ENDET"`        |             |

## konfigurationsprodukt



`konfigurationsprodukt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-konfigurationsprodukt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/konfigurationsprodukt")

### konfigurationsprodukt Type

`string`

## leistungskurvendefinition



`leistungskurvendefinition`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-leistungskurvendefinition.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/leistungskurvendefinition")

### leistungskurvendefinition Type

`string`

## produktdatenRelevanteRolle



`produktdatenRelevanteRolle`

*   is optional

*   Type: `string` ([Marktrolle](marktrolle.md))

*   cannot be null

*   defined in: [Marktlokation](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/produktdatenRelevanteRolle")

### produktdatenRelevanteRolle Type

`string` ([Marktrolle](marktrolle.md))

### produktdatenRelevanteRolle Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | :---------- |
| `"NB"`              |             |
| `"LF"`              |             |
| `"MSB"`             |             |
| `"MSBA"`            |             |
| `"GMSB"`            |             |
| `"MDL"`             |             |
| `"DL"`              |             |
| `"BKV"`             |             |
| `"BKO"`             |             |
| `"UENB"`            |             |
| `"KUNDE-SELBST-NN"` |             |
| `"MGV"`             |             |
| `"EIV"`             |             |
| `"RB"`              |             |
| `"KUNDE"`           |             |
| `"INTERESSENT"`     |             |
| `"KN"`              |             |
| `"UBA"`             |             |
| `"BIKO"`            |             |
| `"ESA"`             |             |

## beteiligterMarktpartner



`beteiligterMarktpartner`

*   is optional

*   Type: `object` ([Marktteilnehmer](marktteilnehmer.md))

*   cannot be null

*   defined in: [Marktlokation](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/beteiligterMarktpartner")

### beteiligterMarktpartner Type

`object` ([Marktteilnehmer](marktteilnehmer.md))

## modulNetzentgelte



`modulNetzentgelte`

*   is optional

*   Type: `string` ([ModulNetzentgelte](modulnetzentgelte.md))

*   cannot be null

*   defined in: [Marktlokation](modulnetzentgelte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ModulNetzentgelte.schema.json#/properties/modulNetzentgelte")

### modulNetzentgelte Type

`string` ([ModulNetzentgelte](modulnetzentgelte.md))

### modulNetzentgelte Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                             | Explanation |
| :------------------------------------------------ | :---------- |
| `"PAUSCHALE_NETZGELDREDUZIERUNG_MODUL_1"`         |             |
| `"PROZENTUALE_REDUZIERUNG_ARBEITSPREIS_MODUL_2"`  |             |
| `"ANREIZMODUL_ZEITVARIABLES_NETZENTGELT_MODUL_3"` |             |

## datenqualitaet



`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Marktlokation](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

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

*   defined in: [Marktlokation](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))

## marktrollen



`marktrollen`

*   is optional

*   Type: `object[]` ([Marktteilnehmer](marktteilnehmer.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-marktrollen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/marktrollen")

### marktrollen Type

`object[]` ([Marktteilnehmer](marktteilnehmer.md))

## zaehlwerke



`zaehlwerke`

*   is optional

*   Type: `object[]` ([Zaehlwerk](zaehlwerk.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/zaehlwerke")

### zaehlwerke Type

`object[]` ([Zaehlwerk](zaehlwerk.md))

## zaehlwerkeBeteiligteMarktrolle



`zaehlwerkeBeteiligteMarktrolle`

*   is optional

*   Type: `string[]` ([Marktrolle](marktrolle.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-zaehlwerkebeteiligtemarktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/zaehlwerkeBeteiligteMarktrolle")

### zaehlwerkeBeteiligteMarktrolle Type

`string[]` ([Marktrolle](marktrolle.md))

## verbrauchsmenge



`verbrauchsmenge`

*   is optional

*   Type: `object[]` ([Verbrauch](verbrauch.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-verbrauchsmenge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/verbrauchsmenge")

### verbrauchsmenge Type

`object[]` ([Verbrauch](verbrauch.md))

## zugehoerigeMesslokationen



`zugehoerigeMesslokationen`

*   is optional

*   Type: `object[]` ([Messlokationszuordnung](messlokationszuordnung.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-zugehoerigemesslokationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/zugehoerigeMesslokationen")

### zugehoerigeMesslokationen Type

`object[]` ([Messlokationszuordnung](messlokationszuordnung.md))

## netznutzungsabrechnungsdaten



`netznutzungsabrechnungsdaten`

*   is optional

*   Type: `object[]` ([Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-netznutzungsabrechnungsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/netznutzungsabrechnungsdaten")

### netznutzungsabrechnungsdaten Type

`object[]` ([Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten.md))

## messstellenbetriebsabrechnungsdaten



`messstellenbetriebsabrechnungsdaten`

*   is optional

*   Type: `object[]` ([Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-messstellenbetriebsabrechnungsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/messstellenbetriebsabrechnungsdaten")

### messstellenbetriebsabrechnungsdaten Type

`object[]` ([Messstellenbetriebsabrechnungsdaten](messstellenbetriebsabrechnungsdaten.md))

## energieherkunft



`energieherkunft`

*   is optional

*   Type: `object[]` ([Energieherkunft](energieherkunft.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-energieherkunft.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/energieherkunft")

### energieherkunft Type

`object[]` ([Energieherkunft](energieherkunft.md))

## erforderlichesProduktpaket



`erforderlichesProduktpaket`

*   is optional

*   Type: `object[]` ([Produktpaket](produktpaket.md))

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-erforderlichesproduktpaket.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/erforderlichesProduktpaket")

### erforderlichesProduktpaket Type

`object[]` ([Produktpaket](produktpaket.md))

## geokoordinaten



`geokoordinaten`

*   is optional

*   Type: `object` ([Geokoordinaten](geokoordinaten.md))

*   cannot be null

*   defined in: [Marktlokation](geokoordinaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/geokoordinaten")

### geokoordinaten Type

`object` ([Geokoordinaten](geokoordinaten.md))

## paketId



`paketId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktlokation](marktlokation-properties-paketid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktlokation.schema.json#/properties/paketId")

### paketId Type

`string`
