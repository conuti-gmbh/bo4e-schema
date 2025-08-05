## Tranche Type

`object` ([Tranche](tranche.md))

# Tranche Properties

| Property                                                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :---------------------------------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                   | `string`  | Required | cannot be null | [Tranche](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                      |
| [versionStruktur](#versionstruktur)                               | `string`  | Required | cannot be null | [Tranche](tranche-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/versionStruktur")                               |
| [tranchenId](#tranchenid)                                         | `string`  | Optional | cannot be null | [Tranche](tranche-properties-tranchenid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/tranchenId")                                         |
| [sparte](#sparte)                                                 | `string`  | Optional | cannot be null | [Tranche](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")                                                                   |
| [energierichtung](#energierichtung)                               | `string`  | Optional | cannot be null | [Tranche](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")                                        |
| [bilanzierungsmethode](#bilanzierungsmethode)                     | `string`  | Optional | cannot be null | [Tranche](bilanzierungsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bilanzierungsmethode.schema.json#/properties/bilanzierungsmethode")                         |
| [verbrauchsart](#verbrauchsart)                                   | `array`   | Optional | can be null    | [Tranche](tranche-properties-verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/verbrauchsart")                                   |
| [unterbrechbar](#unterbrechbar)                                   | `boolean` | Optional | cannot be null | [Tranche](tranche-properties-unterbrechbar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/unterbrechbar")                                   |
| [netzebene](#netzebene)                                           | `string`  | Optional | cannot be null | [Tranche](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/netzebene")                                                          |
| [netzbetreiberCodeNr](#netzbetreibercodenr)                       | `string`  | Optional | cannot be null | [Tranche](tranche-properties-netzbetreibercodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/netzbetreiberCodeNr")                       |
| [gebietTyp](#gebiettyp)                                           | `string`  | Optional | cannot be null | [Tranche](gebiettyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gebiettyp.schema.json#/properties/gebietTyp")                                                          |
| [netzgebietNr](#netzgebietnr)                                     | `string`  | Optional | cannot be null | [Tranche](tranche-properties-netzgebietnr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/netzgebietNr")                                     |
| [bilanzierungsgebiet](#bilanzierungsgebiet)                       | `string`  | Optional | cannot be null | [Tranche](tranche-properties-bilanzierungsgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/bilanzierungsgebiet")                       |
| [grundversorgerCodeNr](#grundversorgercodenr)                     | `string`  | Optional | cannot be null | [Tranche](tranche-properties-grundversorgercodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/grundversorgerCodeNr")                     |
| [gasqualitaet](#gasqualitaet)                                     | `string`  | Optional | cannot be null | [Tranche](gasqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gasqualitaet.schema.json#/properties/gasqualitaet")                                                 |
| [endkunde](#endkunde)                                             | `object`  | Optional | cannot be null | [Tranche](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/endkunde")                                             |
| [lokationsadresse](#lokationsadresse)                             | `object`  | Optional | cannot be null | [Tranche](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/lokationsadresse")                                                        |
| [katasterinformation](#katasterinformation)                       | `object`  | Optional | cannot be null | [Tranche](katasteradresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Katasteradresse.schema.json#/properties/katasterinformation")                                     |
| [regelzone](#regelzone)                                           | `string`  | Optional | cannot be null | [Tranche](tranche-properties-regelzone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/regelzone")                                           |
| [marktgebiet](#marktgebiet)                                       | `string`  | Optional | cannot be null | [Tranche](tranche-properties-marktgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/marktgebiet")                                       |
| [zeitreihentyp](#zeitreihentyp)                                   | `string`  | Optional | cannot be null | [Tranche](zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeitreihentyp.schema.json#/properties/zeitreihentyp")                                              |
| [messtechnischeEinordnung](#messtechnischeeinordnung)             | `string`  | Optional | cannot be null | [Tranche](messtechnischeeinordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MesstechnischeEinordnung.schema.json#/properties/messtechnischeEinordnung")             |
| [sperrstatus](#sperrstatus)                                       | `string`  | Optional | cannot be null | [Tranche](sperrstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrstatus.schema.json#/properties/sperrstatus")                                                    |
| [referenzMarktlokationsId](#referenzmarktlokationsid)             | `string`  | Optional | cannot be null | [Tranche](tranche-properties-referenzmarktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/referenzMarktlokationsId")             |
| [versorgungsart](#versorgungsart)                                 | `string`  | Optional | cannot be null | [Tranche](versorgungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Versorgungsart.schema.json#/properties/versorgungsart")                                           |
| [fernsteuerbarkeit](#fernsteuerbarkeit)                           | `string`  | Optional | cannot be null | [Tranche](fernsteuerbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fernsteuerbarkeit.schema.json#/properties/fernsteuerbarkeit")                                  |
| [verguetungEmpfaenger](#verguetungempfaenger)                     | `string`  | Optional | cannot be null | [Tranche](verguetungempfaenger.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/VerguetungEmpfaenger.schema.json#/properties/verguetungEmpfaenger")                         |
| [foerderungsLand](#foerderungsland)                               | `string`  | Optional | cannot be null | [Tranche](tranche-properties-foerderungsland.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/foerderungsLand")                               |
| [statusErzeugendeMalo](#statuserzeugendemalo)                     | `string`  | Optional | cannot be null | [Tranche](statuserzeugendemarktlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/StatusErzeugendeMarktlokation.schema.json#/properties/statusErzeugendeMalo")       |
| [referenzTranche](#referenztranche)                               | `string`  | Optional | cannot be null | [Tranche](tranche-properties-referenztranche.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/referenzTranche")                               |
| [aufteilungsmenge](#aufteilungsmenge)                             | `object`  | Optional | cannot be null | [Tranche](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/aufteilungsmenge")                                                            |
| [bilanzkreis](#bilanzkreis)                                       | `string`  | Optional | cannot be null | [Tranche](tranche-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/bilanzkreis")                                       |
| [bildungTranchengroesse](#bildungtranchengroesse)                 | `string`  | Optional | cannot be null | [Tranche](bildungtranchengroesse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BildungTranchengroesse.schema.json#/properties/bildungTranchengroesse")                   |
| [zukuenftigerMeldepunkt](#zukuenftigermeldepunkt)                 | `boolean` | Optional | cannot be null | [Tranche](tranche-properties-zukuenftigermeldepunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/zukuenftigerMeldepunkt")                 |
| [lokationszuordnung](#lokationszuordnung)                         | `string`  | Optional | cannot be null | [Tranche](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")                               |
| [beteiligterMarktpartner](#beteiligtermarktpartner)               | `object`  | Optional | cannot be null | [Tranche](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/beteiligterMarktpartner")                                  |
| [marktrollen](#marktrollen)                                       | `array`   | Optional | can be null    | [Tranche](tranche-properties-marktrollen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/marktrollen")                                       |
| [zaehlwerke](#zaehlwerke)                                         | `array`   | Optional | can be null    | [Tranche](tranche-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/zaehlwerke")                                         |
| [zaehlwerkeBeteiligteMarktrolle](#zaehlwerkebeteiligtemarktrolle) | `array`   | Optional | can be null    | [Tranche](tranche-properties-zaehlwerkebeteiligtemarktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/zaehlwerkeBeteiligteMarktrolle") |
| [verbrauchsmenge](#verbrauchsmenge)                               | `array`   | Optional | can be null    | [Tranche](tranche-properties-verbrauchsmenge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/verbrauchsmenge")                               |
| [zugehoerigeMesslokationen](#zugehoerigemesslokationen)           | `array`   | Optional | can be null    | [Tranche](tranche-properties-zugehoerigemesslokationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/zugehoerigeMesslokationen")           |
| [netznutzungsabrechnungsdaten](#netznutzungsabrechnungsdaten)     | `array`   | Optional | can be null    | [Tranche](tranche-properties-netznutzungsabrechnungsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/netznutzungsabrechnungsdaten")     |
| [energieherkunft](#energieherkunft)                               | `array`   | Optional | can be null    | [Tranche](tranche-properties-energieherkunft.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/energieherkunft")                               |
| [datenqualitaet](#datenqualitaet)                                 | `string`  | Optional | cannot be null | [Tranche](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")                                           |
| [gueltigkeitszeitraum](#gueltigkeitszeitraum)                     | `object`  | Optional | cannot be null | [Tranche](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")                                                  |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Tranche](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"TRANCHE"
```

## versionStruktur

versionStruktur

`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## tranchenId

tranchenId

`tranchenId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-tranchenid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/tranchenId")

### tranchenId Type

`string`

## sparte

Sparte

`sparte`

*   is optional

*   Type: `string` ([Sparte](sparte.md))

*   cannot be null

*   defined in: [Tranche](sparte.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sparte.schema.json#/properties/sparte")

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

## energierichtung

Spezifiziert die Energierichtung einer Markt- und/oder Messlokation

`energierichtung`

*   is optional

*   Type: `string` ([Energierichtung](energierichtung.md))

*   cannot be null

*   defined in: [Tranche](energierichtung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Energierichtung.schema.json#/properties/energierichtung")

### energierichtung Type

`string` ([Energierichtung](energierichtung.md))

### energierichtung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"AUSSP"` |             |
| `"EINSP"` |             |

## bilanzierungsmethode

Mit dieser Aufzählung kann zwischen den Bilanzierungsmethoden bzw. -grundlagen unterschieden werden.

`bilanzierungsmethode`

*   is optional

*   Type: `string` ([Bilanzierungsmethode](bilanzierungsmethode.md))

*   cannot be null

*   defined in: [Tranche](bilanzierungsmethode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Bilanzierungsmethode.schema.json#/properties/bilanzierungsmethode")

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

Stromverbrauchsart/Verbrauchsart

`verbrauchsart`

*   is optional

*   Type: `string[]` ([Verbrauchsart](verbrauchsart.md))

*   can be null

*   defined in: [Tranche](tranche-properties-verbrauchsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/verbrauchsart")

### verbrauchsart Type

`string[]` ([Verbrauchsart](verbrauchsart.md))

## unterbrechbar

unterbrechbar

`unterbrechbar`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Tranche](tranche-properties-unterbrechbar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/unterbrechbar")

### unterbrechbar Type

`boolean`

## netzebene

Netzebene

`netzebene`

*   is optional

*   Type: `string` ([Netzebene](netzebene.md))

*   cannot be null

*   defined in: [Tranche](netzebene.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Netzebene.schema.json#/properties/netzebene")

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

## netzbetreiberCodeNr

netzbetreiberCodeNr

`netzbetreiberCodeNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-netzbetreibercodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/netzbetreiberCodeNr")

### netzbetreiberCodeNr Type

`string`

## gebietTyp

Gebiettyp

`gebietTyp`

*   is optional

*   Type: `string` ([Gebiettyp](gebiettyp.md))

*   cannot be null

*   defined in: [Tranche](gebiettyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gebiettyp.schema.json#/properties/gebietTyp")

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

netzgebietNr

`netzgebietNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-netzgebietnr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/netzgebietNr")

### netzgebietNr Type

`string`

## bilanzierungsgebiet

bilanzierungsgebiet

`bilanzierungsgebiet`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-bilanzierungsgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/bilanzierungsgebiet")

### bilanzierungsgebiet Type

`string`

## grundversorgerCodeNr

grundversorgerCodeNr

`grundversorgerCodeNr`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-grundversorgercodenr.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/grundversorgerCodeNr")

### grundversorgerCodeNr Type

`string`

## gasqualitaet

Unterscheidung für hoch- und niedrig-kalorisches Gas.

`gasqualitaet`

*   is optional

*   Type: `string` ([Gasqualitaet](gasqualitaet.md))

*   cannot be null

*   defined in: [Tranche](gasqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Gasqualitaet.schema.json#/properties/gasqualitaet")

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

*   defined in: [Tranche](geschaeftspartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Geschaeftspartner.schema.json#/properties/endkunde")

### endkunde Type

`object` ([Geschaeftspartner](geschaeftspartner.md))

## lokationsadresse



`lokationsadresse`

*   is optional

*   Type: `object` ([Adresse](adresse.md))

*   cannot be null

*   defined in: [Tranche](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/lokationsadresse")

### lokationsadresse Type

`object` ([Adresse](adresse.md))

## katasterinformation



`katasterinformation`

*   is optional

*   Type: `object` ([Katasteradresse](katasteradresse.md))

*   cannot be null

*   defined in: [Tranche](katasteradresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Katasteradresse.schema.json#/properties/katasterinformation")

### katasterinformation Type

`object` ([Katasteradresse](katasteradresse.md))

## regelzone

regelzone

`regelzone`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-regelzone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/regelzone")

### regelzone Type

`string`

## marktgebiet

marktgebiet

`marktgebiet`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-marktgebiet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/marktgebiet")

### marktgebiet Type

`string`

## zeitreihentyp



`zeitreihentyp`

*   is optional

*   Type: `string` ([Zeitreihentyp](zeitreihentyp.md))

*   cannot be null

*   defined in: [Tranche](zeitreihentyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zeitreihentyp.schema.json#/properties/zeitreihentyp")

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
| `"AUS"`     |             |
| `"BAS"`     |             |
| `"DBA"`     |             |
| `"DZR"`     |             |
| `"DZÜ"`     |             |
| `"FPE"`     |             |
| `"FPI"`     |             |
| `"SRE"`     |             |
| `"SRI"`     |             |
| `"VZR"`     |             |
| `"BIL"`     |             |
| `"BIP"`     |             |
| `"BIT"`     |             |
| `"GAL"`     |             |
| `"GAP"`     |             |
| `"GAT"`     |             |
| `"GEL"`     |             |
| `"GEP"`     |             |
| `"GET"`     |             |
| `"SOL"`     |             |
| `"SOP"`     |             |
| `"SOT"`     |             |
| `"WFL"`     |             |
| `"WFP"`     |             |
| `"WNL"`     |             |
| `"WNP"`     |             |
| `"WNT"`     |             |
| `"WAL"`     |             |
| `"WAP"`     |             |
| `"WAT"`     |             |
| `"AU1"`     |             |
| `"BI1"`     |             |
| `"BI2"`     |             |
| `"BI3"`     |             |
| `"GAA"`     |             |
| `"GAB"`     |             |
| `"GAC"`     |             |
| `"GE1"`     |             |
| `"GE2"`     |             |
| `"GE3"`     |             |
| `"SO1"`     |             |
| `"SO2"`     |             |
| `"SO3"`     |             |
| `"WF1"`     |             |
| `"WF2"`     |             |
| `"WF3"`     |             |
| `"WN1"`     |             |
| `"WN2"`     |             |
| `"WN3"`     |             |
| `"WAA"`     |             |
| `"WAB"`     |             |
| `"WAC"`     |             |

## messtechnischeEinordnung

MesstechnischeEinordnung

`messtechnischeEinordnung`

*   is optional

*   Type: `string` ([MesstechnischeEinordnung](messtechnischeeinordnung.md))

*   cannot be null

*   defined in: [Tranche](messtechnischeeinordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MesstechnischeEinordnung.schema.json#/properties/messtechnischeEinordnung")

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

Sperrstatus

`sperrstatus`

*   is optional

*   Type: `string` ([Sperrstatus](sperrstatus.md))

*   cannot be null

*   defined in: [Tranche](sperrstatus.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Sperrstatus.schema.json#/properties/sperrstatus")

### sperrstatus Type

`string` ([Sperrstatus](sperrstatus.md))

### sperrstatus Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"ENTSPERRT"` |             |
| `"GESPERRT"`  |             |

## referenzMarktlokationsId

referenzMarktlokationsId

`referenzMarktlokationsId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-referenzmarktlokationsid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/referenzMarktlokationsId")

### referenzMarktlokationsId Type

`string`

## versorgungsart

Versorgungsart

`versorgungsart`

*   is optional

*   Type: `string` ([Versorgungsart](versorgungsart.md))

*   cannot be null

*   defined in: [Tranche](versorgungsart.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Versorgungsart.schema.json#/properties/versorgungsart")

### versorgungsart Type

`string` ([Versorgungsart](versorgungsart.md))

### versorgungsart Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                 | Explanation |
| :-------------------- | :---------- |
| `"ERSATZVERSORGUNG"`  |             |
| `"GRUNDVERSORGUNG"`   |             |
| `"ERSATZBELIEFERUNG"` |             |

## fernsteuerbarkeit

Fernsteuerbarkeit

`fernsteuerbarkeit`

*   is optional

*   Type: `string` ([Fernsteuerbarkeit](fernsteuerbarkeit.md))

*   cannot be null

*   defined in: [Tranche](fernsteuerbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Fernsteuerbarkeit.schema.json#/properties/fernsteuerbarkeit")

### fernsteuerbarkeit Type

`string` ([Fernsteuerbarkeit](fernsteuerbarkeit.md))

### fernsteuerbarkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                             | Explanation |
| :-------------------------------- | :---------- |
| `"TECHNISCH_NICHT_FERNSTEUERBAR"` |             |
| `"TECHNISCH_FERNSTEUERBAR"`       |             |
| `"DURCH_LF_FERNSTEUERBAR"`        |             |

## verguetungEmpfaenger

VerguetungEmpfaenger

`verguetungEmpfaenger`

*   is optional

*   Type: `string` ([VerguetungEmpfaenger](verguetungempfaenger.md))

*   cannot be null

*   defined in: [Tranche](verguetungempfaenger.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/VerguetungEmpfaenger.schema.json#/properties/verguetungEmpfaenger")

### verguetungEmpfaenger Type

`string` ([VerguetungEmpfaenger](verguetungempfaenger.md))

### verguetungEmpfaenger Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"KUNDE"`     |             |
| `"LIEFERANT"` |             |

## foerderungsLand

foerderungsLand

`foerderungsLand`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-foerderungsland.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/foerderungsLand")

### foerderungsLand Type

`string`

## statusErzeugendeMalo

StatusErzeugendeMarktlokation

`statusErzeugendeMalo`

*   is optional

*   Type: `string` ([StatusErzeugendeMarktlokation](statuserzeugendemarktlokation.md))

*   cannot be null

*   defined in: [Tranche](statuserzeugendemarktlokation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/StatusErzeugendeMarktlokation.schema.json#/properties/statusErzeugendeMalo")

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

## referenzTranche

referenzTranche

`referenzTranche`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-referenztranche.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/referenzTranche")

### referenzTranche Type

`string`

## aufteilungsmenge

Prozentualer Anteil der Tranche an der erzeugenden Marktlokation in Prozent mit 2 Nachkommastellen

`aufteilungsmenge`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Tranche](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/aufteilungsmenge")

### aufteilungsmenge Type

`object` ([Menge](menge.md))

## bilanzkreis

bilanzkreis

`bilanzkreis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Tranche](tranche-properties-bilanzkreis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/bilanzkreis")

### bilanzkreis Type

`string`

## bildungTranchengroesse

BildungTranchengroesse

`bildungTranchengroesse`

*   is optional

*   Type: `string` ([BildungTranchengroesse](bildungtranchengroesse.md))

*   cannot be null

*   defined in: [Tranche](bildungtranchengroesse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BildungTranchengroesse.schema.json#/properties/bildungTranchengroesse")

### bildungTranchengroesse Type

`string` ([BildungTranchengroesse](bildungtranchengroesse.md))

### bildungTranchengroesse Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                 | Explanation |
| :-------------------- | :---------- |
| `"PROZENTUAL"`        |             |
| `"AUFTEILUNGSFAKTOR"` |             |

## zukuenftigerMeldepunkt

zukuenftigerMeldepunkt

`zukuenftigerMeldepunkt`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Tranche](tranche-properties-zukuenftigermeldepunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/zukuenftigerMeldepunkt")

### zukuenftigerMeldepunkt Type

`boolean`

## lokationszuordnung

Lokationszuordnung

`lokationszuordnung`

*   is optional

*   Type: `string` ([Lokationszuordnung](lokationszuordnung.md))

*   cannot be null

*   defined in: [Tranche](lokationszuordnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Lokationszuordnung.schema.json#/properties/lokationszuordnung")

### lokationszuordnung Type

`string` ([Lokationszuordnung](lokationszuordnung.md))

### lokationszuordnung Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"UNVERAENDERT"` |             |
| `"BEGINNT"`      |             |
| `"ENDET"`        |             |

## beteiligterMarktpartner



`beteiligterMarktpartner`

*   is optional

*   Type: `object` ([Marktteilnehmer](marktteilnehmer.md))

*   cannot be null

*   defined in: [Tranche](marktteilnehmer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/beteiligterMarktpartner")

### beteiligterMarktpartner Type

`object` ([Marktteilnehmer](marktteilnehmer.md))

## marktrollen

marktrollen

`marktrollen`

*   is optional

*   Type: `object[]` ([Marktteilnehmer](marktteilnehmer.md))

*   can be null

*   defined in: [Tranche](tranche-properties-marktrollen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/marktrollen")

### marktrollen Type

`object[]` ([Marktteilnehmer](marktteilnehmer.md))

## zaehlwerke

zaehlwerke

`zaehlwerke`

*   is optional

*   Type: `object[]` ([Zaehlwerk](zaehlwerk.md))

*   can be null

*   defined in: [Tranche](tranche-properties-zaehlwerke.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/zaehlwerke")

### zaehlwerke Type

`object[]` ([Zaehlwerk](zaehlwerk.md))

## zaehlwerkeBeteiligteMarktrolle

zaehlwerkeBeteiligteMarktrolle

`zaehlwerkeBeteiligteMarktrolle`

*   is optional

*   Type: `string[]` ([Marktrolle](marktrolle.md))

*   can be null

*   defined in: [Tranche](tranche-properties-zaehlwerkebeteiligtemarktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/zaehlwerkeBeteiligteMarktrolle")

### zaehlwerkeBeteiligteMarktrolle Type

`string[]` ([Marktrolle](marktrolle.md))

## verbrauchsmenge

verbrauchsmenge

`verbrauchsmenge`

*   is optional

*   Type: `object[]` ([Verbrauch](verbrauch.md))

*   can be null

*   defined in: [Tranche](tranche-properties-verbrauchsmenge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/verbrauchsmenge")

### verbrauchsmenge Type

`object[]` ([Verbrauch](verbrauch.md))

## zugehoerigeMesslokationen

zugehoerigeMesslokationen

`zugehoerigeMesslokationen`

*   is optional

*   Type: `object[]` ([Messlokationszuordnung](messlokationszuordnung.md))

*   can be null

*   defined in: [Tranche](tranche-properties-zugehoerigemesslokationen.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/zugehoerigeMesslokationen")

### zugehoerigeMesslokationen Type

`object[]` ([Messlokationszuordnung](messlokationszuordnung.md))

## netznutzungsabrechnungsdaten

netznutzungsabrechnungsdaten

`netznutzungsabrechnungsdaten`

*   is optional

*   Type: `object[]` ([Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten.md))

*   can be null

*   defined in: [Tranche](tranche-properties-netznutzungsabrechnungsdaten.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/netznutzungsabrechnungsdaten")

### netznutzungsabrechnungsdaten Type

`object[]` ([Netznutzungsabrechnungsdaten](netznutzungsabrechnungsdaten.md))

## energieherkunft

energieherkunft

`energieherkunft`

*   is optional

*   Type: `object[]` ([Energieherkunft](energieherkunft.md))

*   can be null

*   defined in: [Tranche](tranche-properties-energieherkunft.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Tranche.schema.json#/properties/energieherkunft")

### energieherkunft Type

`object[]` ([Energieherkunft](energieherkunft.md))

## datenqualitaet

Datenqualitaet

`datenqualitaet`

*   is optional

*   Type: `string` ([Datenqualitaet](datenqualitaet.md))

*   cannot be null

*   defined in: [Tranche](datenqualitaet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Datenqualitaet.schema.json#/properties/datenqualitaet")

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

*   defined in: [Tranche](zeitraum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitraum.schema.json#/properties/gueltigkeitszeitraum")

### gueltigkeitszeitraum Type

`object` ([Zeitraum](zeitraum.md))
