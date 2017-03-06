# Sample Description
Simple request of an CustomObject record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, DeveloperName, NamespacePrefix From CustomObject
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
  "entityTypeName": "CustomObject",
  "queryLocator": null,
  "records": [
    {
      "DeveloperName": "Apiato_CustomObject",
      "Id": "{ID}",
      "NamespacePrefix": null,
      "attributes": {
        "type": "CustomObject",
        "url": "/services/data/v39.0/tooling/sobjects/CustomObject/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```