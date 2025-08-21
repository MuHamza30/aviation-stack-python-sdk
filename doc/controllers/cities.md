# Cities

Using `cities` endpoint, you can look up at destination cities.

```python
cities_controller = client.cities
```

## Class Name

`CitiesController`


# Get Cities

Retrieve city data

```python
def get_cities(self,
              limit=100,
              offset=0,
              country_code=None,
              city_name=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `country_code` | `str` | Query, Optional | Country code |
| `city_name` | `str` | Query, Optional | City name |

## Response Type

[`CityResponse`](../../doc/models/city-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = cities_controller.get_cities(
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

