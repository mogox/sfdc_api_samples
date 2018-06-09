# Sample Description
Simple request of an MetadataContainer record

## PATH
```
/services/data/{version}/tooling/query/?q=select Id, Name, CreatedDate, CreatedById, IsDeleted, LastModifiedDate, LastModifiedById, SystemModstamp from MetadataContainer where Id = '{ID}'
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
  "entityTypeName": "MetadataContainer",
  "queryLocator": null,
  "records": [
    {
      "CreatedDate": "2016-09-17T00:43:41.000+0000",
      "Id": "{ID}",
      "Name": "MDContainer_RandomName",
      "attributes": {
        "type": "MetadataContainer",
        "url": "/services/data/{version}/tooling/sobjects/MetadataContainer/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
