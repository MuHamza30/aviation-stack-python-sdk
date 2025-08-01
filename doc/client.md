
# Client Class Documentation

The following parameters are configurable for the API Client:

| Parameter | Type | Description |
|  --- | --- | --- |
| environment | `Environment` | The API environment. <br> **Default: `Environment.PRODUCTION`** |
| http_client_instance | `HttpClient` | The Http Client passed from the sdk user for making requests |
| override_http_client_configuration | `bool` | The value which determines to override properties of the passed Http Client from the sdk user |
| http_call_back | `HttpCallBack` | The callback value that is invoked before and after an HTTP call is made to an endpoint |
| timeout | `float` | The value to use for connection timeout. <br> **Default: 60** |
| max_retries | `int` | The number of times to retry an endpoint call if it fails. <br> **Default: 0** |
| backoff_factor | `float` | A backoff factor to apply between attempts after the second try. <br> **Default: 2** |
| retry_statuses | `Array of int` | The http statuses on which retry is to be done. <br> **Default: [408, 413, 429, 500, 502, 503, 504, 521, 522, 524]** |
| retry_methods | `Array of string` | The http methods on which retry is to be done. <br> **Default: ['GET', 'PUT']** |
| custom_query_authentication_credentials | [`CustomQueryAuthenticationCredentials`](auth/custom-query-parameter.md) | The credential object for Custom Query Parameter |

The API client can be initialized as follows:

```python
from aviationstack.aviationstack_client import AviationstackClient
from aviationstack.configuration import Environment
from aviationstack.http.auth.custom_query_authentication import CustomQueryAuthenticationCredentials

client = AviationstackClient(
    custom_query_authentication_credentials=CustomQueryAuthenticationCredentials(
        access_key='access_key'
    ),
    environment=Environment.PRODUCTION
)
```

## Aviationstack Client

The gateway for the SDK. This class acts as a factory for the Controllers and also holds the configuration of the SDK.

## Controllers

| Name | Description |
|  --- | --- |
| flights | Gets FlightsController |
| routes | Gets RoutesController |
| airports | Gets AirportsController |
| airlines | Gets AirlinesController |
| airplanes | Gets AirplanesController |
| aircraft_types | Gets AircraftTypesController |
| taxes | Gets TaxesController |
| cities | Gets CitiesController |
| countries | Gets CountriesController |
| flight_schedules | Gets FlightSchedulesController |
| flight_future_schedules | Gets FlightFutureSchedulesController |

