
# Arrival

## Structure

`Arrival`

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
| `delay` | `str` | Required | - |
| `scheduled` | `str` | Required | - |
| `estimated` | `str` | Required | - |
| `actual` | `str` | Required | - |
| `estimated_runway` | `str` | Required | - |
| `actual_runway` | `str` | Required | - |

## Example (as JSON)

```json
{
  "airport": "Shanghai Pudong International",
  "timezone": "Asia/Shanghai",
  "iata": "PVG",
  "icao": "ZSPD",
  "terminal": "2",
  "gate": "gate0",
  "baggage": "baggage6",
  "delay": "delay6",
  "scheduled": "2024-08-17T05:00:00+00:00",
  "estimated": "2024-08-17T05:00:00+00:00",
  "actual": "actual0",
  "estimated_runway": "estimated_runway0",
  "actual_runway": "actual_runway0"
}
```

