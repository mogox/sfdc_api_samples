# Sample Description
Simple request of an OwnerChangeOptionInfo Get

## PATH
```
/services/data/{version}/tooling/query/?q=SELECT Id, Name, Label, IsEditable, DefaultValue, EntityDefinition.QualifiedApiName FROM OwnerChangeOptionInfo WHERE EntityDefinition.QualifiedApiName='Account'
```
## Supported Versions
38.0, 39.0, 40.0, 41.0, 42.0, 43.0

## request
 ```json
 { }

```
## response
```json
{
  "size": 1,
  "totalSize": 1,
  "done": true,
  "queryLocator": null,
  "entityTypeName": "OwnerChangeOptionInfo",
  "records": [
    {
      "attributes": {
        "type": "OwnerChangeOptionInfo",
        "url": "/services/data/{version}/tooling/sobjects/OwnerChangeOptionInfo/Account.TransferOthersOpenOpportunities"
      },
      "Id": "000000000000000AAA",
      "Name": "TransferOthersOpenOpportunities",
      "Label": "Transfer open opportunities not owned by you",
      "IsEditable": true,
      "DefaultValue": false,
      "EntityDefinition": {
        "attributes": {
          "type": "EntityDefinition",
          "url": "/services/data/{version}/tooling/sobjects/EntityDefinition/Account"
        },
        "QualifiedApiName": "Account"
      }
    }
  ]
}
```
