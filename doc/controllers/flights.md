# Flights

In order to look up real-time or historical information about one or multiple flights, you can use the Aviationstack's `flights` endpoint.

```python
flights_controller = client.flights
```

## Class Name

`FlightsController`

## Methods

* [Real Time](../../doc/controllers/flights.md#real-time)
* [Historical](../../doc/controllers/flights.md#historical)


# Real Time

The Flight endpoint is capable of tracking flights and retrieving flight status information in real-time.

```python
def real_time(self)
```

## Response Type

[`M200OKReamTime`](../../doc/models/m200-ok-ream-time.md)

## Example Usage

```python
result = flights_controller.real_time()
print(result)
```


# Historical

```python
def historical(self,
              flight_date)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `flight_date` | `str` | Query, Required | - |

## Response Type

[`M200OKHistorical`](../../doc/models/m200-ok-historical.md)

## Example Usage

```python
flight_date = '2023-12-11'

result = flights_controller.historical(flight_date)
print(result)
```

