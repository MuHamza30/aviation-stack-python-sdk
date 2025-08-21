
# Pagination

## Structure

`Pagination`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Required | Number of results per page |
| `offset` | `int` | Required | Number of results skipped |
| `count` | `int` | Required | Total number of results |
| `total` | `int` | Required | Total number of available results |

## Example (as JSON)

```json
{
  "limit": 66,
  "offset": 162,
  "count": 210,
  "total": 160
}
```

