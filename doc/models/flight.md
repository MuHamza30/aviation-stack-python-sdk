
# Flight

## Structure

`Flight`

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
    "airline_name": "t'way air",
    "airline_iata": "tw",
    "airline_icao": "twb",
    "flight_number": "176",
    "flight_iata": "tw176",
    "flight_icao": "twb176"
  }
}
```

