
# Departure 2

## Structure

`Departure2`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `airport` | `str` | Required | - |
| `timezone` | `str` | Required | - |
| `iata` | `str` | Required | - |
| `icao` | `str` | Required | - |
| `terminal` | `str` | Required | - |
| `gate` | `str` | Required | - |
| `delay` | str \| None \| int | Required | This is a container for one-of cases. |
| `scheduled` | `str` | Required | - |
| `estimated` | `str` | Required | - |
| `actual` | `str` | Required | - |
| `estimated_runway` | `str` | Required | - |
| `actual_runway` | `str` | Required | - |

## Example (as JSON)

```json
{
  "airport": "airport2",
  "timezone": "timezone4",
  "iata": "iata0",
  "icao": "icao0",
  "terminal": "terminal4",
  "gate": "gate8",
  "delay": "String9",
  "scheduled": "scheduled2",
  "estimated": "estimated2",
  "actual": "actual2",
  "estimated_runway": "estimated_runway2",
  "actual_runway": "actual_runway8"
}
```

