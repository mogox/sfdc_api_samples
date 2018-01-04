# Sample Description
Simple request of an ApexClass record

## PATH
```
/services/data/v41.0/query/?q=Select Id, NamespacePrefix, Name, ApiVersion, Status, IsValid, BodyCrc, Body, LengthWithoutComments from ApexClass
```
## Supported Versions
38.0, 39.0, 40.0, 41.0

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
        "url": "/services/data/v41.0/sobjects/ApexClass/{ID}"
      },
      "Id": "{ID}",
      "NamespacePrefix": null,
      "Name": "ApiatoSample",
      "ApiVersion": 41,
      "Status": "Active",
      "IsValid": false,
      "BodyCrc": 1521804554,
      "Body": "public with sharing class ApiatoSample {}",
      "LengthWithoutComments": 45
    }
  ]
}
```
