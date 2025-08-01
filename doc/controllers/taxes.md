# Taxes

Using `taxes` endpoint, you can get the data about different aviation taxes.

```python
taxes_controller = client.taxes
```

## Class Name

`TaxesController`


# Taxes

```python
def taxes(self)
```

## Response Type

[`M200OKTaxes`](../../doc/models/m200-ok-taxes.md)

## Example Usage

```python
result = taxes_controller.taxes()
print(result)
```

## Example Response *(as JSON)*

```json
{
  "pagination": {
    "offset": 0,
    "limit": 100,
    "count": 100,
    "total": 521
  },
  "data": [
    {
      "id": "28135",
      "tax_id": "1",
      "tax_name": "Government Tax",
      "iata_code": "AB"
    },
    {
      "id": "28136",
      "tax_id": "2",
      "tax_name": "Value Added Tax",
      "iata_code": "AC"
    },
    {
      "id": "28137",
      "tax_id": "3",
      "tax_name": "Passenger Service Charge (International)",
      "iata_code": "AE"
    },
    {
      "id": "28138",
      "tax_id": "4",
      "tax_name": "Airport Departure Fee (Domestic/International)",
      "iata_code": "AF"
    },
    {
      "id": "28139",
      "tax_id": "5",
      "tax_name": "Ticket Tax",
      "iata_code": "AG"
    },
    {
      "id": "28140",
      "tax_id": "6",
      "tax_name": "Airport Tax",
      "iata_code": "AH"
    },
    {
      "id": "28141",
      "tax_id": "7",
      "tax_name": "Baggage Security Screening Fee",
      "iata_code": "AI"
    },
    {
      "id": "28142",
      "tax_id": "8",
      "tax_name": "Airport Exit Tax (International)",
      "iata_code": "AJ"
    },
    {
      "id": "28143",
      "tax_id": "9",
      "tax_name": "Airport Departure Tax (International)",
      "iata_code": "AK"
    },
    {
      "id": "28144",
      "tax_id": "10",
      "tax_name": "Passenger Service Charge (Domestic/International)",
      "iata_code": "AL"
    },
    {
      "id": "28145",
      "tax_id": "11",
      "tax_name": "Tax",
      "iata_code": "AM"
    },
    {
      "id": "28146",
      "tax_id": "12",
      "tax_name": "Airport Facility Charge (Domestic/International)",
      "iata_code": "AN"
    },
    {
      "id": "28147",
      "tax_id": "13",
      "tax_name": "Embarkation Tax (International)",
      "iata_code": "AO"
    },
    {
      "id": "28148",
      "tax_id": "14",
      "tax_name": "Security Charge (Domestic/International)",
      "iata_code": "AP"
    },
    {
      "id": "28149",
      "tax_id": "15",
      "tax_name": "Ticket Tax",
      "iata_code": "AR"
    },
    {
      "id": "28150",
      "tax_id": "16",
      "tax_name": "Passenger Security Charge(Domestic/International)",
      "iata_code": "AT"
    },
    {
      "id": "28151",
      "tax_id": "17",
      "tax_name": "Passenger Movement Charge",
      "iata_code": "AU"
    },
    {
      "id": "28152",
      "tax_id": "18",
      "tax_name": "Tourism Development Tax (International)",
      "iata_code": "AV"
    },
    {
      "id": "28153",
      "tax_id": "19",
      "tax_name": "Passenger Facility and Security Charge",
      "iata_code": "AW"
    },
    {
      "id": "28154",
      "tax_id": "20",
      "tax_name": "Passenger Service Charge (Domestic)",
      "iata_code": "AX"
    },
    {
      "id": "28155",
      "tax_id": "21",
      "tax_name": "Passenger Civil Aviation Security Service Fee (Domestic/International)",
      "iata_code": "AY"
    },
    {
      "id": "28156",
      "tax_id": "22",
      "tax_name": "Departure Tax (International)",
      "iata_code": "AZ"
    },
    {
      "id": "28157",
      "tax_id": "23",
      "tax_name": "Passenger Service Charge (Domestic/International)",
      "iata_code": "BA"
    },
    {
      "id": "28158",
      "tax_id": "24",
      "tax_name": "Value Added Tax",
      "iata_code": "BB"
    },
    {
      "id": "28159",
      "tax_id": "25",
      "tax_name": "Airport Security Charge -(Domestic/International)",
      "iata_code": "BC"
    },
    {
      "id": "28160",
      "tax_id": "26",
      "tax_name": "Embarkation Fee (Domestic/International)",
      "iata_code": "BD"
    },
    {
      "id": "28161",
      "tax_id": "27",
      "tax_name": "Passenger Service and Security Charge",
      "iata_code": "BE"
    },
    {
      "id": "28162",
      "tax_id": "28",
      "tax_name": "Fiscal Stamp / Security / Sales / Tourism Tax (Domestic/International)",
      "iata_code": "BF"
    },
    {
      "id": "28163",
      "tax_id": "29",
      "tax_name": "Passenger Charge (Domestic/International)",
      "iata_code": "BG"
    },
    {
      "id": "28164",
      "tax_id": "30",
      "tax_name": "Government Tax",
      "iata_code": "BH"
    },
    {
      "id": "28165",
      "tax_id": "31",
      "tax_name": "Airport Departure Fee (Domestic/International)",
      "iata_code": "BK"
    },
    {
      "id": "28166",
      "tax_id": "32",
      "tax_name": "Aviation Security Fee",
      "iata_code": "BL"
    },
    {
      "id": "28167",
      "tax_id": "33",
      "tax_name": "Government Passenger Tax",
      "iata_code": "BM"
    },
    {
      "id": "28168",
      "tax_id": "34",
      "tax_name": "Passenger Services Charge (International)",
      "iata_code": "BN"
    },
    {
      "id": "28169",
      "tax_id": "35",
      "tax_name": "Sales Tax (Domestic/International)",
      "iata_code": "BO"
    },
    {
      "id": "28170",
      "tax_id": "36",
      "tax_name": "PSC, Departure Tax and Contribution to International Poverty Eradication ",
      "iata_code": "BP"
    },
    {
      "id": "28171",
      "tax_id": "37",
      "tax_name": "Airport Fee",
      "iata_code": "BQ"
    },
    {
      "id": "28172",
      "tax_id": "38",
      "tax_name": "Embarkation Tax (Domestic/International)",
      "iata_code": "BR"
    },
    {
      "id": "28173",
      "tax_id": "39",
      "tax_name": "Ticket Tax (International)",
      "iata_code": "BS"
    },
    {
      "id": "28174",
      "tax_id": "40",
      "tax_name": "Airport Development Fee",
      "iata_code": "BU"
    },
    {
      "id": "28175",
      "tax_id": "41",
      "tax_name": "Departure Tax (Domestic/International)",
      "iata_code": "BW"
    },
    {
      "id": "28176",
      "tax_id": "42",
      "tax_name": "Security Tax (Domestic/International)",
      "iata_code": "BX"
    },
    {
      "id": "28177",
      "tax_id": "43",
      "tax_name": "Sales Tax (International)",
      "iata_code": "BY"
    },
    {
      "id": "28178",
      "tax_id": "44",
      "tax_name": "Ticket Tax",
      "iata_code": "BZ"
    },
    {
      "id": "28179",
      "tax_id": "45",
      "tax_name": "Air Travellers Security Charge (Domestic/International)",
      "iata_code": "CA"
    },
    {
      "id": "28180",
      "tax_id": "46",
      "tax_name": "Passenger Service Charge (Domestic/International)",
      "iata_code": "CB"
    },
    {
      "id": "28181",
      "tax_id": "47",
      "tax_name": "Cocos Island Passenger Service Charge",
      "iata_code": "CC"
    },
    {
      "id": "28182",
      "tax_id": "48",
      "tax_name": "Embarkation / Sales / Tourism Tax (Domestic/International)",
      "iata_code": "CD"
    },
    {
      "id": "28183",
      "tax_id": "49",
      "tax_name": "Aviation Security Screening Levy (Domestic)",
      "iata_code": "CE"
    },
    {
      "id": "28184",
      "tax_id": "50",
      "tax_name": "Security Tax",
      "iata_code": "CF"
    },
    {
      "id": "28185",
      "tax_id": "51",
      "tax_name": "Sales / Security Tax (Domestic/International)",
      "iata_code": "CG"
    },
    {
      "id": "28186",
      "tax_id": "52",
      "tax_name": "Airport Passenger Security and Noise Charge (Domestic/International)",
      "iata_code": "CH"
    },
    {
      "id": "28187",
      "tax_id": "53",
      "tax_name": "Security / Tourism Tax (Domestic/International)",
      "iata_code": "CI"
    },
    {
      "id": "28188",
      "tax_id": "54",
      "tax_name": "Security Service Charge (Domestic/International)",
      "iata_code": "CJ"
    },
    {
      "id": "28189",
      "tax_id": "55",
      "tax_name": "Airport Facility Charge (Domestic)",
      "iata_code": "CL"
    },
    {
      "id": "28190",
      "tax_id": "56",
      "tax_name": "Tax on Value (Domestic/International)",
      "iata_code": "CM"
    },
    {
      "id": "28191",
      "tax_id": "57",
      "tax_name": "Airport Fee (Domestic/International)",
      "iata_code": "CN"
    },
    {
      "id": "28192",
      "tax_id": "58",
      "tax_name": "Airport Tax (Domestic/International)",
      "iata_code": "CO"
    },
    {
      "id": "28193",
      "tax_id": "59",
      "tax_name": "Rehabilitation fund and care of handicapped person",
      "iata_code": "CQ"
    },
    {
      "id": "28194",
      "tax_id": "60",
      "tax_name": "Transportation Tax",
      "iata_code": "CR"
    },
    {
      "id": "28195",
      "tax_id": "61",
      "tax_name": "Security Tax (Domestic/International)",
      "iata_code": "CT"
    },
    {
      "id": "28196",
      "tax_id": "62",
      "tax_name": "Airport Embarkation Tax (Domestic/International)",
      "iata_code": "CV"
    },
    {
      "id": "28197",
      "tax_id": "63",
      "tax_name": "Value Added Tax (Domestic)",
      "iata_code": "CW"
    },
    {
      "id": "28198",
      "tax_id": "64",
      "tax_name": "Christmas Island Passenger Service Charge (Domestic/International)",
      "iata_code": "CX"
    },
    {
      "id": "28199",
      "tax_id": "65",
      "tax_name": "Airport Service Charge (International)",
      "iata_code": "CY"
    },
    {
      "id": "28200",
      "tax_id": "66",
      "tax_name": "Embarkation Tax (Domestic/International)",
      "iata_code": "CZ"
    },
    {
      "id": "28201",
      "tax_id": "67",
      "tax_name": "Passenger Service Charge (Domestic)",
      "iata_code": "DA"
    },
    {
      "id": "28202",
      "tax_id": "68",
      "tax_name": "Airport Security Charge",
      "iata_code": "DB"
    },
    {
      "id": "28203",
      "tax_id": "69",
      "tax_name": "Security Charge (Domestic/International)",
      "iata_code": "DC"
    },
    {
      "id": "28204",
      "tax_id": "70",
      "tax_name": "Concourse Fee (Intl)",
      "iata_code": "DD"
    },
    {
      "id": "28205",
      "tax_id": "71",
      "tax_name": "Airport Security Charge (Domestic/International)",
      "iata_code": "DE"
    },
    {
      "id": "28206",
      "tax_id": "72",
      "tax_name": "Security Charge (Intl)",
      "iata_code": "DF"
    },
    {
      "id": "28207",
      "tax_id": "73",
      "tax_name": "Resident Exit Tax (Timbre)",
      "iata_code": "DG"
    },
    {
      "id": "28208",
      "tax_id": "74",
      "tax_name": "Passenger Facility Charge",
      "iata_code": "DH"
    },
    {
      "id": "28209",
      "tax_id": "75",
      "tax_name": "Airport Facilitation Fee (International)",
      "iata_code": "DI"
    },
    {
      "id": "28210",
      "tax_id": "76",
      "tax_name": "Departure Tax",
      "iata_code": "DJ"
    },
    {
      "id": "28211",
      "tax_id": "77",
      "tax_name": "Value Added Tax (Passengers)",
      "iata_code": "DL"
    },
    {
      "id": "28212",
      "tax_id": "78",
      "tax_name": "Transportation Tax (International)",
      "iata_code": "DM"
    },
    {
      "id": "28213",
      "tax_id": "79",
      "tax_name": "Value Added Tax (Excess Baggage)",
      "iata_code": "DN"
    },
    {
      "id": "28214",
      "tax_id": "80",
      "tax_name": "Transportation Tax (Domestic/International)",
      "iata_code": "DO"
    },
    {
      "id": "28215",
      "tax_id": "81",
      "tax_name": "Goods and Services Tax (GST), (Domestic/International)",
      "iata_code": "DP"
    },
    {
      "id": "28216",
      "tax_id": "82",
      "tax_name": "Security Charge (Domestic/International)",
      "iata_code": "DQ"
    },
    {
      "id": "28217",
      "tax_id": "83",
      "tax_name": "Airport Facility Charge (Domestic/International)",
      "iata_code": "DR"
    },
    {
      "id": "28218",
      "tax_id": "84",
      "tax_name": "Safety Fee (Intl)",
      "iata_code": "DS"
    },
    {
      "id": "28219",
      "tax_id": "85",
      "tax_name": "Transfer Passenger Fee (Domestic/International)",
      "iata_code": "DT"
    },
    {
      "id": "28220",
      "tax_id": "86",
      "tax_name": "Embarkation Tax (Domestic/International)",
      "iata_code": "DW"
    },
    {
      "id": "28221",
      "tax_id": "87",
      "tax_name": "Aeronautical Development Charge (Intl)",
      "iata_code": "DX"
    },
    {
      "id": "28222",
      "tax_id": "88",
      "tax_name": "Tourism Arrival Tax",
      "iata_code": "DY"
    },
    {
      "id": "28223",
      "tax_id": "89",
      "tax_name": "Transportation / Fiscal / Airport Tax",
      "iata_code": "DZ"
    },
    {
      "id": "28224",
      "tax_id": "90",
      "tax_name": "Passenger Departure Tax",
      "iata_code": "EA"
    },
    {
      "id": "28225",
      "tax_id": "91",
      "tax_name": "Passenger and Safety Charge (Domestic/International)",
      "iata_code": "EB"
    },
    {
      "id": "28226",
      "tax_id": "92",
      "tax_name": "Government Transportation Tax (Domestic/International)",
      "iata_code": "EC"
    },
    {
      "id": "28227",
      "tax_id": "93",
      "tax_name": "Tourism Fee (International)",
      "iata_code": "ED"
    },
    {
      "id": "28228",
      "tax_id": "94",
      "tax_name": "Passenger Service Charge (Domestic/International)",
      "iata_code": "EE"
    },
    {
      "id": "28229",
      "tax_id": "95",
      "tax_name": "Security Tax (Domestic/International)",
      "iata_code": "EF"
    },
    {
      "id": "28230",
      "tax_id": "96",
      "tax_name": "Transportation Tax",
      "iata_code": "EG"
    },
    {
      "id": "28231",
      "tax_id": "97",
      "tax_name": "VAT Adjustment Tax (Dom)",
      "iata_code": "EI"
    },
    {
      "id": "28232",
      "tax_id": "98",
      "tax_name": "PTA surcharge (International)",
      "iata_code": "EJ"
    },
    {
      "id": "28233",
      "tax_id": "99",
      "tax_name": "Passenger Service and Security Fee (Domestic/International)",
      "iata_code": "EK"
    },
    {
      "id": "28234",
      "tax_id": "100",
      "tax_name": "Airport Improvement Fee",
      "iata_code": "EL"
    }
  ]
}
```

