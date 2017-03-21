# Sample Description
Simple request of an EntityDefinition record

## PATH
```
/services/data/v39.0/tooling/query/?q=SELECT DurableId, QualifiedApiName, RecordTypesSupported from EntityDefinition where QualifiedApiName = 'Campaign'
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
  "entityTypeName": "EntityDefinition",
  "queryLocator": null,
  "records": [
    {
      "DurableId": "Campaign",
      "QualifiedApiName": "Campaign",
      "RecordTypesSupported": {
        "recordTypeInfos": [
          {
            "available": true,
            "defaultRecordTypeMapping": true,
            "master": true,
            "name": "Master",
            "recordTypeId": "{RecordTypeID}"
          }
        ]
      },
      "attributes": {
        "type": "EntityDefinition",
        "url": "/services/data/v39.0/tooling/sobjects/EntityDefinition/Campaign"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
