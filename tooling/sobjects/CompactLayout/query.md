# Sample Description
Simple request of an CompactLayout record

## PATH
```
/services/data/{version}/tooling/query/?q=SELECT Label, DeveloperName, EntityDefinition.Label, EntityDefinition.DurableId FROM CompactLayoutInfo where EntityDefinition.DurableId = 'Account'
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
  "entityTypeName": "CompactLayoutInfo",
  "queryLocator": null,
  "records": [
    {
      "DeveloperName": "SYSTEM",
      "EntityDefinition": {
        "DurableId": "Account",
        "Label": "Account",
        "attributes": {
          "type": "EntityDefinition",
          "url": "/services/data/{version}/tooling/sobjects/EntityDefinition/Account"
        }
      },
      "Label": "System Default",
      "attributes": {
        "type": "CompactLayoutInfo",
        "url": "/services/data/{version}/tooling/sobjects/CompactLayoutInfo/Account.SYSTEM"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
