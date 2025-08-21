# Flight Schedules

```python
flight_schedules_controller = client.flight_schedules
```

## Class Name

`FlightSchedulesController`


# Get Flight Schedules

Retrieve flight schedule information for a specific airport

```python
def get_flight_schedules(self,
                        iata_code,
                        mtype,
                        limit=100,
                        offset=0)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `iata_code` | `str` | Template, Required | [Required] The IATA code of the airport you'd like to request data from. Example: JFK,DXB. |
| `mtype` | [`TypeEnum`](../../doc/models/type-enum.md) | Template, Required | [Required] Airport schedule type. Available values: departure or arrival. |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |

## Response Type

[`FlightScheduleResponse`](../../doc/models/flight-schedule-response.md)

## Example Usage

```python
iata_code = 'iata_code4'

mtype = TypeEnum.DEPARTURE

limit = 100

offset = 0

result = flight_schedules_controller.get_flight_schedules(
    iata_code,
    mtype,
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

