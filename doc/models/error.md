
# Error

## Structure

`Error`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `code` | `str` | Optional | Error code |
| `message` | `str` | Optional | Error message |
| `details` | `Any` | Optional | Additional error details |

## Example (as JSON)

```json
{
  "code": "code2",
  "message": "message4",
  "details": {
    "key1": "val1",
    "key2": "val2"
  }
}
```

