# Sample Description
POST Request for ApexClassMember

## PATH
```
/services/data/v39.0/tooling/sobjects/ApexClassMember/
```
## Supported Versions
39.0

## request
```json
{
  "MetadataContainerId": "{ID}",
  "FullName": "UniqueName_ACM",
  "Body": "public with sharing class ApiatoTestClass {}",
  "Metadata": {
    "apiVersion": "39", "status": "Active"
  }
}
```
## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
