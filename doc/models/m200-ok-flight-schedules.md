
# M200 OK Flight Schedules

## Structure

`M200OKFlightSchedules`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `pagination` | [`Pagination20`](../../doc/models/pagination-20.md) | Required | - |
| `data` | [`List[Datum20]`](../../doc/models/datum-20.md) | Required | - |

## Example (as JSON)

```json
{
  "pagination": {
    "limit": "limit2",
    "offset": "offset6",
    "count": 539,
    "total": 539
  },
  "data": [
    {
      "airline": {
        "iataCode": "7L",
        "icaoCode": "AZG",
        "name": "Silk Way West"
      },
      "arrival": {
        "actualRunway": "actualRunway2",
        "actualTime": "actualTime0",
        "baggage": "baggage2",
        "delay": "delay8",
        "estimatedRunway": "estimatedRunway6",
        "estimatedTime": "estimatedTime4",
        "gate": "gate2",
        "iataCode": "GYD",
        "icaoCode": "UBBB",
        "scheduledTime": "2024-08-16T19:27:00.000",
        "terminal": "terminal4"
      },
      "codeshared": {
        "airline": {
          "iataCode": "tk",
          "icaoCode": "thy",
          "name": "turkish airlines"
        },
        "flight": {
          "iataNumber": "tk12",
          "icaoNumber": "thy12",
          "number": "12"
        }
      },
      "departure": {
        "actualRunway": "actualRunway6",
        "actualTime": "actualTime6",
        "baggage": "baggage2",
        "delay": "125",
        "estimatedRunway": "estimatedRunway0",
        "estimatedTime": "2024-08-16T02:05:00.000",
        "gate": "gate6",
        "iataCode": "JFK",
        "icaoCode": "KJFK",
        "scheduledTime": "2024-08-16T00:00:00.000",
        "terminal": "terminal8"
      },
      "flight": {
        "iataNumber": "7L2786",
        "icaoNumber": "AZG2786",
        "number": "2786"
      },
      "status": "status2",
      "type": "type0"
    }
  ]
}
```

