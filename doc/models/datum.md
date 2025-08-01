
# Datum

## Structure

`Datum`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `flight_date` | `str` | Required | - |
| `flight_status` | `str` | Required | - |
| `departure` | [`Departure`](../../doc/models/departure.md) | Required | - |
| `arrival` | [`Arrival`](../../doc/models/arrival.md) | Required | - |
| `airline` | [`Airline`](../../doc/models/airline.md) | Required | - |
| `flight` | [`Flight`](../../doc/models/flight.md) | Required | - |
| `aircraft` | `str` | Required | - |
| `live` | `str` | Required | - |

## Example (as JSON)

```json
{
  "flight_date": "flight_date8",
  "flight_status": "flight_status8",
  "departure": {
    "airport": "airport6",
    "timezone": "timezone0",
    "iata": "iata6",
    "icao": "icao4",
    "terminal": "terminal8",
    "gate": "gate6",
    "delay": "String3",
    "scheduled": "scheduled8",
    "estimated": "estimated6",
    "actual": "actual6",
    "estimated_runway": "estimated_runway6",
    "actual_runway": "actual_runway6"
  },
  "arrival": {
    "airport": "Shanghai Pudong International",
    "timezone": "Asia/Shanghai",
    "iata": "PVG",
    "icao": "ZSPD",
    "terminal": "2",
    "gate": "gate2",
    "baggage": "baggage2",
    "delay": "delay8",
    "scheduled": "2024-08-17T05:00:00+00:00",
    "estimated": "2024-08-17T05:00:00+00:00",
    "actual": "actual2",
    "estimated_runway": "estimated_runway2",
    "actual_runway": "actual_runway8"
  },
  "airline": {
    "name": "Peach Aviation",
    "iata": "MM",
    "icao": "APJ"
  },
  "flight": {
    "number": "number4",
    "iata": "iata8",
    "icao": "icao8",
    "codeshared": {
      "airline_name": "t'way air",
      "airline_iata": "tw",
      "airline_icao": "twb",
      "flight_number": "176",
      "flight_iata": "tw176",
      "flight_icao": "twb176"
    }
  },
  "aircraft": "aircraft4",
  "live": "live4"
}
```

