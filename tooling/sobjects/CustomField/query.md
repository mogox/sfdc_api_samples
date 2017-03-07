# Sample Description
Simple request of an CustomField record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, DeveloperName, NamespacePrefix, TableEnumOrId From CustomField Where TableEnumOrId = '{Object Name}' and DeveloperName = '{Field DeveloperName}'
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
  "entityTypeName": "CustomField",
  "queryLocator": null,
  "records": [
    {
      "DeveloperName": "{Field DeveloperName}",
      "Id": "{ID}",
      "NamespacePrefix": null,
      "TableEnumOrId": "{Object Name}",
      "attributes": {
        "type": "CustomField",
        "url": "/services/data/v39.0/tooling/sobjects/CustomField/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```