# Sample Description
Simple request of an ApexClassMember record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, IsDeleted, MetadataContainerId, Body, SymbolTable, Metadata, FullName from ApexClassMember where Id = '{Id}'
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
  "entityTypeName": "ApexClassMember",
  "queryLocator": null,
  "records": [
    {
      "Body": "public with sharing class ApiatoTestClass {}",
      "FullName": "UniqueName_ACM",
      "Id": "{ID}",
      "IsDeleted": false,
      "Metadata": {
        "apiVersion": 39,
        "packageVersions": null,
        "status": "Active",
        "urls": null
      },
      "MetadataContainerId": "{MetadataContainerId}",
      "SymbolTable": null,
      "attributes": {
        "type": "ApexClassMember",
        "url": "/services/data/v39.0/tooling/sobjects/ApexClassMember/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
