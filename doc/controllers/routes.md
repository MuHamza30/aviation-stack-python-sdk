# Routes

The aviationstack API `routes` endpoint is capable of providing data about airline routes, updated every 24 hours.

```python
routes_controller = client.routes
```

## Class Name

`RoutesController`


# Get Routes

Retrieve airline route information

```python
def get_routes(self,
              limit=100,
              offset=0,
              airline_iata=None,
              airline_icao=None)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `limit` | `int` | Query, Optional | Number of results to return<br><br>**Default**: `100` |
| `offset` | `int` | Query, Optional | Number of results to skip<br><br>**Default**: `0` |
| `airline_iata` | `str` | Query, Optional | IATA code of the airline |
| `airline_icao` | `str` | Query, Optional | ICAO code of the airline |

## Response Type

[`RouteResponse`](../../doc/models/route-response.md)

## Example Usage

```python
limit = 100

offset = 0

result = routes_controller.get_routes(
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

