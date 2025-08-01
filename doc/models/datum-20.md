
# Datum 20

## Structure

`Datum20`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `airline` | [`Airline6`](../../doc/models/airline-6.md) | Required | - |
| `arrival` | [`Arrival6`](../../doc/models/arrival-6.md) | Required | - |
| `codeshared` | [Codeshared6](../../doc/models/codeshared-6.md) \| None \| [Codeshared61](../../doc/models/codeshared-61.md) | Required | This is a container for one-of cases. |
| `departure` | [`Departure6`](../../doc/models/departure-6.md) | Required | - |
| `flight` | [`Flight8`](../../doc/models/flight-8.md) | Required | - |
| `status` | `str` | Required | - |
| `mtype` | `str` | Required | - |

## Example (as JSON)

```json
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
  "status": "status8",
  "type": "type0"
}
```

