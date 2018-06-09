# Sample Description
Simple request of an ApexClass record

## PATH
```
/services/data/{version}/query/?q=Select Id, NamespacePrefix, Name, ApiVersion, Status, IsValid, BodyCrc, Body, LengthWithoutComments from ApexClass
```
## Supported Versions
38.0, 39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
 { }
```

## response
```json
{
  "totalSize": 1,
  "done": true,
  "records": [
    {
      "attributes": {
        "type": "ApexClass",
        "url": "/services/data/{version}/sobjects/ApexClass/{ID}"
      },
      "Id": "{ID}",
      "NamespacePrefix": null,
      "Name": "SutroSample",
      "ApiVersion": 41,
      "Status": "Active",
      "IsValid": false,
      "BodyCrc": 1521804554,
      "Body": "public with sharing class SutroSample {}",
      "LengthWithoutComments": 45
    }
  ]
}
```
