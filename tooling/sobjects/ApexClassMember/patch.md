# Sample Description
POST Request for ApexClassMember

## PATH
```
/services/data/{version}/tooling/sobjects/ApexClassMember/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "FullName": "UniqueName_ACM",
  "Body": "public with sharing class ApiatoTestClass_Patch {}",
  "Metadata": {
    "apiVersion": "39", "status": "Active"
  }
}
```
## response
```json
{}
```
