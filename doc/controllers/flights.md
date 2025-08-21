# Flights

In order to look up real-time or historical information about one or multiple flights, you can use the Aviationstack's `flights` endpoint.

```python
flights_controller = client.flights
```

## Class Name

`FlightsController`


# Get Flights

Retrieve real-time and historical flight data

```python
def get_flights(self,
               limit=100,
               offset=0,
               flight_iata=None,
               flight_icao=None,
               airline_iata=None,
               airline_icao=None,
               flight_number=None,
               dep_iata=None,
               dep_icao=None,
               arr_iata=None,
               arr_icao=None,
               flight_status=None,
               date=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return (max 1000)<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `flight_iata` | `str` | Query, Optional | IATA code of the flight |
| `flight_icao` | `str` | Query, Optional | ICAO code of the flight |
| `airline_iata` | `str` | Query, Optional | IATA code of the airline |
| `airline_icao` | `str` | Query, Optional | ICAO code of the airline |
| `flight_number` | `str` | Query, Optional | Flight number |
| `dep_iata` | `str` | Query, Optional | IATA code of departure airport |
| `dep_icao` | `str` | Query, Optional | ICAO code of departure airport |
| `arr_iata` | `str` | Query, Optional | IATA code of arrival airport |
| `arr_icao` | `str` | Query, Optional | ICAO code of arrival airport |
| `flight_status` | [`FlightStatus2Enum`](../../doc/models/flight-status-2-enum.md) | Query, Optional | Status of the flight |
| `date` | `date` | Query, Optional | Date in YYYY-MM-DD format |

## Response Type

[`FlightResponse`](../../doc/models/flight-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = flights_controller.get_flights(
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
| 429 | Rate limit exceeded | [`ErrorResponseException`](../../doc/models/error-response-exception.md) |

