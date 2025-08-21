# Countries

Using `countries` endpoint, you can look up at destination countries.

```python
countries_controller = client.countries
```

## Class Name

`CountriesController`


# Get Countries

Retrieve country data

```python
def get_countries(self,
                 limit=100,
                 offset=0,
                 country_code=None,
                 country_name=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `country_code` | `str` | Query, Optional | Country code |
| `country_name` | `str` | Query, Optional | Country name |

## Response Type

[`CountryResponse`](../../doc/models/country-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = countries_controller.get_countries(
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

