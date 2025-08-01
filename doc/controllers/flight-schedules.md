# Flight Schedules

```python
flight_schedules_controller = client.flight_schedules
```

## Class Name

`FlightSchedulesController`


# Flight Schedules

```python
def flight_schedules(self,
                    iata_code,
                    mtype)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `iata_code` | `str` | Query, Required | [Required] The IATA code of the airport you'd like to request data from. Example: JFK,DXB. |
| `mtype` | `str` | Query, Required | [Required] Airport schedule type. Available values: departure or arrival. |

## Response Type

[`M200OKFlightSchedules`](../../doc/models/m200-ok-flight-schedules.md)

## Example Usage

```python
iata_code = 'JFK'

mtype = 'departure'

result = flight_schedules_controller.flight_schedules(
    iata_code,
    mtype
)
print(result)
```

