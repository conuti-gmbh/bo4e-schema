## Adresse Type

`object` ([Adresse](adresse.md))

# Adresse Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                |
| :-------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [postleitzahl](#postleitzahl)           | `string` | Optional | cannot be null | [Adresse](adresse-properties-postleitzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/postleitzahl")              |
| [ort](#ort)                             | `string` | Optional | cannot be null | [Adresse](adresse-properties-ort.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/ort")                                |
| [strasse](#strasse)                     | `string` | Optional | cannot be null | [Adresse](adresse-properties-strasse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/strasse")                        |
| [hausnummer](#hausnummer)               | `string` | Optional | cannot be null | [Adresse](adresse-properties-hausnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/hausnummer")                  |
| [postfach](#postfach)                   | `string` | Optional | cannot be null | [Adresse](adresse-properties-postfach.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/postfach")                      |
| [adresszusatz](#adresszusatz)           | `string` | Optional | cannot be null | [Adresse](adresse-properties-adresszusatz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/adresszusatz")              |
| [coErgaenzung](#coergaenzung)           | `string` | Optional | cannot be null | [Adresse](adresse-properties-coergaenzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/coErgaenzung")              |
| [landescode](#landescode)               | `string` | Optional | cannot be null | [Adresse](landescode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Landescode.schema.json#/properties/landescode")                                 |
| [ortsteil](#ortsteil)                   | `string` | Optional | cannot be null | [Adresse](adresse-properties-ortsteil.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/ortsteil")                      |
| [zusatzInformation](#zusatzinformation) | `object` | Optional | cannot be null | [Adresse](adresszusatzinformation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AdresszusatzInformation.schema.json#/properties/zusatzInformation") |

## postleitzahl

Postleitzahl

`postleitzahl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Adresse](adresse-properties-postleitzahl.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/postleitzahl")

### postleitzahl Type

`string`

## ort

Ort

`ort`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Adresse](adresse-properties-ort.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/ort")

### ort Type

`string`

## strasse

Strasse

`strasse`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Adresse](adresse-properties-strasse.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/strasse")

### strasse Type

`string`

## hausnummer

Hausnummer und Ergänzung

`hausnummer`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Adresse](adresse-properties-hausnummer.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/hausnummer")

### hausnummer Type

`string`

## postfach

Postfach

`postfach`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Adresse](adresse-properties-postfach.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/postfach")

### postfach Type

`string`

## adresszusatz

Adresszusatz

`adresszusatz`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Adresse](adresse-properties-adresszusatz.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/adresszusatz")

### adresszusatz Type

`string`

## coErgaenzung

coErgaenzung

`coErgaenzung`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Adresse](adresse-properties-coergaenzung.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/coErgaenzung")

### coErgaenzung Type

`string`

## landescode

Der ISO-Landescode als Enumeration

`landescode`

*   is optional

*   Type: `string` ([Landescode](landescode.md))

*   cannot be null

*   defined in: [Adresse](landescode.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Landescode.schema.json#/properties/landescode")

### landescode Type

`string` ([Landescode](landescode.md))

### landescode Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value  | Explanation |
| :----- | :---------- |
| `"AC"` |             |
| `"AD"` |             |
| `"AE"` |             |
| `"AF"` |             |
| `"AG"` |             |
| `"AI"` |             |
| `"AL"` |             |
| `"AM"` |             |
| `"AN"` |             |
| `"AO"` |             |
| `"AQ"` |             |
| `"AR"` |             |
| `"AS"` |             |
| `"AT"` |             |
| `"AU"` |             |
| `"AW"` |             |
| `"AX"` |             |
| `"AZ"` |             |
| `"BA"` |             |
| `"BB"` |             |
| `"BD"` |             |
| `"BE"` |             |
| `"BF"` |             |
| `"BG"` |             |
| `"BH"` |             |
| `"BI"` |             |
| `"BJ"` |             |
| `"BL"` |             |
| `"BM"` |             |
| `"BN"` |             |
| `"BO"` |             |
| `"BQ"` |             |
| `"BR"` |             |
| `"BS"` |             |
| `"BT"` |             |
| `"BU"` |             |
| `"BV"` |             |
| `"BW"` |             |
| `"BY"` |             |
| `"BZ"` |             |
| `"CA"` |             |
| `"CC"` |             |
| `"CD"` |             |
| `"CF"` |             |
| `"CG"` |             |
| `"CH"` |             |
| `"CI"` |             |
| `"CK"` |             |
| `"CL"` |             |
| `"CM"` |             |
| `"CN"` |             |
| `"CO"` |             |
| `"CP"` |             |
| `"CR"` |             |
| `"CS"` |             |
| `"CU"` |             |
| `"CV"` |             |
| `"CW"` |             |
| `"CX"` |             |
| `"CY"` |             |
| `"CZ"` |             |
| `"DE"` |             |
| `"DG"` |             |
| `"DJ"` |             |
| `"DK"` |             |
| `"DM"` |             |
| `"DO"` |             |
| `"DZ"` |             |
| `"EA"` |             |
| `"EC"` |             |
| `"EE"` |             |
| `"EG"` |             |
| `"EH"` |             |
| `"ER"` |             |
| `"ES"` |             |
| `"ET"` |             |
| `"EU"` |             |
| `"FI"` |             |
| `"FJ"` |             |
| `"FK"` |             |
| `"FM"` |             |
| `"FO"` |             |
| `"FR"` |             |
| `"FX"` |             |
| `"GA"` |             |
| `"GB"` |             |
| `"GD"` |             |
| `"GE"` |             |
| `"GF"` |             |
| `"GG"` |             |
| `"GH"` |             |
| `"GI"` |             |
| `"GL"` |             |
| `"GM"` |             |
| `"GN"` |             |
| `"GP"` |             |
| `"GQ"` |             |
| `"GR"` |             |
| `"GS"` |             |
| `"GT"` |             |
| `"GU"` |             |
| `"GW"` |             |
| `"GY"` |             |
| `"HK"` |             |
| `"HM"` |             |
| `"HN"` |             |
| `"HR"` |             |
| `"HT"` |             |
| `"HU"` |             |
| `"IC"` |             |
| `"ID"` |             |
| `"IE"` |             |
| `"IL"` |             |
| `"IM"` |             |
| `"IN"` |             |
| `"IO"` |             |
| `"IQ"` |             |
| `"IR"` |             |
| `"IS"` |             |
| `"IT"` |             |
| `"JE"` |             |
| `"JM"` |             |
| `"JO"` |             |
| `"JP"` |             |
| `"KE"` |             |
| `"KG"` |             |
| `"KH"` |             |
| `"KI"` |             |
| `"KM"` |             |
| `"KN"` |             |
| `"KP"` |             |
| `"KR"` |             |
| `"KW"` |             |
| `"KY"` |             |
| `"KZ"` |             |
| `"LA"` |             |
| `"LB"` |             |
| `"LC"` |             |
| `"LI"` |             |
| `"LK"` |             |
| `"LR"` |             |
| `"LS"` |             |
| `"LT"` |             |
| `"LU"` |             |
| `"LV"` |             |
| `"LY"` |             |
| `"MA"` |             |
| `"MC"` |             |
| `"MD"` |             |
| `"ME"` |             |
| `"MF"` |             |
| `"MG"` |             |
| `"MH"` |             |
| `"MK"` |             |
| `"ML"` |             |
| `"MM"` |             |
| `"MN"` |             |
| `"MO"` |             |
| `"MP"` |             |
| `"MQ"` |             |
| `"MR"` |             |
| `"MS"` |             |
| `"MT"` |             |
| `"MU"` |             |
| `"MV"` |             |
| `"MW"` |             |
| `"MX"` |             |
| `"MY"` |             |
| `"MZ"` |             |
| `"NA"` |             |
| `"NC"` |             |
| `"NE"` |             |
| `"NF"` |             |
| `"NG"` |             |
| `"NI"` |             |
| `"NL"` |             |
| `"NO"` |             |
| `"NP"` |             |
| `"NR"` |             |
| `"NT"` |             |
| `"NU"` |             |
| `"NZ"` |             |
| `"OM"` |             |
| `"PA"` |             |
| `"PE"` |             |
| `"PF"` |             |
| `"PG"` |             |
| `"PH"` |             |
| `"PK"` |             |
| `"PL"` |             |
| `"PM"` |             |
| `"PN"` |             |
| `"PR"` |             |
| `"PS"` |             |
| `"PT"` |             |
| `"PW"` |             |
| `"PY"` |             |
| `"QA"` |             |
| `"RE"` |             |
| `"RO"` |             |
| `"RS"` |             |
| `"RU"` |             |
| `"RW"` |             |
| `"SA"` |             |
| `"SB"` |             |
| `"SC"` |             |
| `"SD"` |             |
| `"SE"` |             |
| `"SF"` |             |
| `"SG"` |             |
| `"SH"` |             |
| `"SI"` |             |
| `"SJ"` |             |
| `"SK"` |             |
| `"SL"` |             |
| `"SM"` |             |
| `"SN"` |             |
| `"SO"` |             |
| `"SR"` |             |
| `"SS"` |             |
| `"ST"` |             |
| `"SU"` |             |
| `"SV"` |             |
| `"SX"` |             |
| `"SY"` |             |
| `"SZ"` |             |
| `"TA"` |             |
| `"TC"` |             |
| `"TD"` |             |
| `"TF"` |             |
| `"TG"` |             |
| `"TJ"` |             |
| `"TK"` |             |
| `"TL"` |             |
| `"TM"` |             |
| `"TN"` |             |
| `"TO"` |             |
| `"TP"` |             |
| `"TR"` |             |
| `"TT"` |             |
| `"TV"` |             |
| `"TW"` |             |
| `"TZ"` |             |
| `"UA"` |             |
| `"UG"` |             |
| `"UK"` |             |
| `"UM"` |             |
| `"US"` |             |
| `"UY"` |             |
| `"UZ"` |             |
| `"VA"` |             |
| `"VC"` |             |
| `"VE"` |             |
| `"VG"` |             |
| `"VI"` |             |
| `"VN"` |             |
| `"VU"` |             |
| `"WF"` |             |
| `"WS"` |             |
| `"XK"` |             |
| `"YE"` |             |
| `"YT"` |             |
| `"YU"` |             |
| `"ZA"` |             |
| `"ZM"` |             |
| `"ZR"` |             |
| `"ZW"` |             |

## ortsteil

Ortsteil

`ortsteil`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Adresse](adresse-properties-ortsteil.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Adresse.schema.json#/properties/ortsteil")

### ortsteil Type

`string`

## zusatzInformation



`zusatzInformation`

*   is optional

*   Type: `object` ([AdresszusatzInformation](adresszusatzinformation.md))

*   cannot be null

*   defined in: [Adresse](adresszusatzinformation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/AdresszusatzInformation.schema.json#/properties/zusatzInformation")

### zusatzInformation Type

`object` ([AdresszusatzInformation](adresszusatzinformation.md))
