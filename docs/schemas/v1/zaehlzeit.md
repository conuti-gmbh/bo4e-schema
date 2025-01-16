## Zaehlzeit Type

`object` ([Zaehlzeit](zaehlzeit.md))

# Zaehlzeit Properties

| Property                                                  | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                  |
| :-------------------------------------------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [code](#code)                                             | `string`  | Optional | cannot be null | [Zaehlzeit](zaehlzeit-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/code")                                          |
| [haeufigkeit](#haeufigkeit)                               | `string`  | Optional | cannot be null | [Zaehlzeit](haeufigkeitzaehlzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/HaeufigkeitZaehlzeit.schema.json#/properties/haeufigkeit")                            |
| [uebermittelbarkeit](#uebermittelbarkeit)                 | `string`  | Optional | cannot be null | [Zaehlzeit](uebermittelbarkeitzaehlzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/UebermittelbarkeitZaehlzeit.schema.json#/properties/uebermittelbarkeit")       |
| [ermittlungLeistungsmaximum](#ermittlungleistungsmaximum) | `string`  | Optional | cannot be null | [Zaehlzeit](ermittlungleistungsmaximum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ErmittlungLeistungsmaximum.schema.json#/properties/ermittlungLeistungsmaximum") |
| [istBestellbar](#istbestellbar)                           | `boolean` | Optional | cannot be null | [Zaehlzeit](zaehlzeit-properties-istbestellbar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/istBestellbar")                        |
| [typ](#typ)                                               | `string`  | Optional | cannot be null | [Zaehlzeit](zaehlzeitdefinitiontyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e/main/schemas/v1/enum/ZaehlzeitdefinitionTyp.schema.json#/properties/typ")                                         |
| [beschreibungTyp](#beschreibungtyp)                       | `string`  | Optional | cannot be null | [Zaehlzeit](zaehlzeit-properties-beschreibungtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/beschreibungTyp")                    |
| [aenderungszeitpunkt](#aenderungszeitpunkt)               | `string`  | Optional | cannot be null | [Zaehlzeit](zaehlzeit-properties-aenderungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/aenderungszeitpunkt")            |
| [register](#register)                                     | `string`  | Optional | cannot be null | [Zaehlzeit](zaehlzeit-properties-register.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/register")                                  |

## code

Zählzeitdefinition

`code`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeit](zaehlzeit-properties-code.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/code")

### code Type

`string`

## haeufigkeit

HaeufigkeitZaehlzeit

`haeufigkeit`

*   is optional

*   Type: `string` ([HaeufigkeitZaehlzeit](haeufigkeitzaehlzeit.md))

*   cannot be null

*   defined in: [Zaehlzeit](haeufigkeitzaehlzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/HaeufigkeitZaehlzeit.schema.json#/properties/haeufigkeit")

### haeufigkeit Type

`string` ([HaeufigkeitZaehlzeit](haeufigkeitzaehlzeit.md))

### haeufigkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"EINMALIG"`  |             |
| `"JAEHRLICH"` |             |

## uebermittelbarkeit

UebermittelbarkeitZaehlzeit

`uebermittelbarkeit`

*   is optional

*   Type: `string` ([UebermittelbarkeitZaehlzeit](uebermittelbarkeitzaehlzeit.md))

*   cannot be null

*   defined in: [Zaehlzeit](uebermittelbarkeitzaehlzeit.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/UebermittelbarkeitZaehlzeit.schema.json#/properties/uebermittelbarkeit")

### uebermittelbarkeit Type

`string` ([UebermittelbarkeitZaehlzeit](uebermittelbarkeitzaehlzeit.md))

### uebermittelbarkeit Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                  | Explanation |
| :--------------------- | :---------- |
| `"ELEKTRONISCH"`       |             |
| `"NICHT_ELEKTRONISCH"` |             |

## ermittlungLeistungsmaximum

ErmittlungLeistungsmaximum

`ermittlungLeistungsmaximum`

*   is optional

*   Type: `string` ([ErmittlungLeistungsmaximum](ermittlungleistungsmaximum.md))

*   cannot be null

*   defined in: [Zaehlzeit](ermittlungleistungsmaximum.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/ErmittlungLeistungsmaximum.schema.json#/properties/ermittlungLeistungsmaximum")

### ermittlungLeistungsmaximum Type

`string` ([ErmittlungLeistungsmaximum](ermittlungleistungsmaximum.md))

### ermittlungLeistungsmaximum Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                | Explanation |
| :----------------------------------- | :---------- |
| `"VERWENDUNG_HOCHLASTFENSTER"`       |             |
| `"KEINE_VERWENDUNG_HOCHLASTFENSTER"` |             |

## istBestellbar

Ist die Zählzeit bestellbar?

`istBestellbar`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Zaehlzeit](zaehlzeit-properties-istbestellbar.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/istBestellbar")

### istBestellbar Type

`boolean`

## typ

ZaehlzeitdefinitionTyp

`typ`

*   is optional

*   Type: `string` ([ZaehlzeitdefinitionTyp](zaehlzeitdefinitiontyp.md))

*   cannot be null

*   defined in: [Zaehlzeit](zaehlzeitdefinitiontyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e/main/schemas/v1/enum/ZaehlzeitdefinitionTyp.schema.json#/properties/typ")

### typ Type

`string` ([ZaehlzeitdefinitionTyp](zaehlzeitdefinitiontyp.md))

### typ Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                      | Explanation |
| :------------------------- | :---------- |
| `"WAERMEPUMPE"`            |             |
| `"NACHTSPEICHERHEIZUNG"`   |             |
| `"SCHWACHLASTZEITFENSTER"` |             |
| `"SONSTIGE"`               |             |
| `"HOCHLASTZEITFENSTER"`    |             |

## beschreibungTyp

Beschreibung des ZählzeitdefinitionTyp

`beschreibungTyp`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeit](zaehlzeit-properties-beschreibungtyp.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/beschreibungTyp")

### beschreibungTyp Type

`string`

## aenderungszeitpunkt

aenderungszeitpunkt

`aenderungszeitpunkt`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeit](zaehlzeit-properties-aenderungszeitpunkt.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/aenderungszeitpunkt")

### aenderungszeitpunkt Type

`string`

### aenderungszeitpunkt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## register

register

`register`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zaehlzeit](zaehlzeit-properties-register.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zaehlzeit.schema.json#/properties/register")

### register Type

`string`
