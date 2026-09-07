## Zeitreihenprodukt Type

`object` ([Zeitreihenprodukt](zeitreihenprodukt.md))

# Zeitreihenprodukt Properties

| Property                                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                       |
| :---------------------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [identifikation](#identifikation)                     | `string` | Optional | cannot be null | [Zeitreihenprodukt](zeitreihenprodukt-properties-identifikation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitreihenprodukt.schema.json#/properties/identifikation")   |
| [korrekturfaktor](#korrekturfaktor)                   | `number` | Optional | cannot be null | [Zeitreihenprodukt](zeitreihenprodukt-properties-korrekturfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitreihenprodukt.schema.json#/properties/korrekturfaktor") |
| [energiemenge](#energiemenge)                         | `object` | Optional | cannot be null | [Zeitreihenprodukt](verbrauch.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/energiemenge")                                               |
| [jahresverbrauchsprognose](#jahresverbrauchsprognose) | `object` | Optional | cannot be null | [Zeitreihenprodukt](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/jahresverbrauchsprognose")                                           |

## identifikation

Identifikation des Zeitreihenprodukts, z.B. OBIS-Kennzahl

`identifikation`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Zeitreihenprodukt](zeitreihenprodukt-properties-identifikation.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitreihenprodukt.schema.json#/properties/identifikation")

### identifikation Type

`string`

## korrekturfaktor

Gibt ggf. einen Korrekturfaktor für die Menge an.

`korrekturfaktor`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [Zeitreihenprodukt](zeitreihenprodukt-properties-korrekturfaktor.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Zeitreihenprodukt.schema.json#/properties/korrekturfaktor")

### korrekturfaktor Type

`number`

### korrekturfaktor Constraints

**unknown format**: the value of this string must follow the format: `float`

## energiemenge

Energiemenge des Zeitreihenprodukts im Bezugszeitraum

`energiemenge`

*   is optional

*   Type: `object` ([Verbrauch](verbrauch.md))

*   cannot be null

*   defined in: [Zeitreihenprodukt](verbrauch.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Verbrauch.schema.json#/properties/energiemenge")

### energiemenge Type

`object` ([Verbrauch](verbrauch.md))

## jahresverbrauchsprognose

Jahresverbrauchsprognose

`jahresverbrauchsprognose`

*   is optional

*   Type: `object` ([Menge](menge.md))

*   cannot be null

*   defined in: [Zeitreihenprodukt](menge.md "https://raw.githubusercontent.com/conuti-gmbh/bo4e-schema/master/schemas/v1/com/Menge.schema.json#/properties/jahresverbrauchsprognose")

### jahresverbrauchsprognose Type

`object` ([Menge](menge.md))
