# Airports

To get data about Airports across the globe, you can use the API's `airports` endpoint.

```python
airports_controller = client.airports
```

## Class Name

`AirportsController`


# Get Airports

Retrieve airport data

```python
def get_airports(self,
                limit=100,
                offset=0,
                iata_code=None,
                icao_code=None,
                country_code=None,
                city_name=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `iata_code` | `str` | Query, Optional | IATA code of the airport |
| `icao_code` | `str` | Query, Optional | ICAO code of the airport |
| `country_code` | `str` | Query, Optional | Country code |
| `city_name` | `str` | Query, Optional | City name |

## Response Type

[`AirportResponse`](../../doc/models/airport-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = airports_controller.get_airports(
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

