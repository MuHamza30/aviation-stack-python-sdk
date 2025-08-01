
# M200 OK Ream Time

## Structure

`M200OKReamTime`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `pagination` | [`Pagination`](../../doc/models/pagination.md) | Required | - |
| `data` | [`List[Datum]`](../../doc/models/datum.md) | Required | - |

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
      "aircraft": "aircraft2",
      "live": "live2"
    }
  ]
}
```

