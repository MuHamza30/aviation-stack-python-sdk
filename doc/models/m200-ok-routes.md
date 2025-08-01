
# M200 OK Routes

## Structure

`M200OKRoutes`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `pagination` | [`Pagination`](../../doc/models/pagination.md) | Required | - |
| `data` | [`List[Datum4]`](../../doc/models/datum-4.md) | Required | - |

## Example (as JSON)

```json
{
  "pagination": {
    "limit": 100,
    "offset": 0,
    "count": 100,
    "total": 208033
  },
  "data": [
    {
      "departure": {
        "airport": "Viru Viru International",
        "timezone": "America/La_Paz",
        "iata": "VVI",
        "icao": "SLVR",
        "terminal": "terminal8",
        "time": "09:45:00"
      },
      "arrival": {
        "airport": "J Wilsterman",
        "timezone": "America/La_Paz",
        "iata": "CBB",
        "icao": "SLCB",
        "terminal": "terminal4",
        "time": "10:30:00"
      },
      "airline": {
        "name": "Compania de Servicios de Transporte Aereo Amaszonas - Amaszonas S.A",
        "callsign": "AMAZONAS",
        "iata": "Z8",
        "icao": "AZN"
      },
      "flight": {
        "number": "173"
      }
    },
    {
      "departure": {
        "airport": "Prague Vaclav Havel Airport",
        "timezone": "Europe/Prague",
        "iata": "PRG",
        "icao": "LKPR",
        "terminal": "2",
        "time": "10:10:00"
      },
      "arrival": {
        "airport": "Kastrup",
        "timezone": "Europe/Copenhagen",
        "iata": "CPH",
        "icao": "EKCH",
        "terminal": "3",
        "time": "11:25:00"
      },
      "airline": {
        "name": "Air Nostrum",
        "callsign": "NOSTRU AIR",
        "iata": "YW",
        "icao": "ANE"
      },
      "flight": {
        "number": "1766"
      }
    },
    {
      "departure": {
        "airport": "Kastrup",
        "timezone": "Europe/Copenhagen",
        "iata": "CPH",
        "icao": "EKCH",
        "terminal": "3",
        "time": "08:15:00"
      },
      "arrival": {
        "airport": "Prague Vaclav Havel Airport",
        "timezone": "Europe/Prague",
        "iata": "PRG",
        "icao": "LKPR",
        "terminal": "2",
        "time": "09:30:00"
      },
      "airline": {
        "name": "Air Nostrum",
        "callsign": "NOSTRU AIR",
        "iata": "YW",
        "icao": "ANE"
      },
      "flight": {
        "number": "1761"
      }
    },
    {
      "departure": {
        "airport": "Adnan Menderes Airport",
        "timezone": "Europe/Istanbul",
        "iata": "ADB",
        "icao": "LTBJ",
        "terminal": "I",
        "time": "00:20:00"
      },
      "arrival": {
        "airport": "Cologne/bonn",
        "timezone": "Europe/Berlin",
        "iata": "CGN",
        "icao": "EDDK",
        "terminal": "2",
        "time": "02:45:00"
      },
      "airline": {
        "name": "SunExpress",
        "callsign": "SUNEXPRESS",
        "iata": "XQ",
        "icao": "SXS"
      },
      "flight": {
        "number": "902"
      }
    },
    {
      "departure": {
        "airport": "Logan International",
        "timezone": "America/New_York",
        "iata": "BOS",
        "icao": "KBOS",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Miami International Airport",
        "timezone": "America/New_York",
        "iata": "MIA",
        "icao": "KMIA",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "Xtra Airways",
        "callsign": "RUBY MOUNTAIN",
        "iata": "XP",
        "icao": "CXP"
      },
      "flight": {
        "number": "9803"
      }
    },
    {
      "departure": {
        "airport": "Logan International",
        "timezone": "America/New_York",
        "iata": "BOS",
        "icao": "KBOS",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Piedmont Triad International",
        "timezone": "America/New_York",
        "iata": "GSO",
        "icao": "KGSO",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "Xtra Airways",
        "callsign": "RUBY MOUNTAIN",
        "iata": "XP",
        "icao": "CXP"
      },
      "flight": {
        "number": "8801"
      }
    },
    {
      "departure": {
        "airport": "Franz Josef Strauss",
        "timezone": "Europe/Berlin",
        "iata": "MUC",
        "icao": "EDDM",
        "terminal": "1",
        "time": "06:05:00"
      },
      "arrival": {
        "airport": "Bourgas",
        "timezone": "Europe/Sofia",
        "iata": "BOJ",
        "icao": "LBBG",
        "terminal": "terminal4",
        "time": "09:25:00"
      },
      "airline": {
        "name": "SunExpress Deutschland GmbH",
        "callsign": "SUNRISE",
        "iata": "XG",
        "icao": "SXD"
      },
      "flight": {
        "number": "3291"
      }
    },
    {
      "departure": {
        "airport": "Bourgas",
        "timezone": "Europe/Sofia",
        "iata": "BOJ",
        "icao": "LBBG",
        "terminal": "terminal8",
        "time": "10:25:00"
      },
      "arrival": {
        "airport": "Franz Josef Strauss",
        "timezone": "Europe/Berlin",
        "iata": "MUC",
        "icao": "EDDM",
        "terminal": "1",
        "time": "11:55:00"
      },
      "airline": {
        "name": "SunExpress Deutschland GmbH",
        "callsign": "SUNRISE",
        "iata": "XG",
        "icao": "SXD"
      },
      "flight": {
        "number": "3290"
      }
    },
    {
      "departure": {
        "airport": "Stuttgart Echterdingen",
        "timezone": "Europe/Berlin",
        "iata": "STR",
        "icao": "EDDS",
        "terminal": "3",
        "time": "06:40:00"
      },
      "arrival": {
        "airport": "Aktion",
        "timezone": "Europe/Athens",
        "iata": "PVK",
        "icao": "LGPZ",
        "terminal": "terminal4",
        "time": "10:00:00"
      },
      "airline": {
        "name": "name2",
        "callsign": "callsign6",
        "iata": "X9",
        "icao": "NVD"
      },
      "flight": {
        "number": "1410"
      }
    },
    {
      "departure": {
        "airport": "Cologne/bonn",
        "timezone": "Europe/Berlin",
        "iata": "CGN",
        "icao": "EDDK",
        "terminal": "1",
        "time": "11:40:00"
      },
      "arrival": {
        "airport": "El Prat De Llobregat",
        "timezone": "Europe/Madrid",
        "iata": "BCN",
        "icao": "LEBL",
        "terminal": "2",
        "time": "13:50:00"
      },
      "airline": {
        "name": "TUIfly",
        "callsign": "HAPAG LLOYD",
        "iata": "X3",
        "icao": "TUI"
      },
      "flight": {
        "number": "526"
      }
    },
    {
      "departure": {
        "airport": "Kos Island International Airport",
        "timezone": "Europe/Athens",
        "iata": "KGS",
        "icao": "LGKO",
        "terminal": "terminal8",
        "time": "09:35:00"
      },
      "arrival": {
        "airport": "Düsseldorf International Airport",
        "timezone": "Europe/Berlin",
        "iata": "DUS",
        "icao": "EDDL",
        "terminal": "terminal4",
        "time": "12:00:00"
      },
      "airline": {
        "name": "TUIfly",
        "callsign": "HAPAG LLOYD",
        "iata": "X3",
        "icao": "TUI"
      },
      "flight": {
        "number": "4543"
      }
    },
    {
      "departure": {
        "airport": "Hanover Airport",
        "timezone": "Europe/Berlin",
        "iata": "HAJ",
        "icao": "EDDV",
        "terminal": "C",
        "time": "03:00:00"
      },
      "arrival": {
        "airport": "Nikos Kazantzakis Airport",
        "timezone": "Europe/Athens",
        "iata": "HER",
        "icao": "LGIR",
        "terminal": "terminal4",
        "time": "07:15:00"
      },
      "airline": {
        "name": "TUIfly",
        "callsign": "HAPAG LLOYD",
        "iata": "X3",
        "icao": "TUI"
      },
      "flight": {
        "number": "4170"
      }
    },
    {
      "departure": {
        "airport": "Rijeka",
        "timezone": "Europe/Zagreb",
        "iata": "RJK",
        "icao": "LDRI",
        "terminal": "terminal8",
        "time": "23:45:00"
      },
      "arrival": {
        "airport": "Hanover Airport",
        "timezone": "Europe/Berlin",
        "iata": "HAJ",
        "icao": "EDDV",
        "terminal": "A",
        "time": "01:35:00"
      },
      "airline": {
        "name": "TUIfly",
        "callsign": "HAPAG LLOYD",
        "iata": "X3",
        "icao": "TUI"
      },
      "flight": {
        "number": "3967"
      }
    },
    {
      "departure": {
        "airport": "Lambert-St. Louis International",
        "timezone": "America/Chicago",
        "iata": "STL",
        "icao": "KSTL",
        "terminal": "2",
        "time": "22:55:00"
      },
      "arrival": {
        "airport": "Keflavik International",
        "timezone": "Atlantic/Reykjavik",
        "iata": "KEF",
        "icao": "BIKF",
        "terminal": "terminal4",
        "time": "10:40:00"
      },
      "airline": {
        "name": "WOW Air ehf",
        "callsign": "WOWAIR",
        "iata": "WW",
        "icao": "WOW"
      },
      "flight": {
        "number": "168"
      }
    },
    {
      "departure": {
        "airport": "Baltimore/Washington International Thurgood Marshall",
        "timezone": "America/New_York",
        "iata": "BWI",
        "icao": "KBWI",
        "terminal": "terminal8",
        "time": "00:45:00"
      },
      "arrival": {
        "airport": "Keflavik International",
        "timezone": "Atlantic/Reykjavik",
        "iata": "KEF",
        "icao": "BIKF",
        "terminal": "terminal4",
        "time": "10:50:00"
      },
      "airline": {
        "name": "WOW Air ehf",
        "callsign": "WOWAIR",
        "iata": "WW",
        "icao": "WOW"
      },
      "flight": {
        "number": "116"
      }
    },
    {
      "departure": {
        "airport": "Kelowna Airport",
        "timezone": "America/Vancouver",
        "iata": "YLW",
        "icao": "CYLW",
        "terminal": "terminal8",
        "time": "09:05:00"
      },
      "arrival": {
        "airport": "Calgary International Airport",
        "timezone": "America/Edmonton",
        "iata": "YYC",
        "icao": "CYYC",
        "terminal": "terminal4",
        "time": "11:05:00"
      },
      "airline": {
        "name": "WestJet",
        "callsign": "WESTJET",
        "iata": "WS",
        "icao": "WJA"
      },
      "flight": {
        "number": "194"
      }
    },
    {
      "departure": {
        "airport": "Mc Carran International",
        "timezone": "America/Los_Angeles",
        "iata": "LAS",
        "icao": "KLAS",
        "terminal": "3",
        "time": "23:30:00"
      },
      "arrival": {
        "airport": "Lester B. Pearson International",
        "timezone": "America/Toronto",
        "iata": "YYZ",
        "icao": "CYYZ",
        "terminal": "3",
        "time": "06:47:00"
      },
      "airline": {
        "name": "WestJet",
        "callsign": "WESTJET",
        "iata": "WS",
        "icao": "WJA"
      },
      "flight": {
        "number": "1123"
      }
    },
    {
      "departure": {
        "airport": "Sacramento International",
        "timezone": "America/Los_Angeles",
        "iata": "SMF",
        "icao": "KSMF",
        "terminal": "B",
        "time": "time0"
      },
      "arrival": {
        "airport": "Long Beach Municipal",
        "timezone": "America/Los_Angeles",
        "iata": "LGB",
        "icao": "KLGB",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "Southwest Airlines Co.",
        "callsign": "SOUTHWEST",
        "iata": "WN",
        "icao": "SWA"
      },
      "flight": {
        "number": "8831"
      }
    },
    {
      "departure": {
        "airport": "Tromso/langnes",
        "timezone": "Europe/Oslo",
        "iata": "TOS",
        "icao": "ENTC",
        "terminal": "terminal8",
        "time": "11:25:00"
      },
      "arrival": {
        "airport": "Helsinki-vantaa",
        "timezone": "Europe/Helsinki",
        "iata": "HEL",
        "icao": "EFHK",
        "terminal": "2",
        "time": "14:20:00"
      },
      "airline": {
        "name": "Wideroe",
        "callsign": "WIDEROE",
        "iata": "WF",
        "icao": "WIF"
      },
      "flight": {
        "number": "946"
      }
    },
    {
      "departure": {
        "airport": "Edmonton International Airport",
        "timezone": "America/Edmonton",
        "iata": "YEG",
        "icao": "CYEG",
        "terminal": "terminal8",
        "time": "10:15:00"
      },
      "arrival": {
        "airport": "Vancouver International",
        "timezone": "America/Vancouver",
        "iata": "YVR",
        "icao": "CYVR",
        "terminal": "terminal4",
        "time": "11:13:00"
      },
      "airline": {
        "name": "WestJet Encore",
        "callsign": "ENCORE",
        "iata": "WR",
        "icao": "WEN"
      },
      "flight": {
        "number": "3361"
      }
    },
    {
      "departure": {
        "airport": "Kelowna Airport",
        "timezone": "America/Vancouver",
        "iata": "YLW",
        "icao": "CYLW",
        "terminal": "terminal8",
        "time": "08:00:00"
      },
      "arrival": {
        "airport": "Vancouver International",
        "timezone": "America/Vancouver",
        "iata": "YVR",
        "icao": "CYVR",
        "terminal": "terminal4",
        "time": "08:57:00"
      },
      "airline": {
        "name": "WestJet Encore",
        "callsign": "ENCORE",
        "iata": "WR",
        "icao": "WEN"
      },
      "flight": {
        "number": "3353"
      }
    },
    {
      "departure": {
        "airport": "La Aurora",
        "timezone": "America/Guatemala",
        "iata": "GUA",
        "icao": "MGGT",
        "terminal": "terminal8",
        "time": "06:17:00"
      },
      "arrival": {
        "airport": "El Salvador International",
        "timezone": "America/El_Salvador",
        "iata": "SAL",
        "icao": "MSLP",
        "terminal": "terminal4",
        "time": "07:15:00"
      },
      "airline": {
        "name": "Islena de Inversiones S.A. de C.V. dba Islena Airlines",
        "callsign": "callsign6",
        "iata": "WC",
        "icao": "ISV"
      },
      "flight": {
        "number": "589"
      }
    },
    {
      "departure": {
        "airport": "Ibiza",
        "timezone": "Europe/Madrid",
        "iata": "IBZ",
        "icao": "LEIB",
        "terminal": "1",
        "time": "time0"
      },
      "arrival": {
        "airport": "El Prat De Llobregat",
        "timezone": "Europe/Madrid",
        "iata": "BCN",
        "icao": "LEBL",
        "terminal": "1",
        "time": "time6"
      },
      "airline": {
        "name": "Vueling",
        "callsign": "VUELING",
        "iata": "VY",
        "icao": "VLG"
      },
      "flight": {
        "number": "6545"
      }
    },
    {
      "departure": {
        "airport": "Biarritz Parme",
        "timezone": "Europe/Paris",
        "iata": "BIQ",
        "icao": "LFBZ",
        "terminal": "terminal8",
        "time": "09:10:00"
      },
      "arrival": {
        "airport": "Marseille Provence Airport",
        "timezone": "Europe/Paris",
        "iata": "MRS",
        "icao": "LFML",
        "terminal": "1 Hall B",
        "time": "10:20:00"
      },
      "airline": {
        "name": "Volotea, S.L.",
        "callsign": "VOLOTEA",
        "iata": "V7",
        "icao": "VOE"
      },
      "flight": {
        "number": "2585"
      }
    },
    {
      "departure": {
        "airport": "Lester B. Pearson International",
        "timezone": "America/Toronto",
        "iata": "YYZ",
        "icao": "CYYZ",
        "terminal": "3",
        "time": "07:30:00"
      },
      "arrival": {
        "airport": "Vancouver International",
        "timezone": "America/Vancouver",
        "iata": "YVR",
        "icao": "CYVR",
        "terminal": "terminal4",
        "time": "09:40:00"
      },
      "airline": {
        "name": "Air Transat",
        "callsign": "AIR TRANSAT",
        "iata": "TS",
        "icao": "TSC"
      },
      "flight": {
        "number": "981"
      }
    },
    {
      "departure": {
        "airport": "Vancouver International",
        "timezone": "America/Vancouver",
        "iata": "YVR",
        "icao": "CYVR",
        "terminal": "D",
        "time": "22:55:00"
      },
      "arrival": {
        "airport": "Lester B. Pearson International",
        "timezone": "America/Toronto",
        "iata": "YYZ",
        "icao": "CYYZ",
        "terminal": "3",
        "time": "06:35:00"
      },
      "airline": {
        "name": "Air Transat",
        "callsign": "AIR TRANSAT",
        "iata": "TS",
        "icao": "TSC"
      },
      "flight": {
        "number": "970"
      }
    },
    {
      "departure": {
        "airport": "Hurghada",
        "timezone": "Africa/Cairo",
        "iata": "HRG",
        "icao": "HEGN",
        "terminal": "terminal8",
        "time": "21:45:00"
      },
      "arrival": {
        "airport": "Birmingham International Airport",
        "timezone": "Europe/London",
        "iata": "BHX",
        "icao": "EGBB",
        "terminal": "terminal4",
        "time": "02:35:00"
      },
      "airline": {
        "name": "TUI Airways Limited",
        "callsign": "TOMJET",
        "iata": "BY",
        "icao": "TOM"
      },
      "flight": {
        "number": "549"
      }
    },
    {
      "departure": {
        "airport": "Manchester Airport",
        "timezone": "Europe/London",
        "iata": "MAN",
        "icao": "EGCC",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Glasgow International",
        "timezone": "Europe/London",
        "iata": "GLA",
        "icao": "EGPF",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "Thomas Cook Airlines Limited of Manchester",
        "callsign": "KESTREL",
        "iata": "MT",
        "icao": "TCX"
      },
      "flight": {
        "number": "4892"
      }
    },
    {
      "departure": {
        "airport": "Antalya",
        "timezone": "Europe/Istanbul",
        "iata": "AYT",
        "icao": "LTAI",
        "terminal": "2",
        "time": "01:10:00"
      },
      "arrival": {
        "airport": "Manchester Airport",
        "timezone": "Europe/London",
        "iata": "MAN",
        "icao": "EGCC",
        "terminal": "1",
        "time": "04:00:00"
      },
      "airline": {
        "name": "Thomas Cook Airlines Limited of Manchester",
        "callsign": "KESTREL",
        "iata": "MT",
        "icao": "TCX"
      },
      "flight": {
        "number": "309"
      }
    },
    {
      "departure": {
        "airport": "Gatwick",
        "timezone": "Europe/London",
        "iata": "LGW",
        "icao": "EGKK",
        "terminal": "S",
        "time": "09:00:00"
      },
      "arrival": {
        "airport": "Megas Alexandros International",
        "timezone": "Europe/Athens",
        "iata": "KVA",
        "icao": "LGKV",
        "terminal": "terminal4",
        "time": "14:20:00"
      },
      "airline": {
        "name": "Thomas Cook Airlines Limited of Manchester",
        "callsign": "KESTREL",
        "iata": "MT",
        "icao": "TCX"
      },
      "flight": {
        "number": "1044"
      }
    },
    {
      "departure": {
        "airport": "Istanbul Airport",
        "timezone": "Europe/Istanbul",
        "iata": "IST",
        "icao": "LTBA",
        "terminal": "terminal8",
        "time": "03:30:00"
      },
      "arrival": {
        "airport": "airport2",
        "timezone": "timezone6",
        "iata": "IKA",
        "icao": "OIIE",
        "terminal": "terminal4",
        "time": "07:30:00"
      },
      "airline": {
        "name": "ATA Airlines",
        "callsign": "ATALAR AIR",
        "iata": "I3",
        "icao": "TBZ"
      },
      "flight": {
        "number": "7272"
      }
    },
    {
      "departure": {
        "airport": "airport6",
        "timezone": "timezone0",
        "iata": "IKA",
        "icao": "OIIE",
        "terminal": "terminal8",
        "time": "00:30:00"
      },
      "arrival": {
        "airport": "Istanbul Airport",
        "timezone": "Europe/Istanbul",
        "iata": "IST",
        "icao": "LTBA",
        "terminal": "terminal4",
        "time": "02:30:00"
      },
      "airline": {
        "name": "ATA Airlines",
        "callsign": "ATALAR AIR",
        "iata": "I3",
        "icao": "TBZ"
      },
      "flight": {
        "number": "7271"
      }
    },
    {
      "departure": {
        "airport": "Logan International",
        "timezone": "America/New_York",
        "iata": "BOS",
        "icao": "KBOS",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Miami International Airport",
        "timezone": "America/New_York",
        "iata": "MIA",
        "icao": "KMIA",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "SWIFT AIR,L.L.C.",
        "callsign": "SWIFTFLIGHT",
        "iata": "WQ",
        "icao": "SWQ"
      },
      "flight": {
        "number": "9554"
      }
    },
    {
      "departure": {
        "airport": "Nassau International",
        "timezone": "America/Nassau",
        "iata": "NAS",
        "icao": "MYNN",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Logan International",
        "timezone": "America/New_York",
        "iata": "BOS",
        "icao": "KBOS",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "SWIFT AIR,L.L.C.",
        "callsign": "SWIFTFLIGHT",
        "iata": "WQ",
        "icao": "SWQ"
      },
      "flight": {
        "number": "7562"
      }
    },
    {
      "departure": {
        "airport": "Louis Armstrong New Orléans International Airport",
        "timezone": "America/Chicago",
        "iata": "MSY",
        "icao": "KMSY",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Cancún International",
        "timezone": "America/Cancun",
        "iata": "CUN",
        "icao": "MMUN",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "Sunwing Airlines Inc.",
        "callsign": "SUNWING",
        "iata": "WG",
        "icao": "SWG"
      },
      "flight": {
        "number": "4090"
      }
    },
    {
      "departure": {
        "airport": "Düsseldorf International Airport",
        "timezone": "Europe/Berlin",
        "iata": "DUS",
        "icao": "EDDL",
        "terminal": "terminal8",
        "time": "06:10:00"
      },
      "arrival": {
        "airport": "Diagoras",
        "timezone": "Europe/Athens",
        "iata": "RHO",
        "icao": "LGRP",
        "terminal": "terminal4",
        "time": "11:00:00"
      },
      "airline": {
        "name": "Germania",
        "callsign": "GERMANIA",
        "iata": "ST",
        "icao": "GMI"
      },
      "flight": {
        "number": "4956"
      }
    },
    {
      "departure": {
        "airport": "Nürnberg",
        "timezone": "Europe/Berlin",
        "iata": "NUE",
        "icao": "EDDN",
        "terminal": "terminal8",
        "time": "11:15:00"
      },
      "arrival": {
        "airport": "Son Sant Joan Airport",
        "timezone": "Europe/Madrid",
        "iata": "PMI",
        "icao": "LEPA",
        "terminal": "terminal4",
        "time": "13:35:00"
      },
      "airline": {
        "name": "Germania",
        "callsign": "GERMANIA",
        "iata": "ST",
        "icao": "GMI"
      },
      "flight": {
        "number": "3910"
      }
    },
    {
      "departure": {
        "airport": "Nürnberg",
        "timezone": "Europe/Berlin",
        "iata": "NUE",
        "icao": "EDDN",
        "terminal": "terminal8",
        "time": "12:00:00"
      },
      "arrival": {
        "airport": "Poretta",
        "timezone": "Europe/Paris",
        "iata": "BIA",
        "icao": "LFKB",
        "terminal": "terminal4",
        "time": "13:35:00"
      },
      "airline": {
        "name": "Germania",
        "callsign": "GERMANIA",
        "iata": "ST",
        "icao": "GMI"
      },
      "flight": {
        "number": "3306"
      }
    },
    {
      "departure": {
        "airport": "Dresden Airport",
        "timezone": "Europe/Berlin",
        "iata": "DRS",
        "icao": "EDDC",
        "terminal": "terminal8",
        "time": "07:50:00"
      },
      "arrival": {
        "airport": "Poretta",
        "timezone": "Europe/Paris",
        "iata": "BIA",
        "icao": "LFKB",
        "terminal": "terminal4",
        "time": "09:45:00"
      },
      "airline": {
        "name": "Germania",
        "callsign": "GERMANIA",
        "iata": "ST",
        "icao": "GMI"
      },
      "flight": {
        "number": "3248"
      }
    },
    {
      "departure": {
        "airport": "Laage",
        "timezone": "Europe/Berlin",
        "iata": "RLG",
        "icao": "ETNL",
        "terminal": "terminal8",
        "time": "04:30:00"
      },
      "arrival": {
        "airport": "Bourgas",
        "timezone": "Europe/Sofia",
        "iata": "BOJ",
        "icao": "LBBG",
        "terminal": "terminal4",
        "time": "08:00:00"
      },
      "airline": {
        "name": "Germania",
        "callsign": "GERMANIA",
        "iata": "ST",
        "icao": "GMI"
      },
      "flight": {
        "number": "2998"
      }
    },
    {
      "departure": {
        "airport": "Nordela (São Miguel Island)",
        "timezone": "Atlantic/Azores",
        "iata": "PDL",
        "icao": "LPPD",
        "terminal": "T1",
        "time": "11:20:00"
      },
      "arrival": {
        "airport": "Pico Island",
        "timezone": "Atlantic/Azores",
        "iata": "PIX",
        "icao": "LPPI",
        "terminal": "terminal4",
        "time": "12:20:00"
      },
      "airline": {
        "name": "SATA Air Acores",
        "callsign": "SATA",
        "iata": "SP",
        "icao": "SAT"
      },
      "flight": {
        "number": "2432"
      }
    },
    {
      "departure": {
        "airport": "Brussels Airport",
        "timezone": "Europe/Brussels",
        "iata": "BRU",
        "icao": "EBBR",
        "terminal": "terminal8",
        "time": "06:20:00"
      },
      "arrival": {
        "airport": "Reus",
        "timezone": "Europe/Madrid",
        "iata": "REU",
        "icao": "LERS",
        "terminal": "1",
        "time": "08:20:00"
      },
      "airline": {
        "name": "Brussels Airlines",
        "callsign": "B-LINE",
        "iata": "SN",
        "icao": "BEL"
      },
      "flight": {
        "number": "3685"
      }
    },
    {
      "departure": {
        "airport": "Brussels Airport",
        "timezone": "Europe/Brussels",
        "iata": "BRU",
        "icao": "EBBR",
        "terminal": "terminal8",
        "time": "06:10:00"
      },
      "arrival": {
        "airport": "Girona-Costa Brava",
        "timezone": "Europe/Madrid",
        "iata": "GRO",
        "icao": "LEGE",
        "terminal": "1",
        "time": "07:55:00"
      },
      "airline": {
        "name": "Brussels Airlines",
        "callsign": "B-LINE",
        "iata": "SN",
        "icao": "BEL"
      },
      "flight": {
        "number": "3683"
      }
    },
    {
      "departure": {
        "airport": "Landvetter",
        "timezone": "Europe/Stockholm",
        "iata": "GOT",
        "icao": "ESGG",
        "terminal": "A",
        "time": "time0"
      },
      "arrival": {
        "airport": "Samos",
        "timezone": "Europe/Athens",
        "iata": "SMI",
        "icao": "LGSM",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "SAS",
        "callsign": "SCANDINAVIAN",
        "iata": "SK",
        "icao": "SAS"
      },
      "flight": {
        "number": "7629"
      }
    },
    {
      "departure": {
        "airport": "Gardermoen",
        "timezone": "Europe/Oslo",
        "iata": "OSL",
        "icao": "ENGM",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Svalbard",
        "timezone": "Arctic/Longyearbyen",
        "iata": "LYR",
        "icao": "ENSB",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "SAS",
        "callsign": "SCANDINAVIAN",
        "iata": "SK",
        "icao": "SAS"
      },
      "flight": {
        "number": "7086"
      }
    },
    {
      "departure": {
        "airport": "Tolmachevo",
        "timezone": "Asia/Novosibirsk",
        "iata": "OVB",
        "icao": "UNNT",
        "terminal": "A",
        "time": "10:20:00"
      },
      "arrival": {
        "airport": "Koltsovo International",
        "timezone": "Asia/Yekaterinburg",
        "iata": "SVX",
        "icao": "USSS",
        "terminal": "terminal4",
        "time": "10:45:00"
      },
      "airline": {
        "name": "S7 Airlines",
        "callsign": "SIBERIAN AIRLINES",
        "iata": "S7",
        "icao": "SBI"
      },
      "flight": {
        "number": "3249"
      }
    },
    {
      "departure": {
        "airport": "Da Nang",
        "timezone": "Asia/Ho_Chi_Minh",
        "iata": "DAD",
        "icao": "VVDN",
        "terminal": "terminal8",
        "time": "02:20:00"
      },
      "arrival": {
        "airport": "Seoul (Incheon)",
        "timezone": "Asia/Seoul",
        "iata": "ICN",
        "icao": "RKSI",
        "terminal": "1",
        "time": "08:40:00"
      },
      "airline": {
        "name": "name2",
        "callsign": "callsign6",
        "iata": "RS",
        "icao": "ASV"
      },
      "flight": {
        "number": "552"
      }
    },
    {
      "departure": {
        "airport": "Lester B. Pearson International",
        "timezone": "America/Toronto",
        "iata": "YYZ",
        "icao": "CYYZ",
        "terminal": "3",
        "time": "06:20:00"
      },
      "arrival": {
        "airport": "Cancún International",
        "timezone": "America/Cancun",
        "iata": "CUN",
        "icao": "MMUN",
        "terminal": "2",
        "time": "09:25:00"
      },
      "airline": {
        "name": "Travel Service, A.S.",
        "callsign": "SKYTRAVEL",
        "iata": "QS",
        "icao": "TVS"
      },
      "flight": {
        "number": "535"
      }
    },
    {
      "departure": {
        "airport": "Charles De Gaulle",
        "timezone": "Europe/Paris",
        "iata": "CDG",
        "icao": "LFPG",
        "terminal": "3",
        "time": "06:05:00"
      },
      "arrival": {
        "airport": "Nikos Kazantzakis Airport",
        "timezone": "Europe/Athens",
        "iata": "HER",
        "icao": "LGIR",
        "terminal": "terminal4",
        "time": "10:45:00"
      },
      "airline": {
        "name": "Travel Service, A.S.",
        "callsign": "SKYTRAVEL",
        "iata": "QS",
        "icao": "TVS"
      },
      "flight": {
        "number": "3452"
      }
    },
    {
      "departure": {
        "airport": "Cayo Largo Del Sur",
        "timezone": "America/Havana",
        "iata": "CYO",
        "icao": "MUCL",
        "terminal": "terminal8",
        "time": "21:05:00"
      },
      "arrival": {
        "airport": "Pierre Elliott Trudeau International",
        "timezone": "America/Montreal",
        "iata": "YUL",
        "icao": "CYUL",
        "terminal": "terminal4",
        "time": "00:55:00"
      },
      "airline": {
        "name": "Travel Service, A.S.",
        "callsign": "SKYTRAVEL",
        "iata": "QS",
        "icao": "TVS"
      },
      "flight": {
        "number": "2813"
      }
    },
    {
      "departure": {
        "airport": "Prague Vaclav Havel Airport",
        "timezone": "Europe/Prague",
        "iata": "PRG",
        "icao": "LKPR",
        "terminal": "2",
        "time": "03:10:00"
      },
      "arrival": {
        "airport": "Kos Island International Airport",
        "timezone": "Europe/Athens",
        "iata": "KGS",
        "icao": "LGKO",
        "terminal": "terminal4",
        "time": "06:55:00"
      },
      "airline": {
        "name": "Travel Service, A.S.",
        "callsign": "SKYTRAVEL",
        "iata": "QS",
        "icao": "TVS"
      },
      "flight": {
        "number": "1036"
      }
    },
    {
      "departure": {
        "airport": "Vancouver International",
        "timezone": "America/Vancouver",
        "iata": "YVR",
        "icao": "CYVR",
        "terminal": "I",
        "time": "08:55:00"
      },
      "arrival": {
        "airport": "Sacramento International",
        "timezone": "America/Los_Angeles",
        "iata": "SMF",
        "icao": "KSMF",
        "terminal": "A",
        "time": "11:06:00"
      },
      "airline": {
        "name": "Jazz Aviation LP",
        "callsign": "JAZZ",
        "iata": "QK",
        "icao": "JZA"
      },
      "flight": {
        "number": "8042"
      }
    },
    {
      "departure": {
        "airport": "Sharm el-Sheikh International Airport",
        "timezone": "Africa/Cairo",
        "iata": "SSH",
        "icao": "HESH",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Boryspil (Borispol)",
        "timezone": "Europe/Kiev",
        "iata": "KBP",
        "icao": "UKBB",
        "terminal": "D",
        "time": "time6"
      },
      "airline": {
        "name": "Ukraine International Airlines",
        "callsign": "UKRAINE INTERNATIONAL",
        "iata": "PS",
        "icao": "AUI"
      },
      "flight": {
        "number": "6012"
      }
    },
    {
      "departure": {
        "airport": "Newark Liberty International",
        "timezone": "America/New_York",
        "iata": "EWR",
        "icao": "KEWR",
        "terminal": "B",
        "time": "23:30:00"
      },
      "arrival": {
        "airport": "Birmingham International Airport",
        "timezone": "Europe/London",
        "iata": "BHX",
        "icao": "EGBB",
        "terminal": "terminal4",
        "time": "11:30:00"
      },
      "airline": {
        "name": "Primera Air Scandinavia A/S",
        "callsign": "PRIMERA",
        "iata": "PF",
        "icao": "PRI"
      },
      "flight": {
        "number": "52"
      }
    },
    {
      "departure": {
        "airport": "Adnan Menderes Airport",
        "timezone": "Europe/Istanbul",
        "iata": "ADB",
        "icao": "LTBJ",
        "terminal": "I",
        "time": "09:45:00"
      },
      "arrival": {
        "airport": "Ercan",
        "timezone": "Asia/Nicosia",
        "iata": "ECN",
        "icao": "LCEN",
        "terminal": "terminal4",
        "time": "11:05:00"
      },
      "airline": {
        "name": "Pegasus Airlines",
        "callsign": "SUNTURK",
        "iata": "PC",
        "icao": "PGT"
      },
      "flight": {
        "number": "7040"
      }
    },
    {
      "departure": {
        "airport": "Antalya",
        "timezone": "Europe/Istanbul",
        "iata": "AYT",
        "icao": "LTAI",
        "terminal": "1",
        "time": "time0"
      },
      "arrival": {
        "airport": "Franz Josef Strauss",
        "timezone": "Europe/Berlin",
        "iata": "MUC",
        "icao": "EDDM",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "Pegasus Airlines",
        "callsign": "SUNTURK",
        "iata": "PC",
        "icao": "PGT"
      },
      "flight": {
        "number": "5037"
      }
    },
    {
      "departure": {
        "airport": "Belgrade Nikola Tesla",
        "timezone": "Europe/Belgrade",
        "iata": "BEG",
        "icao": "LYBE",
        "terminal": "2",
        "time": "08:25:00"
      },
      "arrival": {
        "airport": "Sabiha Gokcen",
        "timezone": "Europe/Istanbul",
        "iata": "SAW",
        "icao": "LTFJ",
        "terminal": "terminal4",
        "time": "11:10:00"
      },
      "airline": {
        "name": "Pegasus Airlines",
        "callsign": "SUNTURK",
        "iata": "PC",
        "icao": "PGT"
      },
      "flight": {
        "number": "1908"
      }
    },
    {
      "departure": {
        "airport": "Sabiha Gokcen",
        "timezone": "Europe/Istanbul",
        "iata": "SAW",
        "icao": "LTFJ",
        "terminal": "terminal8",
        "time": "06:35:00"
      },
      "arrival": {
        "airport": "Belgrade Nikola Tesla",
        "timezone": "Europe/Belgrade",
        "iata": "BEG",
        "icao": "LYBE",
        "terminal": "2",
        "time": "07:35:00"
      },
      "airline": {
        "name": "Pegasus Airlines",
        "callsign": "SUNTURK",
        "iata": "PC",
        "icao": "PGT"
      },
      "flight": {
        "number": "1907"
      }
    },
    {
      "departure": {
        "airport": "Hartsfield-jackson Atlanta International",
        "timezone": "America/New_York",
        "iata": "ATL",
        "icao": "KATL",
        "terminal": "S",
        "time": "10:31:00"
      },
      "arrival": {
        "airport": "Lovell Field",
        "timezone": "America/New_York",
        "iata": "CHA",
        "icao": "KCHA",
        "terminal": "terminal4",
        "time": "11:22:00"
      },
      "airline": {
        "name": "SkyWest Airlines",
        "callsign": "SKYWEST",
        "iata": "OO",
        "icao": "SKW"
      },
      "flight": {
        "number": "4322"
      }
    },
    {
      "departure": {
        "airport": "Antalya",
        "timezone": "Europe/Istanbul",
        "iata": "AYT",
        "icao": "LTAI",
        "terminal": "2",
        "time": "21:30:00"
      },
      "arrival": {
        "airport": "Koltsovo International",
        "timezone": "Asia/Yekaterinburg",
        "iata": "SVX",
        "icao": "USSS",
        "terminal": "terminal4",
        "time": "03:50:00"
      },
      "airline": {
        "name": "Onur Air",
        "callsign": "ONUR AIR",
        "iata": "8Q",
        "icao": "OHY"
      },
      "flight": {
        "number": "887"
      }
    },
    {
      "departure": {
        "airport": "Juana Azurduy de Padilla",
        "timezone": "America/La_Paz",
        "iata": "SRE",
        "icao": "SLSU",
        "terminal": "terminal8",
        "time": "07:00:00"
      },
      "arrival": {
        "airport": "J Wilsterman",
        "timezone": "America/La_Paz",
        "iata": "CBB",
        "icao": "SLCB",
        "terminal": "terminal4",
        "time": "07:40:00"
      },
      "airline": {
        "name": "Boliviana de Aviacion - BoA",
        "callsign": "BOLIVIANO",
        "iata": "OB",
        "icao": "BOV"
      },
      "flight": {
        "number": "571"
      }
    },
    {
      "departure": {
        "airport": "Milano Malpensa",
        "timezone": "Europe/Rome",
        "iata": "MXP",
        "icao": "LIMC",
        "terminal": "1",
        "time": "06:00:00"
      },
      "arrival": {
        "airport": "Diagoras",
        "timezone": "Europe/Athens",
        "iata": "RHO",
        "icao": "LGRP",
        "terminal": "terminal4",
        "time": "09:45:00"
      },
      "airline": {
        "name": "name2",
        "callsign": "callsign6",
        "iata": "NO",
        "icao": "NOS"
      },
      "flight": {
        "number": "6978"
      }
    },
    {
      "departure": {
        "airport": "Nikos Kazantzakis Airport",
        "timezone": "Europe/Athens",
        "iata": "HER",
        "icao": "LGIR",
        "terminal": "terminal8",
        "time": "11:25:00"
      },
      "arrival": {
        "airport": "Milano Malpensa",
        "timezone": "Europe/Rome",
        "iata": "MXP",
        "icao": "LIMC",
        "terminal": "1",
        "time": "13:10:00"
      },
      "airline": {
        "name": "name2",
        "callsign": "callsign6",
        "iata": "NO",
        "icao": "NOS"
      },
      "flight": {
        "number": "6741"
      }
    },
    {
      "departure": {
        "airport": "Detroit Metropolitan Wayne County",
        "timezone": "America/Detroit",
        "iata": "DTW",
        "icao": "KDTW",
        "terminal": "N",
        "time": "time0"
      },
      "arrival": {
        "airport": "George Bush Intercontinental",
        "timezone": "America/Chicago",
        "iata": "IAH",
        "icao": "KIAH",
        "terminal": "A",
        "time": "time6"
      },
      "airline": {
        "name": "Spirit Airlines",
        "callsign": "SPIRIT WINGS",
        "iata": "NK",
        "icao": "NKS"
      },
      "flight": {
        "number": "8685"
      }
    },
    {
      "departure": {
        "airport": "La Araucanía Airport",
        "timezone": "timezone0",
        "iata": "ZCO",
        "icao": "SCTC",
        "terminal": "1",
        "time": "10:17:00"
      },
      "arrival": {
        "airport": "Arturo Merino Benitez",
        "timezone": "America/Santiago",
        "iata": "SCL",
        "icao": "SCEL",
        "terminal": "terminal4",
        "time": "11:35:00"
      },
      "airline": {
        "name": "Transporte Aereo S.A. dba LATAM Airlines Chile",
        "callsign": "LANEX",
        "iata": "LU",
        "icao": "LXP"
      },
      "flight": {
        "number": "232"
      }
    },
    {
      "departure": {
        "airport": "Rodriguez Ballon",
        "timezone": "America/Lima",
        "iata": "AQP",
        "icao": "SPQU",
        "terminal": "1",
        "time": "09:40:00"
      },
      "arrival": {
        "airport": "Jorge Chavez International",
        "timezone": "America/Lima",
        "iata": "LIM",
        "icao": "SPJC",
        "terminal": "terminal4",
        "time": "11:17:00"
      },
      "airline": {
        "name": "Lan Peru",
        "callsign": "PATAGONIA",
        "iata": "LP",
        "icao": "LPE"
      },
      "flight": {
        "number": "2136"
      }
    },
    {
      "departure": {
        "airport": "Istanbul Airport",
        "timezone": "Europe/Istanbul",
        "iata": "IST",
        "icao": "LTBA",
        "terminal": "D",
        "time": "10:25:00"
      },
      "arrival": {
        "airport": "Belgrade Nikola Tesla",
        "timezone": "Europe/Belgrade",
        "iata": "BEG",
        "icao": "LYBE",
        "terminal": "terminal4",
        "time": "11:10:00"
      },
      "airline": {
        "name": "Atlasjet Airlines",
        "callsign": "ATLASGLOBAL",
        "iata": "KK",
        "icao": "KKK"
      },
      "flight": {
        "number": "5625"
      }
    },
    {
      "departure": {
        "airport": "Birmingham",
        "timezone": "America/Chicago",
        "iata": "BHM",
        "icao": "KBHM",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Ronald Reagan Washington National Airport",
        "timezone": "America/New_York",
        "iata": "DCA",
        "icao": "KDCA",
        "terminal": "C",
        "time": "time6"
      },
      "airline": {
        "name": "PSA Airlines",
        "callsign": "BLUE STREAK",
        "iata": "OH",
        "icao": "JIA"
      },
      "flight": {
        "number": "9924"
      }
    },
    {
      "departure": {
        "airport": "El Loa",
        "timezone": "America/Santiago",
        "iata": "CJC",
        "icao": "SCCF",
        "terminal": "terminal8",
        "time": "22:09:00"
      },
      "arrival": {
        "airport": "Arturo Merino Benitez",
        "timezone": "America/Santiago",
        "iata": "SCL",
        "icao": "SCEL",
        "terminal": "terminal4",
        "time": "00:10:00"
      },
      "airline": {
        "name": "name2",
        "callsign": "callsign6",
        "iata": "JA",
        "icao": "JAT"
      },
      "flight": {
        "number": "11"
      }
    },
    {
      "departure": {
        "airport": "Bourgas",
        "timezone": "Europe/Sofia",
        "iata": "BOJ",
        "icao": "LBBG",
        "terminal": "terminal8",
        "time": "11:05:00"
      },
      "arrival": {
        "airport": "Charles De Gaulle",
        "timezone": "Europe/Paris",
        "iata": "CDG",
        "icao": "LFPG",
        "terminal": "3",
        "time": "13:30:00"
      },
      "airline": {
        "name": "TUI Airlines Belgium t/a Jetairfly",
        "callsign": "BEAUTY",
        "iata": "TB",
        "icao": "JAF"
      },
      "flight": {
        "number": "6232"
      }
    },
    {
      "departure": {
        "airport": "Eilat",
        "timezone": "Asia/Jerusalem",
        "iata": "ETH",
        "icao": "LLET",
        "terminal": "terminal8",
        "time": "09:35:00"
      },
      "arrival": {
        "airport": "Ben Gurion International",
        "timezone": "Asia/Jerusalem",
        "iata": "TLV",
        "icao": "LLBG",
        "terminal": "3",
        "time": "10:30:00"
      },
      "airline": {
        "name": "Arkia Israeli Airlines",
        "callsign": "ARKIA",
        "iata": "IZ",
        "icao": "AIZ"
      },
      "flight": {
        "number": "1806"
      }
    },
    {
      "departure": {
        "airport": "airport6",
        "timezone": "timezone0",
        "iata": "IKA",
        "icao": "OIIE",
        "terminal": "terminal8",
        "time": "00:25:00"
      },
      "arrival": {
        "airport": "Istanbul Airport",
        "timezone": "Europe/Istanbul",
        "iata": "IST",
        "icao": "LTBA",
        "terminal": "I",
        "time": "02:10:00"
      },
      "airline": {
        "name": "Iran Air",
        "callsign": "IRANAIR",
        "iata": "IR",
        "icao": "IRA"
      },
      "flight": {
        "number": "5369"
      }
    },
    {
      "departure": {
        "airport": "Istanbul Airport",
        "timezone": "Europe/Istanbul",
        "iata": "IST",
        "icao": "LTBA",
        "terminal": "I",
        "time": "03:40:00"
      },
      "arrival": {
        "airport": "airport2",
        "timezone": "timezone6",
        "iata": "IKA",
        "icao": "OIIE",
        "terminal": "terminal4",
        "time": "08:15:00"
      },
      "airline": {
        "name": "Iran Air",
        "callsign": "IRANAIR",
        "iata": "IR",
        "icao": "IRA"
      },
      "flight": {
        "number": "5368"
      }
    },
    {
      "departure": {
        "airport": "Son Sant Joan Airport",
        "timezone": "Europe/Madrid",
        "iata": "PMI",
        "icao": "LEPA",
        "terminal": "terminal8",
        "time": "10:40:00"
      },
      "arrival": {
        "airport": "Mahon",
        "timezone": "Europe/Madrid",
        "iata": "MAH",
        "icao": "LEMH",
        "terminal": "1",
        "time": "11:25:00"
      },
      "airline": {
        "name": "IBERIA",
        "callsign": "IBERIA",
        "iata": "IB",
        "icao": "IBE"
      },
      "flight": {
        "number": "8482"
      }
    },
    {
      "departure": {
        "airport": "Vnukovo",
        "timezone": "Europe/Moscow",
        "iata": "VKO",
        "icao": "UUWW",
        "terminal": "A",
        "time": "00:35:00"
      },
      "arrival": {
        "airport": "Hong Kong International",
        "timezone": "Asia/Hong_Kong",
        "iata": "HKG",
        "icao": "VHHH",
        "terminal": "1",
        "time": "15:15:00"
      },
      "airline": {
        "name": "Hong Kong Airlines",
        "callsign": "BAUHINIA",
        "iata": "HX",
        "icao": "CRK"
      },
      "flight": {
        "number": "2018"
      }
    },
    {
      "departure": {
        "airport": "Mérignac",
        "timezone": "Europe/Paris",
        "iata": "BOD",
        "icao": "LFBD",
        "terminal": "B",
        "time": "09:20:00"
      },
      "arrival": {
        "airport": "Marseille Provence Airport",
        "timezone": "Europe/Paris",
        "iata": "MRS",
        "icao": "LFML",
        "terminal": "1 Hall B",
        "time": "10:25:00"
      },
      "airline": {
        "name": "HOP!",
        "callsign": "AIR HOP",
        "iata": "A5",
        "icao": "HOP"
      },
      "flight": {
        "number": "3283"
      }
    },
    {
      "departure": {
        "airport": "Marseille Provence Airport",
        "timezone": "Europe/Paris",
        "iata": "MRS",
        "icao": "LFML",
        "terminal": "1 Hall B",
        "time": "11:20:00"
      },
      "arrival": {
        "airport": "Mérignac",
        "timezone": "Europe/Paris",
        "iata": "BOD",
        "icao": "LFBD",
        "terminal": "B",
        "time": "12:25:00"
      },
      "airline": {
        "name": "HOP!",
        "callsign": "AIR HOP",
        "iata": "A5",
        "icao": "HOP"
      },
      "flight": {
        "number": "3282"
      }
    },
    {
      "departure": {
        "airport": "Stuttgart Echterdingen",
        "timezone": "Europe/Berlin",
        "iata": "STR",
        "icao": "EDDS",
        "terminal": "1",
        "time": "11:50:00"
      },
      "arrival": {
        "airport": "Mostar",
        "timezone": "Europe/Sarajevo",
        "iata": "OMO",
        "icao": "LQMO",
        "terminal": "terminal4",
        "time": "14:20:00"
      },
      "airline": {
        "name": "LGW-Luftfahrtgesellschaft Walter GmbH",
        "callsign": "WALTER",
        "iata": "HE",
        "icao": "LGW"
      },
      "flight": {
        "number": "2700"
      }
    },
    {
      "departure": {
        "airport": "Stuttgart Echterdingen",
        "timezone": "Europe/Berlin",
        "iata": "STR",
        "icao": "EDDS",
        "terminal": "1",
        "time": "06:25:00"
      },
      "arrival": {
        "airport": "Pula",
        "timezone": "Europe/Zagreb",
        "iata": "PUY",
        "icao": "LDPL",
        "terminal": "terminal4",
        "time": "07:45:00"
      },
      "airline": {
        "name": "LGW-Luftfahrtgesellschaft Walter GmbH",
        "callsign": "WALTER",
        "iata": "HE",
        "icao": "LGW"
      },
      "flight": {
        "number": "2144"
      }
    },
    {
      "departure": {
        "airport": "Orlando Sanford International",
        "timezone": "America/New_York",
        "iata": "SFB",
        "icao": "KSFB",
        "terminal": "terminal8",
        "time": "07:10:00"
      },
      "arrival": {
        "airport": "Shreveport Regional Airport",
        "timezone": "America/Chicago",
        "iata": "SHV",
        "icao": "KSHV",
        "terminal": "terminal4",
        "time": "08:41:00"
      },
      "airline": {
        "name": "Allegiant Air LLC",
        "callsign": "ALLEGIANT",
        "iata": "G4",
        "icao": "AAY"
      },
      "flight": {
        "number": "668"
      }
    },
    {
      "departure": {
        "airport": "Orlando Sanford International",
        "timezone": "America/New_York",
        "iata": "SFB",
        "icao": "KSFB",
        "terminal": "B",
        "time": "06:50:00"
      },
      "arrival": {
        "airport": "Hector Field",
        "timezone": "America/Chicago",
        "iata": "FAR",
        "icao": "KFAR",
        "terminal": "terminal4",
        "time": "09:31:00"
      },
      "airline": {
        "name": "Allegiant Air LLC",
        "callsign": "ALLEGIANT",
        "iata": "G4",
        "icao": "AAY"
      },
      "flight": {
        "number": "634"
      }
    },
    {
      "departure": {
        "airport": "Provo",
        "timezone": "America/Denver",
        "iata": "PVU",
        "icao": "KPVU",
        "terminal": "terminal8",
        "time": "10:16:00"
      },
      "arrival": {
        "airport": "Los Angeles International",
        "timezone": "America/Los_Angeles",
        "iata": "LAX",
        "icao": "KLAX",
        "terminal": "5",
        "time": "11:08:00"
      },
      "airline": {
        "name": "Allegiant Air LLC",
        "callsign": "ALLEGIANT",
        "iata": "G4",
        "icao": "AAY"
      },
      "flight": {
        "number": "254"
      }
    },
    {
      "departure": {
        "airport": "Eglin AFB",
        "timezone": "America/Chicago",
        "iata": "VPS",
        "icao": "KVPS",
        "terminal": "terminal8",
        "time": "07:00:00"
      },
      "arrival": {
        "airport": "Mc Ghee Tyson",
        "timezone": "America/New_York",
        "iata": "TYS",
        "icao": "KTYS",
        "terminal": "terminal4",
        "time": "09:19:00"
      },
      "airline": {
        "name": "Allegiant Air LLC",
        "callsign": "ALLEGIANT",
        "iata": "G4",
        "icao": "AAY"
      },
      "flight": {
        "number": "1906"
      }
    },
    {
      "departure": {
        "airport": "Modlin",
        "timezone": "Europe/Warsaw",
        "iata": "WMI",
        "icao": "EPMO",
        "terminal": "terminal8",
        "time": "21:05:00"
      },
      "arrival": {
        "airport": "Bourgas",
        "timezone": "Europe/Sofia",
        "iata": "BOJ",
        "icao": "LBBG",
        "terminal": "terminal4",
        "time": "00:15:00"
      },
      "airline": {
        "name": "Ryanair Ltd.",
        "callsign": "RYANAIR",
        "iata": "FR",
        "icao": "RYR"
      },
      "flight": {
        "number": "3731"
      }
    },
    {
      "departure": {
        "airport": "Hopkins International",
        "timezone": "America/New_York",
        "iata": "CLE",
        "icao": "KCLE",
        "terminal": "terminal8",
        "time": "20:20:00"
      },
      "arrival": {
        "airport": "Keflavik International",
        "timezone": "Atlantic/Reykjavik",
        "iata": "KEF",
        "icao": "BIKF",
        "terminal": "terminal4",
        "time": "06:25:00"
      },
      "airline": {
        "name": "Icelandair",
        "callsign": "ICEAIR",
        "iata": "FI",
        "icao": "ICE"
      },
      "flight": {
        "number": "836"
      }
    },
    {
      "departure": {
        "airport": "Minneapolis - St. Paul International",
        "timezone": "America/Chicago",
        "iata": "MSP",
        "icao": "KMSP",
        "terminal": "2",
        "time": "19:30:00"
      },
      "arrival": {
        "airport": "Keflavik International",
        "timezone": "Atlantic/Reykjavik",
        "iata": "KEF",
        "icao": "BIKF",
        "terminal": "terminal4",
        "time": "06:40:00"
      },
      "airline": {
        "name": "Icelandair",
        "callsign": "ICEAIR",
        "iata": "FI",
        "icao": "ICE"
      },
      "flight": {
        "number": "658"
      }
    },
    {
      "departure": {
        "airport": "Philadelphia International",
        "timezone": "America/New_York",
        "iata": "PHL",
        "icao": "KPHL",
        "terminal": "E",
        "time": "time0"
      },
      "arrival": {
        "airport": "Trenton Mercer Airport",
        "timezone": "America/New_York",
        "iata": "TTN",
        "icao": "KTTN",
        "terminal": "terminal4",
        "time": "time6"
      },
      "airline": {
        "name": "Frontier Airlines, Inc.",
        "callsign": "FRONTIER FLIGHT",
        "iata": "F9",
        "icao": "FFT"
      },
      "flight": {
        "number": "890"
      }
    },
    {
      "departure": {
        "airport": "Cincinnati/Northern Kentucky",
        "timezone": "America/New_York",
        "iata": "CVG",
        "icao": "KCVG",
        "terminal": "3",
        "time": "time0"
      },
      "arrival": {
        "airport": "LaGuardia",
        "timezone": "America/New_York",
        "iata": "LGA",
        "icao": "KLGA",
        "terminal": "D",
        "time": "time6"
      },
      "airline": {
        "name": "Frontier Airlines, Inc.",
        "callsign": "FRONTIER FLIGHT",
        "iata": "F9",
        "icao": "FFT"
      },
      "flight": {
        "number": "7156"
      }
    },
    {
      "departure": {
        "airport": "Dallas/Fort Worth International",
        "timezone": "America/Chicago",
        "iata": "DFW",
        "icao": "KDFW",
        "terminal": "E",
        "time": "23:30:00"
      },
      "arrival": {
        "airport": "Philadelphia International",
        "timezone": "America/New_York",
        "iata": "PHL",
        "icao": "KPHL",
        "terminal": "E",
        "time": "04:00:00"
      },
      "airline": {
        "name": "Frontier Airlines, Inc.",
        "callsign": "FRONTIER FLIGHT",
        "iata": "F9",
        "icao": "FFT"
      },
      "flight": {
        "number": "1068"
      }
    },
    {
      "departure": {
        "airport": "Euroairport Swiss",
        "timezone": "Europe/Zurich",
        "iata": "BSL",
        "icao": "icao4",
        "terminal": "terminal8",
        "time": "10:40:00"
      },
      "arrival": {
        "airport": "Son Sant Joan Airport",
        "timezone": "Europe/Madrid",
        "iata": "PMI",
        "icao": "LEPA",
        "terminal": "terminal4",
        "time": "12:35:00"
      },
      "airline": {
        "name": "name2",
        "callsign": "callsign6",
        "iata": "E2",
        "icao": "EWE"
      },
      "flight": {
        "number": "6811"
      }
    },
    {
      "departure": {
        "airport": "Son Sant Joan Airport",
        "timezone": "Europe/Madrid",
        "iata": "PMI",
        "icao": "LEPA",
        "terminal": "terminal8",
        "time": "08:00:00"
      },
      "arrival": {
        "airport": "Euroairport Swiss",
        "timezone": "Europe/Zurich",
        "iata": "BSL",
        "icao": "icao0",
        "terminal": "terminal4",
        "time": "10:00:00"
      },
      "airline": {
        "name": "name2",
        "callsign": "callsign6",
        "iata": "E2",
        "icao": "EWE"
      },
      "flight": {
        "number": "6810"
      }
    },
    {
      "departure": {
        "airport": "Westerland - Sylt",
        "timezone": "Europe/Berlin",
        "iata": "GWT",
        "icao": "EDXW",
        "terminal": "terminal8",
        "time": "08:35:00"
      },
      "arrival": {
        "airport": "Cologne/bonn",
        "timezone": "Europe/Berlin",
        "iata": "CGN",
        "icao": "EDDK",
        "terminal": "1",
        "time": "09:45:00"
      },
      "airline": {
        "name": "Eurowings",
        "callsign": "EUROWINGS",
        "iata": "EW",
        "icao": "EWG"
      },
      "flight": {
        "number": "69"
      }
    },
    {
      "departure": {
        "airport": "Son Sant Joan Airport",
        "timezone": "Europe/Madrid",
        "iata": "PMI",
        "icao": "LEPA",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Cologne/bonn",
        "timezone": "Europe/Berlin",
        "iata": "CGN",
        "icao": "EDDK",
        "terminal": "1",
        "time": "time6"
      },
      "airline": {
        "name": "Eurowings",
        "callsign": "EUROWINGS",
        "iata": "EW",
        "icao": "EWG"
      },
      "flight": {
        "number": "595"
      }
    },
    {
      "departure": {
        "airport": "Stuttgart Echterdingen",
        "timezone": "Europe/Berlin",
        "iata": "STR",
        "icao": "EDDS",
        "terminal": "1",
        "time": "10:25:00"
      },
      "arrival": {
        "airport": "Zakinthos International Airport",
        "timezone": "Europe/Athens",
        "iata": "ZTH",
        "icao": "LGZA",
        "terminal": "terminal4",
        "time": "13:55:00"
      },
      "airline": {
        "name": "Eurowings",
        "callsign": "EUROWINGS",
        "iata": "EW",
        "icao": "EWG"
      },
      "flight": {
        "number": "2814"
      }
    },
    {
      "departure": {
        "airport": "Franz Josef Strauss",
        "timezone": "Europe/Berlin",
        "iata": "MUC",
        "icao": "EDDM",
        "terminal": "2",
        "time": "11:10:00"
      },
      "arrival": {
        "airport": "Sarajevo",
        "timezone": "Europe/Sarajevo",
        "iata": "SJJ",
        "icao": "LQSA",
        "terminal": "terminal4",
        "time": "12:30:00"
      },
      "airline": {
        "name": "AIR DOLOMITI S.p.A. LINEE AEREE REGIONALI EUROPEE",
        "callsign": "DOLOMITI",
        "iata": "EN",
        "icao": "DLA"
      },
      "flight": {
        "number": "1730"
      }
    },
    {
      "departure": {
        "airport": "Makung",
        "timezone": "Asia/Taipei",
        "iata": "MZG",
        "icao": "RCQC",
        "terminal": "terminal8",
        "time": "08:05:00"
      },
      "arrival": {
        "airport": "Taipei Songshan (Sung Shan)",
        "timezone": "Asia/Taipei",
        "iata": "TSA",
        "icao": "RCSS",
        "terminal": "T1",
        "time": "08:50:00"
      },
      "airline": {
        "name": "FAR EASTERN AIR TRANSPORT CORP.",
        "callsign": "FAR EASTERN",
        "iata": "FE",
        "icao": "FEA"
      },
      "flight": {
        "number": "6022"
      }
    },
    {
      "departure": {
        "airport": "Zurich",
        "timezone": "Europe/Zurich",
        "iata": "ZRH",
        "icao": "LSZH",
        "terminal": "2",
        "time": "12:00:00"
      },
      "arrival": {
        "airport": "San Diego International Airport",
        "timezone": "America/Los_Angeles",
        "iata": "SAN",
        "icao": "KSAN",
        "terminal": "2",
        "time": "15:25:00"
      },
      "airline": {
        "name": "Edelweiss Air",
        "callsign": "EDELWEISS",
        "iata": "WK",
        "icao": "EDW"
      },
      "flight": {
        "number": "18"
      }
    },
    {
      "departure": {
        "airport": "John F Kennedy International",
        "timezone": "America/New_York",
        "iata": "JFK",
        "icao": "KJFK",
        "terminal": "terminal8",
        "time": "time0"
      },
      "arrival": {
        "airport": "Gatwick",
        "timezone": "Europe/London",
        "iata": "LGW",
        "icao": "EGKK",
        "terminal": "S",
        "time": "time6"
      },
      "airline": {
        "name": "Norwegian Air UK ltd",
        "callsign": "NORWORLD",
        "iata": "DI",
        "icao": "NRS"
      },
      "flight": {
        "number": "7998"
      }
    },
    {
      "departure": {
        "airport": "Louis Armstrong New Orléans International Airport",
        "timezone": "America/Chicago",
        "iata": "MSY",
        "icao": "KMSY",
        "terminal": "terminal8",
        "time": "18:25:00"
      },
      "arrival": {
        "airport": "Frankfurt International Airport",
        "timezone": "Europe/Berlin",
        "iata": "FRA",
        "icao": "EDDF",
        "terminal": "1",
        "time": "11:10:00"
      },
      "airline": {
        "name": "Condor",
        "callsign": "CONDOR",
        "iata": "DE",
        "icao": "CFG"
      },
      "flight": {
        "number": "2067"
      }
    },
    {
      "departure": {
        "airport": "Frankfurt International Airport",
        "timezone": "Europe/Berlin",
        "iata": "FRA",
        "icao": "EDDF",
        "terminal": "1",
        "time": "11:40:00"
      },
      "arrival": {
        "airport": "Sky Harbor International",
        "timezone": "America/Phoenix",
        "iata": "PHX",
        "icao": "KPHX",
        "terminal": "4",
        "time": "14:45:00"
      },
      "airline": {
        "name": "Condor",
        "callsign": "CONDOR",
        "iata": "DE",
        "icao": "CFG"
      },
      "flight": {
        "number": "2026"
      }
    }
  ]
}
```

