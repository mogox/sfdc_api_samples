# Sample Description
Simple request of an EntityParticle record

## PATH
```
/services/data/v39.0/tooling/query/?q=select DataType, FieldDefinition.QualifiedApiName from EntityParticle where EntityDefinition.QualifiedApiName = 'Account'
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
  "entityTypeName": "EntityParticle",
  "queryLocator": null,
  "records": [
    {
      "DataType": "id",
      "FieldDefinition": {
        "QualifiedApiName": "Id",
        "attributes": {
          "type": "FieldDefinition",
          "url": "/services/data/v39.0/tooling/sobjects/FieldDefinition/Account.Id"
        }
      },
      "attributes": {
        "type": "EntityParticle",
        "url": "/services/data/v39.0/tooling/sobjects/EntityParticle/Account.Id"
      }
    },
    {
      "DataType": "string",
      "FieldDefinition": {
        "QualifiedApiName": "Name",
        "attributes": {
          "type": "FieldDefinition",
          "url": "/services/data/v39.0/tooling/sobjects/FieldDefinition/Account.Name"
        }
      },
      "attributes": {
        "type": "EntityParticle",
        "url": "/services/data/v39.0/tooling/sobjects/EntityParticle/Account.Name.TextName"
      }
    },
    ...
  ],
  "size": 74,
  "totalSize": 74
}
```
