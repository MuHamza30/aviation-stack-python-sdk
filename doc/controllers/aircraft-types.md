# Aircraft Types

```python
aircraft_types_controller = client.aircraft_types
```

## Class Name

`AircraftTypesController`


# Aircraft Types

```python
def aircraft_types(self)
```

## Response Type

[`M200OKAircraftTypes`](../../doc/models/m200-ok-aircraft-types.md)

## Example Usage

```python
result = aircraft_types_controller.aircraft_types()
print(result)
```

## Example Response *(as JSON)*

```json
{
  "pagination": {
    "offset": 0,
    "limit": 100,
    "count": 100,
    "total": 313
  },
  "data": [
    {
      "id": "16907",
      "iata_code": "100",
      "aircraft_name": "Fokker 100",
      "plane_type_id": "1"
    },
    {
      "id": "16908",
      "iata_code": "141",
      "aircraft_name": "British Aerospace BAe 146-100",
      "plane_type_id": "2"
    },
    {
      "id": "16909",
      "iata_code": "142",
      "aircraft_name": "British Aerospace BAe 146-200",
      "plane_type_id": "3"
    },
    {
      "id": "16910",
      "iata_code": "143",
      "aircraft_name": "British Aerospace BAe 146-300",
      "plane_type_id": "4"
    },
    {
      "id": "16911",
      "iata_code": "146",
      "aircraft_name": "British Aerospace BAe 146",
      "plane_type_id": "5"
    },
    {
      "id": "16912",
      "iata_code": "14F",
      "aircraft_name": "British Aerospace BAe 146 Freighter",
      "plane_type_id": "6"
    },
    {
      "id": "16913",
      "iata_code": "14X",
      "aircraft_name": "British Aerospace BAe 146-100QT/QC",
      "plane_type_id": "7"
    },
    {
      "id": "16914",
      "iata_code": "14Y",
      "aircraft_name": "British Aerospace BAe 146-200QT/QC",
      "plane_type_id": "8"
    },
    {
      "id": "16915",
      "iata_code": "14Z",
      "aircraft_name": "British Aerospace BAe 146-300QT/QC",
      "plane_type_id": "9"
    },
    {
      "id": "16916",
      "iata_code": "310",
      "aircraft_name": "Airbus Industrie A310",
      "plane_type_id": "10"
    },
    {
      "id": "16917",
      "iata_code": "312",
      "aircraft_name": "Airbus Industrie A310-200",
      "plane_type_id": "11"
    },
    {
      "id": "16918",
      "iata_code": "313",
      "aircraft_name": "Airbus Industrie A310-300",
      "plane_type_id": "12"
    },
    {
      "id": "16919",
      "iata_code": "318",
      "aircraft_name": "Airbus Industrie A318",
      "plane_type_id": "13"
    },
    {
      "id": "16920",
      "iata_code": "319",
      "aircraft_name": "Airbus Industrie A319",
      "plane_type_id": "14"
    },
    {
      "id": "16921",
      "iata_code": "31F",
      "aircraft_name": "Airbus Industrie A310 Freighter",
      "plane_type_id": "15"
    },
    {
      "id": "16922",
      "iata_code": "31X",
      "aircraft_name": "Airbus Industrie A310-200 Freighter",
      "plane_type_id": "16"
    },
    {
      "id": "16923",
      "iata_code": "31Y",
      "aircraft_name": "Airbus Industrie A310-300 Freighter",
      "plane_type_id": "17"
    },
    {
      "id": "16924",
      "iata_code": "320",
      "aircraft_name": "Airbus Industrie A320",
      "plane_type_id": "18"
    },
    {
      "id": "16925",
      "iata_code": "321",
      "aircraft_name": "Airbus Industrie A321",
      "plane_type_id": "19"
    },
    {
      "id": "16926",
      "iata_code": "32S",
      "aircraft_name": "Airbus Industrie A318/319/320/321",
      "plane_type_id": "20"
    },
    {
      "id": "16927",
      "iata_code": "330",
      "aircraft_name": "Airbus Industrie A330",
      "plane_type_id": "21"
    },
    {
      "id": "16928",
      "iata_code": "332",
      "aircraft_name": "Airbus Industrie A330-200",
      "plane_type_id": "22"
    },
    {
      "id": "16929",
      "iata_code": "333",
      "aircraft_name": "Airbus Industrie A330-300",
      "plane_type_id": "23"
    },
    {
      "id": "16930",
      "iata_code": "340",
      "aircraft_name": "Airbus Industrie A340",
      "plane_type_id": "24"
    },
    {
      "id": "16931",
      "iata_code": "342",
      "aircraft_name": "Airbus Industrie A340-200",
      "plane_type_id": "25"
    },
    {
      "id": "16932",
      "iata_code": "343",
      "aircraft_name": "Airbus Industrie A340-300",
      "plane_type_id": "26"
    },
    {
      "id": "16933",
      "iata_code": "345",
      "aircraft_name": "Airbus Industrie A340-500",
      "plane_type_id": "27"
    },
    {
      "id": "16934",
      "iata_code": "346",
      "aircraft_name": "Airbus Industrie A340-600",
      "plane_type_id": "28"
    },
    {
      "id": "16935",
      "iata_code": "380",
      "aircraft_name": "Airbus Industrie A380",
      "plane_type_id": "29"
    },
    {
      "id": "16936",
      "iata_code": "388",
      "aircraft_name": "Airbus Industrie A380-800",
      "plane_type_id": "30"
    },
    {
      "id": "16937",
      "iata_code": "38F",
      "aircraft_name": "Airbus Industrie A380 Freighter",
      "plane_type_id": "31"
    },
    {
      "id": "16938",
      "iata_code": "703",
      "aircraft_name": "Boeing 707-300",
      "plane_type_id": "32"
    },
    {
      "id": "16939",
      "iata_code": "707",
      "aircraft_name": "Boeing 707/720",
      "plane_type_id": "33"
    },
    {
      "id": "16940",
      "iata_code": "70F",
      "aircraft_name": "Boeing 707-300 Freighter",
      "plane_type_id": "34"
    },
    {
      "id": "16941",
      "iata_code": "70M",
      "aircraft_name": "Boeing 707-300 Combi",
      "plane_type_id": "35"
    },
    {
      "id": "16942",
      "iata_code": "717",
      "aircraft_name": "Boeing 717-200",
      "plane_type_id": "36"
    },
    {
      "id": "16943",
      "iata_code": "721",
      "aircraft_name": "Boeing 727-100",
      "plane_type_id": "37"
    },
    {
      "id": "16944",
      "iata_code": "722",
      "aircraft_name": "Boeing 727-200",
      "plane_type_id": "38"
    },
    {
      "id": "16945",
      "iata_code": "727",
      "aircraft_name": "Boeing 727",
      "plane_type_id": "39"
    },
    {
      "id": "16946",
      "iata_code": "72A",
      "aircraft_name": "Boeing 727-200 Advanced",
      "plane_type_id": "40"
    },
    {
      "id": "16947",
      "iata_code": "72B",
      "aircraft_name": "Boeing 727-100 Combi",
      "plane_type_id": "41"
    },
    {
      "id": "16948",
      "iata_code": "72C",
      "aircraft_name": "Boeing 727-200 Combi",
      "plane_type_id": "42"
    },
    {
      "id": "16949",
      "iata_code": "72F",
      "aircraft_name": "Boeing 727 Freighter",
      "plane_type_id": "43"
    },
    {
      "id": "16950",
      "iata_code": "72M",
      "aircraft_name": "Boeing 727 Combi",
      "plane_type_id": "44"
    },
    {
      "id": "16951",
      "iata_code": "72S",
      "aircraft_name": "Boeing 727-200",
      "plane_type_id": "45"
    },
    {
      "id": "16952",
      "iata_code": "72X",
      "aircraft_name": "Boeing 727-100 Freighter",
      "plane_type_id": "46"
    },
    {
      "id": "16953",
      "iata_code": "72Y",
      "aircraft_name": "Boeing 727-200 Freighter",
      "plane_type_id": "47"
    },
    {
      "id": "16954",
      "iata_code": "731",
      "aircraft_name": "Boeing 737-100",
      "plane_type_id": "48"
    },
    {
      "id": "16955",
      "iata_code": "732",
      "aircraft_name": "Boeing 737-200",
      "plane_type_id": "49"
    },
    {
      "id": "16956",
      "iata_code": "733",
      "aircraft_name": "Boeing 737-300",
      "plane_type_id": "50"
    },
    {
      "id": "16957",
      "iata_code": "734",
      "aircraft_name": "Boeing 737-400",
      "plane_type_id": "51"
    },
    {
      "id": "16958",
      "iata_code": "735",
      "aircraft_name": "Boeing 737-500",
      "plane_type_id": "52"
    },
    {
      "id": "16959",
      "iata_code": "736",
      "aircraft_name": "Boeing 737-600",
      "plane_type_id": "53"
    },
    {
      "id": "16960",
      "iata_code": "737",
      "aircraft_name": "Boeing 737",
      "plane_type_id": "54"
    },
    {
      "id": "16961",
      "iata_code": "738",
      "aircraft_name": "Boeing 737-800",
      "plane_type_id": "55"
    },
    {
      "id": "16962",
      "iata_code": "739",
      "aircraft_name": "Boeing 737-900",
      "plane_type_id": "56"
    },
    {
      "id": "16963",
      "iata_code": "73A",
      "aircraft_name": "Boeing 737-200/200C Advanced",
      "plane_type_id": "57"
    },
    {
      "id": "16964",
      "iata_code": "73C",
      "aircraft_name": "Boeing 737-300",
      "plane_type_id": "58"
    },
    {
      "id": "16965",
      "iata_code": "73E",
      "aircraft_name": "Boeing 737-900ER",
      "plane_type_id": "59"
    },
    {
      "id": "16966",
      "iata_code": "73F",
      "aircraft_name": "Boeing 737 Freighter",
      "plane_type_id": "60"
    },
    {
      "id": "16967",
      "iata_code": "73G",
      "aircraft_name": "Boeing 737-700",
      "plane_type_id": "61"
    },
    {
      "id": "16968",
      "iata_code": "73H",
      "aircraft_name": "Boeing 737-800 With Winglets",
      "plane_type_id": "62"
    },
    {
      "id": "16969",
      "iata_code": "73J",
      "aircraft_name": "Boeing 737-900 With Winglets",
      "plane_type_id": "63"
    },
    {
      "id": "16970",
      "iata_code": "73M",
      "aircraft_name": "Boeing 737-200 Combi",
      "plane_type_id": "64"
    },
    {
      "id": "16971",
      "iata_code": "73N",
      "aircraft_name": "Boeing 737-300 Mixed Config",
      "plane_type_id": "65"
    },
    {
      "id": "16972",
      "iata_code": "73P",
      "aircraft_name": "Boeing 737-400 Freighter",
      "plane_type_id": "66"
    },
    {
      "id": "16973",
      "iata_code": "73Q",
      "aircraft_name": "Boeing 737-400 Mixed Config",
      "plane_type_id": "67"
    },
    {
      "id": "16974",
      "iata_code": "73S",
      "aircraft_name": "Boeing 737 Advanced",
      "plane_type_id": "68"
    },
    {
      "id": "16975",
      "iata_code": "73W",
      "aircraft_name": "Boeing 737-700 With Winglets",
      "plane_type_id": "69"
    },
    {
      "id": "16976",
      "iata_code": "73X",
      "aircraft_name": "Boeing 737-200 Freighter",
      "plane_type_id": "70"
    },
    {
      "id": "16977",
      "iata_code": "73Y",
      "aircraft_name": "Boeing 737-300 Freighter",
      "plane_type_id": "71"
    },
    {
      "id": "16978",
      "iata_code": "741",
      "aircraft_name": "Boeing 747-100",
      "plane_type_id": "72"
    },
    {
      "id": "16979",
      "iata_code": "742",
      "aircraft_name": "Boeing 747-200",
      "plane_type_id": "73"
    },
    {
      "id": "16980",
      "iata_code": "743",
      "aircraft_name": "Boeing 747-300 (including -100SUD and -200SUD)",
      "plane_type_id": "74"
    },
    {
      "id": "16981",
      "iata_code": "744",
      "aircraft_name": "Boeing 747-400",
      "plane_type_id": "75"
    },
    {
      "id": "16982",
      "iata_code": "747",
      "aircraft_name": "Boeing 747",
      "plane_type_id": "76"
    },
    {
      "id": "16983",
      "iata_code": "74C",
      "aircraft_name": "Boeing 747-200 Combi",
      "plane_type_id": "77"
    },
    {
      "id": "16984",
      "iata_code": "74D",
      "aircraft_name": "Boeing 747-300 Combi (including -200SUD)",
      "plane_type_id": "78"
    },
    {
      "id": "16985",
      "iata_code": "74E",
      "aircraft_name": "Boeing 747-400 Combi",
      "plane_type_id": "79"
    },
    {
      "id": "16986",
      "iata_code": "74F",
      "aircraft_name": "Boeing 747 Freighter",
      "plane_type_id": "80"
    },
    {
      "id": "16987",
      "iata_code": "74J",
      "aircraft_name": "Boeing 747-400 Domestic",
      "plane_type_id": "81"
    },
    {
      "id": "16988",
      "iata_code": "74L",
      "aircraft_name": "Boeing 747SP",
      "plane_type_id": "82"
    },
    {
      "id": "16989",
      "iata_code": "74M",
      "aircraft_name": "Boeing 747 Combi",
      "plane_type_id": "83"
    },
    {
      "id": "16990",
      "iata_code": "74T",
      "aircraft_name": "Boeing 747-100 Freighter",
      "plane_type_id": "84"
    },
    {
      "id": "16991",
      "iata_code": "74U",
      "aircraft_name": "Boeing 747-300 Freighter",
      "plane_type_id": "85"
    },
    {
      "id": "16992",
      "iata_code": "74V",
      "aircraft_name": "Boeing 747SR Freighter",
      "plane_type_id": "86"
    },
    {
      "id": "16993",
      "iata_code": "74X",
      "aircraft_name": "Boeing 747-200 Freighter",
      "plane_type_id": "87"
    },
    {
      "id": "16994",
      "iata_code": "74Y",
      "aircraft_name": "Boeing 747-400 Freighter",
      "plane_type_id": "88"
    },
    {
      "id": "16995",
      "iata_code": "752",
      "aircraft_name": "Boeing 757-200",
      "plane_type_id": "89"
    },
    {
      "id": "16996",
      "iata_code": "753",
      "aircraft_name": "Boeing 757-300",
      "plane_type_id": "90"
    },
    {
      "id": "16997",
      "iata_code": "757",
      "aircraft_name": "Boeing 757",
      "plane_type_id": "91"
    },
    {
      "id": "16998",
      "iata_code": "75F",
      "aircraft_name": "Boeing 757-200 Freighter",
      "plane_type_id": "92"
    },
    {
      "id": "16999",
      "iata_code": "75M",
      "aircraft_name": "Boeing 757-200 Combi",
      "plane_type_id": "93"
    },
    {
      "id": "17000",
      "iata_code": "75W",
      "aircraft_name": "Boeing 757-200 With Winglets",
      "plane_type_id": "94"
    },
    {
      "id": "17001",
      "iata_code": "762",
      "aircraft_name": "Boeing 767-200",
      "plane_type_id": "95"
    },
    {
      "id": "17002",
      "iata_code": "763",
      "aircraft_name": "Boeing 767-300",
      "plane_type_id": "96"
    },
    {
      "id": "17003",
      "iata_code": "764",
      "aircraft_name": "Boeing 767-400",
      "plane_type_id": "97"
    },
    {
      "id": "17004",
      "iata_code": "767",
      "aircraft_name": "Boeing 767",
      "plane_type_id": "98"
    },
    {
      "id": "17005",
      "iata_code": "76F",
      "aircraft_name": "Boeing 767 Freighter",
      "plane_type_id": "99"
    },
    {
      "id": "17006",
      "iata_code": "76X",
      "aircraft_name": "Boeing 767-200 Freighter",
      "plane_type_id": "100"
    }
  ]
}
```

