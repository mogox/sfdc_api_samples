# Sample Description
Simple request of an MetadataContainer Get

## PATH
```
/services/data/{version}/tooling/sobjects/MetadataContainer/{ID}
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
  "CreatedById": "{User ID}",
  "CreatedDate": "2017-01-11T07:26:16.000+0000",
  "Id": "{ID}",
  "IsDeleted": false,
  "LastModifiedById": "{User ID}",
  "LastModifiedDate": "2017-01-11T07:26:16.000+0000",
  "Name": "MDContainer_UniqueName",
  "SystemModstamp": "2017-01-11T07:26:16.000+0000",
  "attributes": {
    "type": "MetadataContainer",
    "url": "/services/data/{version}/tooling/sobjects/MetadataContainer/{ID}"
  }
}
```
