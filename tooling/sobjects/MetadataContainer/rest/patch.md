# Sample Description
POST Request for MetadataContainer

## PATH
```
/services/data/v39.0/tooling/sobjects/MetadataContainer/{ID}
```
## Supported Versions
37.0

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
    "url": "/services/data/v39.0/tooling/sobjects/MetadataContainer/{ID}"
  }
}
```
