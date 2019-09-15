# Cheap-Flights-on-a-go
meta search of cheap flights
 {
  "meta": {
    "count": 3,
    "links": {
      "self": "https://test.api.amadeus.com/v2/shopping/flight-offers?originLocationCode=SYD&destinationLocationCode=BKK&departureDate=2020-01-01&returnDate=2020-01-05&adults=2&includedAirlineCodes=TG&max=3"
    }
  },
  "data": [
    {
      "type": "flight-offer",
      "id": "1",
      "source": "GDS",
      "instantTicketingRequired": false,
      "nonHomogeneous": false,
      "oneWay": false,
      "lastTicketingDate": "2020-01-01",
      "numberOfBookableSeats": 3,
      "itineraries": [
        {
          "duration": "PT9H25M",
          "segments": [
            {
              "departure": {
                "iataCode": "SYD",
                "terminal": "1",
                "at": "2020-01-01T10:00:00"
              },
              "arrival": {
                "iataCode": "BKK",
                "at": "2020-01-01T15:25:00"
              },
              "carrierCode": "TG",
              "number": "476",
              "aircraft": {
                "code": "747"
              },
              "operating": {
                "carrierCode": "TG"
              },
              "duration": "PT9H25M",
              "id": "1",
              "numberOfStops": 0,
              "blacklistedInEU": false
            }
          ]
        },
        {
          "duration": "PT9H20M",
          "segments": [
            {
              "departure": {
                "iataCode": "BKK",
                "at": "2020-01-05T17:50:00"
              },
              "arrival": {
                "iataCode": "SYD",
                "terminal": "1",
                "at": "2020-01-06T07:10:00"
              },
              "carrierCode": "TG",
              "number": "475",
              "aircraft": {
                "code": "747"
              },
              "operating": {
                "carrierCode": "TG"
              },
              "duration": "PT9H20M",
              "id": "4",
              "numberOfStops": 0,
              "blacklistedInEU": false
            }
          ]
        }
      ],
      "price": {
        "currency": "EUR",
        "total": "2326.84",
        "base": "2128.00",
        "fees": [
          {
            "amount": "0.00",
            "type": "SUPPLIER"
          },
          {
            "amount": "0.00",
            "type": "TICKETING"
          }
        ]
      },
      "pricingOptions": {
        "fareType": [
          "PUBLISHED"
        ],
        "includedCheckedBagsOnly": true
      },
      "validatingAirlineCodes": [
        "TG"
      ],
      "travelerPricings": [
        {
          "travelerId": "1",
          "fareOption": "STANDARD",
          "travelerType": "ADULT",
          "price": {
            "currency": "EUR",
            "total": "1163.42",
            "base": "1064.00"
          },
          "fareDetailsBySegment": [
            {
              "segmentId": "1",
              "cabin": "ECONOMY",
              "fareBasis": "T1YRTTG",
              "class": "T",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "4",
              "cabin": "ECONOMY",
              "fareBasis": "H1YRTTG",
              "class": "H",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            }
          ]
        },
        {
          "travelerId": "2",
          "fareOption": "STANDARD",
          "travelerType": "ADULT",
          "price": {
            "currency": "EUR",
            "total": "1163.42",
            "base": "1064.00"
          },
          "fareDetailsBySegment": [
            {
              "segmentId": "1",
              "cabin": "ECONOMY",
              "fareBasis": "T1YRTTG",
              "class": "T",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "4",
              "cabin": "ECONOMY",
              "fareBasis": "H1YRTTG",
              "class": "H",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            }
          ]
        }
      ]
    },
    {
      "type": "flight-offer",
      "id": "2",
      "source": "GDS",
      "instantTicketingRequired": false,
      "nonHomogeneous": false,
      "oneWay": false,
      "lastTicketingDate": "2019-09-29",
      "numberOfBookableSeats": 9,
      "itineraries": [
        {
          "duration": "PT20H35M",
          "segments": [
            {
              "departure": {
                "iataCode": "SYD",
                "terminal": "1",
                "at": "2020-01-01T17:00:00"
              },
              "arrival": {
                "iataCode": "SIN",
                "terminal": "1",
                "at": "2020-01-01T22:05:00"
              },
              "carrierCode": "QF",
              "number": "1",
              "aircraft": {
                "code": "388"
              },
              "operating": {
                "carrierCode": "QF"
              },
              "duration": "PT8H5M",
              "id": "2",
              "numberOfStops": 0,
              "blacklistedInEU": false
            },
            {
              "departure": {
                "iataCode": "SIN",
                "terminal": "1",
                "at": "2020-01-02T08:15:00"
              },
              "arrival": {
                "iataCode": "BKK",
                "at": "2020-01-02T09:35:00"
              },
              "carrierCode": "TG",
              "number": "402",
              "aircraft": {
                "code": "773"
              },
              "operating": {
                "carrierCode": "TG"
              },
              "duration": "PT2H20M",
              "id": "3",
              "numberOfStops": 0,
              "blacklistedInEU": false
            }
          ]
        },
        {
          "duration": "PT12H25M",
          "segments": [
            {
              "departure": {
                "iataCode": "BKK",
                "at": "2020-01-05T13:50:00"
              },
              "arrival": {
                "iataCode": "SIN",
                "terminal": "1",
                "at": "2020-01-05T17:10:00"
              },
              "carrierCode": "TG",
              "number": "407",
              "aircraft": {
                "code": "777"
              },
              "operating": {
                "carrierCode": "TG"
              },
              "duration": "PT2H20M",
              "id": "5",
              "numberOfStops": 0,
              "blacklistedInEU": false
            },
            {
              "departure": {
                "iataCode": "SIN",
                "terminal": "1",
                "at": "2020-01-05T19:15:00"
              },
              "arrival": {
                "iataCode": "SYD",
                "terminal": "1",
                "at": "2020-01-06T06:15:00"
              },
              "carrierCode": "QF",
              "number": "2",
              "aircraft": {
                "code": "388"
              },
              "operating": {
                "carrierCode": "QF"
              },
              "duration": "PT8H",
              "id": "6",
              "numberOfStops": 0,
              "blacklistedInEU": false
            }
          ]
        }
      ],
      "price": {
        "currency": "EUR",
        "total": "3016.76",
        "base": "2748.00",
        "fees": [
          {
            "amount": "0.00",
            "type": "SUPPLIER"
          },
          {
            "amount": "0.00",
            "type": "TICKETING"
          }
        ]
      },
      "pricingOptions": {
        "fareType": [
          "PUBLISHED"
        ],
        "includedCheckedBagsOnly": true
      },
      "validatingAirlineCodes": [
        "QF"
      ],
      "travelerPricings": [
        {
          "travelerId": "1",
          "fareOption": "STANDARD",
          "travelerType": "ADULT",
          "price": {
            "currency": "EUR",
            "total": "1508.38",
            "base": "1374.00"
          },
          "fareDetailsBySegment": [
            {
              "segmentId": "2",
              "cabin": "ECONOMY",
              "fareBasis": "KSATH",
              "class": "K",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "3",
              "cabin": "ECONOMY",
              "fareBasis": "KSATH",
              "class": "W",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "5",
              "cabin": "ECONOMY",
              "fareBasis": "BFATH",
              "class": "W",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "6",
              "cabin": "ECONOMY",
              "fareBasis": "BFATH",
              "class": "B",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            }
          ]
        },
        {
          "travelerId": "2",
          "fareOption": "STANDARD",
          "travelerType": "ADULT",
          "price": {
            "currency": "EUR",
            "total": "1508.38",
            "base": "1374.00"
          },
          "fareDetailsBySegment": [
            {
              "segmentId": "2",
              "cabin": "ECONOMY",
              "fareBasis": "KSATH",
              "class": "K",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "3",
              "cabin": "ECONOMY",
              "fareBasis": "KSATH",
              "class": "W",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "5",
              "cabin": "ECONOMY",
              "fareBasis": "BFATH",
              "class": "W",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "6",
              "cabin": "ECONOMY",
              "fareBasis": "BFATH",
              "class": "B",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            }
          ]
        }
      ]
    },
    {
      "type": "flight-offer",
      "id": "3",
      "source": "GDS",
      "instantTicketingRequired": false,
      "nonHomogeneous": false,
      "oneWay": false,
      "lastTicketingDate": "2019-09-29",
      "numberOfBookableSeats": 9,
      "itineraries": [
        {
          "duration": "PT20H35M",
          "segments": [
            {
              "departure": {
                "iataCode": "SYD",
                "terminal": "1",
                "at": "2020-01-01T17:00:00"
              },
              "arrival": {
                "iataCode": "SIN",
                "terminal": "1",
                "at": "2020-01-01T22:05:00"
              },
              "carrierCode": "QF",
              "number": "1",
              "aircraft": {
                "code": "388"
              },
              "operating": {
                "carrierCode": "QF"
              },
              "duration": "PT8H5M",
              "id": "2",
              "numberOfStops": 0,
              "blacklistedInEU": false
            },
            {
              "departure": {
                "iataCode": "SIN",
                "terminal": "1",
                "at": "2020-01-02T08:15:00"
              },
              "arrival": {
                "iataCode": "BKK",
                "at": "2020-01-02T09:35:00"
              },
              "carrierCode": "TG",
              "number": "402",
              "aircraft": {
                "code": "773"
              },
              "operating": {
                "carrierCode": "TG"
              },
              "duration": "PT2H20M",
              "id": "3",
              "numberOfStops": 0,
              "blacklistedInEU": false
            }
          ]
        },
        {
          "duration": "PT14H45M",
          "segments": [
            {
              "departure": {
                "iataCode": "BKK",
                "at": "2020-01-05T11:30:00"
              },
              "arrival": {
                "iataCode": "SIN",
                "terminal": "1",
                "at": "2020-01-05T14:50:00"
              },
              "carrierCode": "TG",
              "number": "413",
              "aircraft": {
                "code": "773"
              },
              "operating": {
                "carrierCode": "TG"
              },
              "duration": "PT2H20M",
              "id": "7",
              "numberOfStops": 0,
              "blacklistedInEU": false
            },
            {
              "departure": {
                "iataCode": "SIN",
                "terminal": "1",
                "at": "2020-01-05T19:15:00"
              },
              "arrival": {
                "iataCode": "SYD",
                "terminal": "1",
                "at": "2020-01-06T06:15:00"
              },
              "carrierCode": "QF",
              "number": "2",
              "aircraft": {
                "code": "388"
              },
              "operating": {
                "carrierCode": "QF"
              },
              "duration": "PT8H",
              "id": "8",
              "numberOfStops": 0,
              "blacklistedInEU": false
            }
          ]
        }
      ],
      "price": {
        "currency": "EUR",
        "total": "3016.76",
        "base": "2748.00",
        "fees": [
          {
            "amount": "0.00",
            "type": "SUPPLIER"
          },
          {
            "amount": "0.00",
            "type": "TICKETING"
          }
        ]
      },
      "pricingOptions": {
        "fareType": [
          "PUBLISHED"
        ],
        "includedCheckedBagsOnly": true
      },
      "validatingAirlineCodes": [
        "QF"
      ],
      "travelerPricings": [
        {
          "travelerId": "1",
          "fareOption": "STANDARD",
          "travelerType": "ADULT",
          "price": {
            "currency": "EUR",
            "total": "1508.38",
            "base": "1374.00"
          },
          "fareDetailsBySegment": [
            {
              "segmentId": "2",
              "cabin": "ECONOMY",
              "fareBasis": "KSATH",
              "class": "K",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "3",
              "cabin": "ECONOMY",
              "fareBasis": "KSATH",
              "class": "W",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "7",
              "cabin": "ECONOMY",
              "fareBasis": "BFATH",
              "class": "W",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "8",
              "cabin": "ECONOMY",
              "fareBasis": "BFATH",
              "class": "B",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            }
          ]
        },
        {
          "travelerId": "2",
          "fareOption": "STANDARD",
          "travelerType": "ADULT",
          "price": {
            "currency": "EUR",
            "total": "1508.38",
            "base": "1374.00"
          },
          "fareDetailsBySegment": [
            {
              "segmentId": "2",
              "cabin": "ECONOMY",
              "fareBasis": "KSATH",
              "class": "K",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "3",
              "cabin": "ECONOMY",
              "fareBasis": "KSATH",
              "class": "W",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "7",
              "cabin": "ECONOMY",
              "fareBasis": "BFATH",
              "class": "W",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            },
            {
              "segmentId": "8",
              "cabin": "ECONOMY",
              "fareBasis": "BFATH",
              "class": "B",
              "includedCheckedBags": {
                "weight": 30,
                "weightUnit": "KG"
              }
            }
          ]
        }
      ]
    }
  ],
  "dictionaries": {
    "locations": {
      "BKK": {
        "cityCode": "BKK",
        "countryCode": "TH"
      },
      "SIN": {
        "cityCode": "SIN",
        "countryCode": "SG"
      },
      "SYD": {
        "cityCode": "SYD",
        "countryCode": "AU"
      }
    }
  }
}
