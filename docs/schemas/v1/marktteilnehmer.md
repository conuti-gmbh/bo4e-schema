## Marktteilnehmer Type

`object` ([Marktteilnehmer](marktteilnehmer.md))

# Marktteilnehmer Properties

| Property                                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                        |
| :------------------------------------------------------------------ | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [boTyp](#botyp)                                                     | `string`  | Required | cannot be null | [Marktteilnehmer](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")                                                                                |
| [versionStruktur](#versionstruktur)                                 | `string`  | Required | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/versionStruktur")                         |
| [geschaeftspartnerrolle](#geschaeftspartnerrolle)                   | `string`  | Optional | cannot be null | [Marktteilnehmer](geschaeftspartnerrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Geschaeftspartnerrolle.schema.json#/properties/geschaeftspartnerrolle")                             |
| [anrede](#anrede)                                                   | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-anrede.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/anrede")                                           |
| [name1](#name1)                                                     | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-name1.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/name1")                                             |
| [name2](#name2)                                                     | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-name2.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/name2")                                             |
| [name3](#name3)                                                     | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-name3.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/name3")                                             |
| [name4](#name4)                                                     | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-name4.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/name4")                                             |
| [partneradresse](#partneradresse)                                   | `object`  | Optional | cannot be null | [Marktteilnehmer](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/partneradresse")                                                                    |
| [gewerbekennzeichnung](#gewerbekennzeichnung)                       | `boolean` | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-gewerbekennzeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/gewerbekennzeichnung")               |
| [externeKundenummerLieferant](#externekundenummerlieferant)         | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-externekundenummerlieferant.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/externeKundenummerLieferant") |
| [marktrolle](#marktrolle)                                           | `string`  | Optional | cannot be null | [Marktteilnehmer](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/marktrolle")                                                                 |
| [rollencodenummer](#rollencodenummer)                               | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-rollencodenummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/rollencodenummer")                       |
| [rollencodetyp](#rollencodetyp)                                     | `string`  | Optional | cannot be null | [Marktteilnehmer](rollencodetyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Rollencodetyp.schema.json#/properties/rollencodetyp")                                                        |
| [umsatzsteuerId](#umsatzsteuerid)                                   | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-umsatzsteuerid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/umsatzsteuerId")                           |
| [steuernummer](#steuernummer)                                       | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-steuernummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/steuernummer")                               |
| [ansprechpartner](#ansprechpartner)                                 | `object`  | Optional | cannot be null | [Marktteilnehmer](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/ansprechpartner")                                                    |
| [makoadresse](#makoadresse)                                         | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-makoadresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/makoadresse")                                 |
| [downloadlinkZertifikat](#downloadlinkzertifikat)                   | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-downloadlinkzertifikat.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/downloadlinkZertifikat")           |
| [amtsgericht](#amtsgericht)                                         | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-amtsgericht.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/amtsgericht")                                 |
| [hrnummer](#hrnummer)                                               | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-hrnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/hrnummer")                                       |
| [website](#website)                                                 | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-website.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/website")                                         |
| [faxnummer](#faxnummer)                                             | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-faxnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/faxnummer")                                     |
| [kommunikationsrolle](#kommunikationsrolle)                         | `string`  | Optional | cannot be null | [Marktteilnehmer](kommunikationsrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Kommunikationsrolle.schema.json#/properties/kommunikationsrolle")                                      |
| [weiterverpflichtet](#weiterverpflichtet)                           | `boolean` | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-weiterverpflichtet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/weiterverpflichtet")                   |
| [kommunikationsparameter](#kommunikationsparameter)                 | `object`  | Optional | cannot be null | [Marktteilnehmer](kommunikationsparameter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Kommunikationsparameter.schema.json#/properties/kommunikationsparameter")                           |
| [messstellenbetreiberEigenschaft](#messstellenbetreibereigenschaft) | `string`  | Optional | cannot be null | [Marktteilnehmer](msbeigenschaft.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MSBEigenschaft.schema.json#/properties/messstellenbetreiberEigenschaft")                                    |
| [bankverbindung](#bankverbindung)                                   | `array`   | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-bankverbindung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/bankverbindung")                           |
| [erreichbarkeit](#erreichbarkeit)                                   | `array`   | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-erreichbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/erreichbarkeit")                           |
| [ipAdresse](#ipadresse)                                             | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-ipadresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/ipAdresse")                                     |
| [ipRange](#iprange)                                                 | `object`  | Optional | cannot be null | [Marktteilnehmer](iprange.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/IpRange.schema.json#/properties/ipRange")                                                                           |
| [zuordnungVon](#zuordnungvon)                                       | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-zuordnungvon.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/zuordnungVon")                               |
| [zuordnungBis](#zuordnungbis)                                       | `string`  | Optional | cannot be null | [Marktteilnehmer](marktteilnehmer-properties-zuordnungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/zuordnungBis")                               |

## boTyp

Typ des BO

`boTyp`

*   is required

*   Type: `string` ([BOTyp](botyp.md))

*   cannot be null

*   defined in: [Marktteilnehmer](botyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/BOTyp.schema.json#/properties/boTyp")

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
"MARKTTEILNEHMER"
```

## versionStruktur



`versionStruktur`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-versionstruktur.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/versionStruktur")

### versionStruktur Type

`string`

### versionStruktur Default Value

The default value is:

```json
"1"
```

## geschaeftspartnerrolle



`geschaeftspartnerrolle`

*   is optional

*   Type: `string` ([Geschaeftspartnerrolle](geschaeftspartnerrolle.md))

*   cannot be null

*   defined in: [Marktteilnehmer](geschaeftspartnerrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Geschaeftspartnerrolle.schema.json#/properties/geschaeftspartnerrolle")

### geschaeftspartnerrolle Type

`string` ([Geschaeftspartnerrolle](geschaeftspartnerrolle.md))

### geschaeftspartnerrolle Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                       | Explanation |
| :-------------------------- | :---------- |
| `"KUNDE"`                   |             |
| `"LIEFERANT"`               |             |
| `"DIENSTLEISTER"`           |             |
| `"INTERESSENT"`             |             |
| `"MARKTPARTNER"`            |             |
| `"EIGENTUEMER"`             |             |
| `"HAUSVERWALTER"`           |             |
| `"KORRESPONDENZEMPFAENGER"` |             |
| `"ABLESEKARTENEMPFAENGER"`  |             |

## anrede



`anrede`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-anrede.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/anrede")

### anrede Type

`string`

## name1



`name1`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-name1.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/name1")

### name1 Type

`string`

## name2



`name2`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-name2.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/name2")

### name2 Type

`string`

## name3



`name3`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-name3.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/name3")

### name3 Type

`string`

## name4



`name4`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-name4.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/name4")

### name4 Type

`string`

## partneradresse



`partneradresse`

*   is optional

*   Type: `object` ([Adresse](adresse.md))

*   cannot be null

*   defined in: [Marktteilnehmer](adresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/partneradresse")

### partneradresse Type

`object` ([Adresse](adresse.md))

## gewerbekennzeichnung



`gewerbekennzeichnung`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-gewerbekennzeichnung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/gewerbekennzeichnung")

### gewerbekennzeichnung Type

`boolean`

## externeKundenummerLieferant



`externeKundenummerLieferant`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-externekundenummerlieferant.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/externeKundenummerLieferant")

### externeKundenummerLieferant Type

`string`

## marktrolle



`marktrolle`

*   is optional

*   Type: `string` ([Marktrolle](marktrolle.md))

*   cannot be null

*   defined in: [Marktteilnehmer](marktrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Marktrolle.schema.json#/properties/marktrolle")

### marktrolle Type

`string` ([Marktrolle](marktrolle.md))

### marktrolle Constraints

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

## rollencodenummer



`rollencodenummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-rollencodenummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/rollencodenummer")

### rollencodenummer Type

`string`

## rollencodetyp



`rollencodetyp`

*   is optional

*   Type: `string` ([Rollencodetyp](rollencodetyp.md))

*   cannot be null

*   defined in: [Marktteilnehmer](rollencodetyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Rollencodetyp.schema.json#/properties/rollencodetyp")

### rollencodetyp Type

`string` ([Rollencodetyp](rollencodetyp.md))

### rollencodetyp Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"BDEW"` |             |
| `"GS1"`  |             |
| `"GLN"`  |             |
| `"DVGW"` |             |

## umsatzsteuerId



`umsatzsteuerId`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-umsatzsteuerid.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/umsatzsteuerId")

### umsatzsteuerId Type

`string`

## steuernummer



`steuernummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-steuernummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/steuernummer")

### steuernummer Type

`string`

## ansprechpartner



`ansprechpartner`

*   is optional

*   Type: `object` ([Ansprechpartner](ansprechpartner.md))

*   cannot be null

*   defined in: [Marktteilnehmer](ansprechpartner.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Ansprechpartner.schema.json#/properties/ansprechpartner")

### ansprechpartner Type

`object` ([Ansprechpartner](ansprechpartner.md))

## makoadresse



`makoadresse`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-makoadresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/makoadresse")

### makoadresse Type

`string`

## downloadlinkZertifikat



`downloadlinkZertifikat`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-downloadlinkzertifikat.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/downloadlinkZertifikat")

### downloadlinkZertifikat Type

`string`

## amtsgericht



`amtsgericht`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-amtsgericht.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/amtsgericht")

### amtsgericht Type

`string`

## hrnummer



`hrnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-hrnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/hrnummer")

### hrnummer Type

`string`

## website



`website`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-website.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/website")

### website Type

`string`

## faxnummer



`faxnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-faxnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/faxnummer")

### faxnummer Type

`string`

## kommunikationsrolle



`kommunikationsrolle`

*   is optional

*   Type: `string` ([Kommunikationsrolle](kommunikationsrolle.md))

*   cannot be null

*   defined in: [Marktteilnehmer](kommunikationsrolle.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Kommunikationsrolle.schema.json#/properties/kommunikationsrolle")

### kommunikationsrolle Type

`string` ([Kommunikationsrolle](kommunikationsrolle.md))

### kommunikationsrolle Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                     | Explanation |
| :------------------------ | :---------- |
| `"DATENAUSTAUSCH"`        |             |
| `"RAHMENVERTRAEGE"`       |             |
| `"KUENDIGUNGSPROZESSE"`   |             |
| `"WECHSELPROZESSE"`       |             |
| `"STAMMDATENPROZESSE"`    |             |
| `"EINSPEISEPROZESSE"`     |             |
| `"ABRECHNUNGSPROZESSE"`   |             |
| `"MMMA_PROZESSE"`         |             |
| `"BEWEGUNGSDATEN"`        |             |
| `"ENT_SPERR_PROZESSE"`    |             |
| `"BILANZIERUNGSPROZESSE"` |             |
| `"NETZANSCHLUSS_ANLAGEN"` |             |

## weiterverpflichtet



`weiterverpflichtet`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-weiterverpflichtet.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/weiterverpflichtet")

### weiterverpflichtet Type

`boolean`

## kommunikationsparameter



`kommunikationsparameter`

*   is optional

*   Type: `object` ([Kommunikationsparameter](kommunikationsparameter.md))

*   cannot be null

*   defined in: [Marktteilnehmer](kommunikationsparameter.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Kommunikationsparameter.schema.json#/properties/kommunikationsparameter")

### kommunikationsparameter Type

`object` ([Kommunikationsparameter](kommunikationsparameter.md))

## messstellenbetreiberEigenschaft



`messstellenbetreiberEigenschaft`

*   is optional

*   Type: `string` ([MSBEigenschaft](msbeigenschaft.md))

*   cannot be null

*   defined in: [Marktteilnehmer](msbeigenschaft.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/MSBEigenschaft.schema.json#/properties/messstellenbetreiberEigenschaft")

### messstellenbetreiberEigenschaft Type

`string` ([MSBEigenschaft](msbeigenschaft.md))

### messstellenbetreiberEigenschaft Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                      | Explanation |
| :----------------------------------------- | :---------- |
| `"GRUNDZUSTAENDIGER_MESSSTELLENBETREIBER"` |             |
| `"WETTBEWERBLICHER_MESSSTELLENBETREIBER"`  |             |
| `"AUFFANGMESSSTELLENBETREIBER"`            |             |

## bankverbindung



`bankverbindung`

*   is optional

*   Type: `object[]` ([Bankverbindung](bankverbindung.md))

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-bankverbindung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/bankverbindung")

### bankverbindung Type

`object[]` ([Bankverbindung](bankverbindung.md))

## erreichbarkeit



`erreichbarkeit`

*   is optional

*   Type: `object[]` ([Erreichbarkeit](erreichbarkeit.md))

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-erreichbarkeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/erreichbarkeit")

### erreichbarkeit Type

`object[]` ([Erreichbarkeit](erreichbarkeit.md))

## ipAdresse



`ipAdresse`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-ipadresse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/ipAdresse")

### ipAdresse Type

`string`

## ipRange



`ipRange`

*   is optional

*   Type: `object` ([IpRange](iprange.md))

*   cannot be null

*   defined in: [Marktteilnehmer](iprange.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/IpRange.schema.json#/properties/ipRange")

### ipRange Type

`object` ([IpRange](iprange.md))

## zuordnungVon

Startdatum der Zuordnung des Marktteilnehmers

`zuordnungVon`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-zuordnungvon.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/zuordnungVon")

### zuordnungVon Type

`string`

### zuordnungVon Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## zuordnungBis

Enddatum der Zuordnung des Marktteilnehmers

`zuordnungBis`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Marktteilnehmer](marktteilnehmer-properties-zuordnungbis.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/bo/Marktteilnehmer.schema.json#/properties/zuordnungBis")

### zuordnungBis Type

`string`

### zuordnungBis Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
