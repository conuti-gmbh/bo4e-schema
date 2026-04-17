## Geokoordinaten Type

`object` ([Geokoordinaten](geokoordinaten.md))

# Geokoordinaten Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                      |
| :-------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [breitengrad](#breitengrad) | `string` | Optional | cannot be null | [Geokoordinaten](geokoordinaten-properties-breitengrad.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/breitengrad") |
| [laengengrad](#laengengrad) | `string` | Optional | cannot be null | [Geokoordinaten](geokoordinaten-properties-laengengrad.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/laengengrad") |
| [ostwert](#ostwert)         | `string` | Optional | cannot be null | [Geokoordinaten](geokoordinaten-properties-ostwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/ostwert")         |
| [nordwert](#nordwert)       | `string` | Optional | cannot be null | [Geokoordinaten](geokoordinaten-properties-nordwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/nordwert")       |
| [zone](#zone)               | `string` | Optional | cannot be null | [Geokoordinaten](zone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zone.schema.json#/properties/zone")                                                  |
| [hochwert](#hochwert)       | `string` | Optional | cannot be null | [Geokoordinaten](geokoordinaten-properties-hochwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/hochwert")       |
| [rechtswert](#rechtswert)   | `string` | Optional | cannot be null | [Geokoordinaten](geokoordinaten-properties-rechtswert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/rechtswert")   |

## breitengrad

Gibt den Breitengrad eines entsprechenden Ortes an.

`breitengrad`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geokoordinaten](geokoordinaten-properties-breitengrad.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/breitengrad")

### breitengrad Type

`string`

## laengengrad

Gibt den Längengrad eines entsprechenden Ortes an.

`laengengrad`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geokoordinaten](geokoordinaten-properties-laengengrad.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/laengengrad")

### laengengrad Type

`string`

## ostwert

Gibt den Ostwert eines entsprechenden Ortes an.

`ostwert`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geokoordinaten](geokoordinaten-properties-ostwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/ostwert")

### ostwert Type

`string`

## nordwert

Gibt den Nordwert eines entsprechenden Ortes an.

`nordwert`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geokoordinaten](geokoordinaten-properties-nordwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/nordwert")

### nordwert Type

`string`

## zone

Zone

`zone`

*   is optional

*   Type: `string` ([Zone](zone.md))

*   cannot be null

*   defined in: [Geokoordinaten](zone.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/enum/Zone.schema.json#/properties/zone")

### zone Type

`string` ([Zone](zone.md))

### zone Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"UTMZone31"` |             |
| `"UTMZone32"` |             |
| `"UTMZone33"` |             |

## hochwert

Gibt den Hochwert eines entsprechenden Ortes an.

`hochwert`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geokoordinaten](geokoordinaten-properties-hochwert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/hochwert")

### hochwert Type

`string`

## rechtswert

Gibt den Rechtswert eines entsprechenden Ortes an.

`rechtswert`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Geokoordinaten](geokoordinaten-properties-rechtswert.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Geokoordinaten.schema.json#/properties/rechtswert")

### rechtswert Type

`string`
