# Taxes

Using `taxes` endpoint, you can get the data about different aviation taxes.

```python
taxes_controller = client.taxes
```

## Class Name

`TaxesController`


# Get Taxes

Retrieve aviation tax data

```python
def get_taxes(self,
             limit=100,
             offset=0,
             iata_code=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `iata_code` | `str` | Query, Optional | IATA code |

## Response Type

[`TaxResponse`](../../doc/models/tax-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = taxes_controller.get_taxes(
    limit=limit,
    offset=offset
)
print(result)
```

## Errors

| HTTP Status Code | Error Description | Exception Class |
|  --- | --- | --- |
| 400 | Bad request | [`ErrorResponseException`](../../doc/models/error-response-exception.md) |
| 401 | Unauthorized | [`ErrorResponseException`](../../doc/models/error-response-exception.md) |

