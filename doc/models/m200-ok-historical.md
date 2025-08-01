
# M200 OK Historical

## Structure

`M200OKHistorical`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `pagination` | [`Pagination`](../../doc/models/pagination.md) | Required | - |
| `data` | [`List[Datum2]`](../../doc/models/datum-2.md) | Required | - |

## Example (as JSON)

```json
{
  "pagination": {
    "limit": 100,
    "offset": 0,
    "count": 100,
    "total": 16069978
  },
  "data": [
    {
      "flight_date": "flight_date6",
      "flight_status": "flight_status6",
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
      "live": "live2"
    }
  ]
}
```

