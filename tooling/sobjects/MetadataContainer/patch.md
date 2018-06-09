# Sample Description
POST Request for MetadataContainer

## PATH
```
/services/data/{version}/tooling/sobjects/MetadataContainer/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "Name" : "MDContainer_NewUniqueName"
}
```
## response
```json
{
  "CreatedById": "{User ID}",
  "CreatedDate": "2016-09-17T00:43:41.000+0000",
  "Id": "{ID}",
  "IsDeleted": false,
  "LastModifiedById": "{User ID}",
  "LastModifiedDate": "2017-03-08T01:07:16.000+0000",
  "Name": "MDContainer_NewUniqueName",
  "SystemModstamp": "2017-03-08T01:07:16.000+0000",
  "attributes": {
    "type": "MetadataContainer",
    "url": "/services/data/{version}/tooling/sobjects/MetadataContainer/{ID}"
  }
}
```
