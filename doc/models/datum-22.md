
# Datum 22

## Structure

`Datum22`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `weekday` | `str` | Required | - |
| `departure` | [`Departure8`](../../doc/models/departure-8.md) | Required | - |
| `arrival` | [`Arrival8`](../../doc/models/arrival-8.md) | Required | - |
| `aircraft` | [`Aircraft4`](../../doc/models/aircraft-4.md) | Required | - |
| `airline` | [`Airline6`](../../doc/models/airline-6.md) | Required | - |
| `flight` | [`Flight6`](../../doc/models/flight-6.md) | Required | - |
| `codeshared` | [`Codeshared61`](../../doc/models/codeshared-61.md) | Optional | - |

## Example (as JSON)

```json
{
  "weekday": "2",
  "departure": {
    "iataCode": "jfk",
    "icaoCode": "kjfk",
    "terminal": "5",
    "gate": "9",
    "scheduledTime": "16:30"
  },
  "arrival": {
    "iataCode": "las",
    "icaoCode": "klas",
    "terminal": "3",
    "gate": "d1",
    "scheduledTime": "19:13"
  },
  "aircraft": {
    "modelCode": "a321",
    "modelText": "airbus a321-231"
  },
  "airline": {
    "name": "",
    "iataCode": "at",
    "icaoCode": "at"
  },
  "flight": {
    "number": "9640",
    "iataNumber": "at9640",
    "icaoNumber": "at9640"
  },
  "codeshared": {
    "airline": {
      "name": "jetblue airways",
      "iataCode": "b6",
      "icaoCode": "jbu"
    },
    "flight": {
      "number": "1211",
      "iataNumber": "b61211",
      "icaoNumber": "jbu1211"
    }
  }
}
```

