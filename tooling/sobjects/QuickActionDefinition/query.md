# Sample Description
Simple request of an QuickActionDefinition record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, DeveloperName, Label, Description, Type, NamespacePrefix, EntityDefinition.Label from QuickActionDefinition where DeveloperName='NewAccount'
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
  "entityTypeName": "QuickActionDefinition",
  "queryLocator": null,
  "records": [
    {
      "Description": null,
      "DeveloperName": "NewAccount",
      "EntityDefinition": null,
      "Id": "{ID}",
      "Label": "New Account",
      "NamespacePrefix": null,
      "Type": "Create",
      "attributes": {
        "type": "QuickActionDefinition",
        "url": "/services/data/{version}/tooling/sobjects/QuickActionDefinition/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
