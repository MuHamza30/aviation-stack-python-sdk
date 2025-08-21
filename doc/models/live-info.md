
# Live Info

## Structure

`LiveInfo`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `updated` | `datetime` | Optional | Last update time |
| `latitude` | `float` | Optional | Current latitude |
| `longitude` | `float` | Optional | Current longitude |
| `altitude` | `float` | Optional | Current altitude |
| `direction` | `float` | Optional | Current direction |
| `speed_horizontal` | `float` | Optional | Horizontal speed |
| `speed_vertical` | `float` | Optional | Vertical speed |
| `is_ground` | `bool` | Optional | Whether aircraft is on ground |

## Example (as JSON)

```json
{
  "updated": "2016-03-13T12:52:32.123Z",
  "latitude": 51.58,
  "longitude": 49.38,
  "altitude": 168.94,
  "direction": 193.8
}
```

