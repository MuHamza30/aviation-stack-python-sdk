# Airlines

You can use the API's `airlines` endpoint to get data about airlines operating all over the world

```python
airlines_controller = client.airlines
```

## Class Name

`AirlinesController`


# Get Airlines

Retrieve airline data

```python
def get_airlines(self,
                limit=100,
                offset=0,
                iata_code=None,
                icao_code=None,
                country_code=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `iata_code` | `str` | Query, Optional | IATA code of the airline |
| `icao_code` | `str` | Query, Optional | ICAO code of the airline |
| `country_code` | `str` | Query, Optional | Country code |

## Response Type

[`AirlineResponse`](../../doc/models/airline-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = airlines_controller.get_airlines(
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

