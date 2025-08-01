
# Datum 2

## Structure

`Datum2`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `flight_date` | `str` | Required | - |
| `flight_status` | `str` | Required | - |
| `departure` | [`Departure2`](../../doc/models/departure-2.md) | Required | - |
| `arrival` | [`Arrival2`](../../doc/models/arrival-2.md) | Required | - |
| `airline` | [`Airline2`](../../doc/models/airline-2.md) | Required | - |
| `flight` | [`Flight2`](../../doc/models/flight-2.md) | Required | - |
| `aircraft` | [Aircraft](../../doc/models/aircraft.md) \| None \| [Aircraft1](../../doc/models/aircraft-1.md) | Required | This is a container for one-of cases. |
| `live` | `str` | Required | - |

## Example (as JSON)

```json
{
  "flight_date": "flight_date0",
  "flight_status": "flight_status0",
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
    "airport": "airport2",
    "timezone": "timezone6",
    "iata": "iata0",
    "icao": "icao0",
    "terminal": "terminal4",
    "gate": "gate2",
    "baggage": "baggage2",
    "delay": "String9",
    "scheduled": "scheduled2",
    "estimated": "estimated2",
    "actual": "actual2",
    "estimated_runway": "estimated_runway2",
    "actual_runway": "actual_runway8"
  },
  "airline": {
    "name": "Astral Aviation",
    "iata": "8V",
    "icao": "ACP"
  },
  "flight": {
    "number": "number4",
    "iata": "iata8",
    "icao": "icao8",
    "codeshared": {
      "airline_name": "swiss",
      "airline_iata": "lx",
      "airline_icao": "swr",
      "flight_number": "41",
      "flight_iata": "lx41",
      "flight_icao": "swr41"
    }
  },
  "aircraft": {
    "registration": "A6-ECG",
    "iata": "B77W",
    "icao": "B77W",
    "icao24": "89610E"
  },
  "live": "live6"
}
```

