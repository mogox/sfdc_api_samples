# Sample Description
Simple request of an AddressSettings record

## PATH
```
/services/data/{version}/tooling/sobjects/AddressSettings/{DurableId}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
 {}
```

## response
```json
{
  "CountriesAndStatesId": "{CountriesAndStatesId}",
  "DurableId": "{DurableId}",
  "FullName": "Address",
  "Id": "000000000000000AAA",
  "Metadata": {
    "countriesAndStates": {
      "countries": [
        {
          "active": true,
          "integrationValue": "Andorra",
          "isoCode": "AD",
          "label": "Andorra",
          "orgDefault": false,
          "standard": true,
          "states": [],
          "visible": true
        },
        {
          "active": true,
          "integrationValue": "United States",
          "isoCode": "US",
          "label": "United States",
          "orgDefault": false,
          "standard": true,
          "states": [
            {
              "active": false,
              "integrationValue": "Armed Forces Americas",
              "isoCode": "AA",
              "label": "Armed Forces Americas",
              "standard": true,
              "visible": false
            },
            {
              "active": true,
              "integrationValue": "California",
              "isoCode": "CA",
              "label": "California",
              "standard": true,
              "visible": true
            }
          ]
        }
      ]
    },
    "urls": null
  },
  "attributes": {
    "type": "AddressSettings",
    "url": "/services/data/{version}/tooling/sobjects/AddressSettings/{DurableId}"
  }
}
```
