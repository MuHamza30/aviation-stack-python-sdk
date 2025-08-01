
# Datum 4

## Structure

`Datum4`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `departure` | [`Departure4`](../../doc/models/departure-4.md) | Required | - |
| `arrival` | [`Arrival4`](../../doc/models/arrival-4.md) | Required | - |
| `airline` | [`Airline4`](../../doc/models/airline-4.md) | Required | - |
| `flight` | [`Flight4`](../../doc/models/flight-4.md) | Required | - |

## Example (as JSON)

```json
{
  "departure": {
    "airport": "Viru Viru International",
    "timezone": "America/La_Paz",
    "iata": "VVI",
    "icao": "SLVR",
    "terminal": "terminal8",
    "time": "09:45:00"
  },
  "arrival": {
    "airport": "J Wilsterman",
    "timezone": "America/La_Paz",
    "iata": "CBB",
    "icao": "SLCB",
    "terminal": "terminal4",
    "time": "10:30:00"
  },
  "airline": {
    "name": "Compania de Servicios de Transporte Aereo Amaszonas - Amaszonas S.A",
    "callsign": "AMAZONAS",
    "iata": "Z8",
    "icao": "AZN"
  },
  "flight": {
    "number": "173"
  }
}
```

