
# Arrival 2

## Structure

`Arrival2`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `airport` | `str` | Required | - |
| `timezone` | `str` | Required | - |
| `iata` | `str` | Required | - |
| `icao` | `str` | Required | - |
| `terminal` | `str` | Required | - |
| `gate` | `str` | Required | - |
| `baggage` | `str` | Required | - |
| `delay` | str \| None \| int | Required | This is a container for one-of cases. |
| `scheduled` | `str` | Required | - |
| `estimated` | `str` | Required | - |
| `actual` | `str` | Required | - |
| `estimated_runway` | `str` | Required | - |
| `actual_runway` | `str` | Required | - |

## Example (as JSON)

```json
{
  "airport": "airport8",
  "timezone": "timezone2",
  "iata": "iata4",
  "icao": "icao4",
  "terminal": "terminal0",
  "gate": "gate8",
  "baggage": "baggage6",
  "delay": "String5",
  "scheduled": "scheduled6",
  "estimated": "estimated8",
  "actual": "actual8",
  "estimated_runway": "estimated_runway8",
  "actual_runway": "actual_runway2"
}
```

