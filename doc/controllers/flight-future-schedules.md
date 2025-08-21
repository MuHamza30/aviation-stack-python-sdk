# Flight Future Schedules

```python
flight_future_schedules_controller = client.flight_future_schedules
```

## Class Name

`FlightFutureSchedulesController`


# Get Future Flight Schedules

Retrieve future flight schedule information for a specific airport and date

```python
def get_future_flight_schedules(self,
                               iata_code,
                               mtype,
                               date,
                               limit=100,
                               offset=0)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `iata_code` | `str` | Template, Required | [Required] The IATA code of the airport you'd like to request data from. Example: JFK,DXB. |
| `mtype` | [`TypeEnum`](../../doc/models/type-enum.md) | Template, Required | [Required] Airport schedule type. Available values: departure or arrival. |
| `date` | `date` | Template, Required | [Required] Filter your results by providing a flight date in the format YYYY-MM-DD. |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |

## Response Type

[`FlightScheduleResponse`](../../doc/models/flight-schedule-response.md)

## Example Usage

```python
iata_code = 'iata_code4'

mtype = TypeEnum.DEPARTURE

date = dateutil.parser.parse('2016-03-13').date()

limit = 100

offset = 0

result = flight_future_schedules_controller.get_future_flight_schedules(
    iata_code,
    mtype,
    date,
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

