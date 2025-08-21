# Airplanes

Using `airplanes` endpoint, you can get the information about Airplanes like Registration number, Production line, etc.

```python
airplanes_controller = client.airplanes
```

## Class Name

`AirplanesController`


# Get Airplanes

Retrieve airplane data

```python
def get_airplanes(self,
                 limit=100,
                 offset=0,
                 iata_type_code=None,
                 registration_number=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `iata_type_code` | `str` | Query, Optional | IATA type code |
| `registration_number` | `str` | Query, Optional | Aircraft registration number |

## Response Type

[`AirplaneResponse`](../../doc/models/airplane-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = airplanes_controller.get_airplanes(
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

