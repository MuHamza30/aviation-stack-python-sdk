
# Flight 2

## Structure

`Flight2`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `number` | `str` | Required | - |
| `iata` | `str` | Required | - |
| `icao` | `str` | Required | - |
| `codeshared` | [Codeshared](../../doc/models/codeshared.md) \| None \| [Codeshared1](../../doc/models/codeshared-1.md) | Required | This is a container for one-of cases. |

## Example (as JSON)

```json
{
  "number": "number8",
  "iata": "iata2",
  "icao": "icao2",
  "codeshared": {
    "airline_name": "swiss",
    "airline_iata": "lx",
    "airline_icao": "swr",
    "flight_number": "41",
    "flight_iata": "lx41",
    "flight_icao": "swr41"
  }
}
```

