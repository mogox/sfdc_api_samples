# Sample Description
Simple request of an AddressSettings record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, DurableId, CountriesAndStatesId, Metadata, Fullname from AddressSettings where DurableId = '{DurableId}'
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
  "done": true,
  "entityTypeName": "AddressSettings",
  "queryLocator": null,
  "records": [
    {
      "CountriesAndStatesId": "{CountriesAndStatesId}",
      "DurableId": "{DurableId}",
      "Id": "000000000000000AAA",
      "attributes": {
        "type": "AddressSettings",
        "url": "/services/data/{version}/tooling/sobjects/AddressSettings/{DurableId}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
