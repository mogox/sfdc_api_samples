# Sample Description
Simple request of an FieldDefinition record

## PATH
```
/services/data/{version}/tooling/query/?q=Select QualifiedApiName, RelationshipName, ReferenceTo, ReferenceTargetField from FieldDefinition where EntityDefinition.QualifiedApiName = 'Contact' and QualifiedApiName = 'AccountId'
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
  "entityTypeName": "FieldDefinition",
  "queryLocator": null,
  "records": [
    {
      "QualifiedApiName": "AccountId",
      "ReferenceTargetField": null,
      "ReferenceTo": {
        "referenceTo": [
          "Account"
        ]
      },
      "RelationshipName": "Account",
      "attributes": {
        "type": "FieldDefinition",
        "url": "/services/data/{version}/tooling/sobjects/FieldDefinition/Contact.Account"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
