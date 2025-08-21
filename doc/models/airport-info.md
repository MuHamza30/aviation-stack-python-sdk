
# Airport Info

## Structure

`AirportInfo`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `airport` | `str` | Optional | Airport name |
| `timezone` | `str` | Optional | Timezone |
| `iata` | `str` | Optional | IATA code |
| `icao` | `str` | Optional | ICAO code |
| `terminal` | `str` | Optional | Terminal |
| `gate` | `str` | Optional | Gate |
| `delay` | `int` | Optional | Delay in minutes |
| `scheduled` | `datetime` | Optional | Scheduled time |
| `estimated` | `datetime` | Optional | Estimated time |
| `actual` | `datetime` | Optional | Actual time |
| `estimated_runway` | `datetime` | Optional | Estimated runway time |
| `actual_runway` | `datetime` | Optional | Actual runway time |

## Example (as JSON)

```json
{
  "airport": "airport2",
  "timezone": "timezone6",
  "iata": "iata0",
  "icao": "icao0",
  "terminal": "terminal4"
}
```

