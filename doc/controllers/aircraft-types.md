# Aircraft Types

```python
aircraft_types_controller = client.aircraft_types
```

## Class Name

`AircraftTypesController`


# Get Aircraft Types

Retrieve aircraft type data

```python
def get_aircraft_types(self,
                      limit=100,
                      offset=0,
                      iata_code=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `iata_code` | `str` | Query, Optional | IATA code of the aircraft type |

## Response Type

[`AircraftTypeResponse`](../../doc/models/aircraft-type-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = aircraft_types_controller.get_aircraft_types(
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

