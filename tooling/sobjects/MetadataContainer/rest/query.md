# Sample Description
Simple request of an MetadataContainer record

## PATH
```
/services/data/v39.0/tooling/query/?q=select Id, Name, CreatedDate  from MetadataContainer
```
## Supported Versions
39.0

## request
 ```json
{}
```

## response
```json
{
  "done": true,
  "entityTypeName": "MetadataContainer",
  "queryLocator": null,
  "records": [
    {
      "CreatedDate": "2016-09-17T00:43:41.000+0000",
      "Id": "{ID}",
      "Name": "MDContainer_RandomName",
      "attributes": {
        "type": "MetadataContainer",
        "url": "/services/data/v39.0/tooling/sobjects/MetadataContainer/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```