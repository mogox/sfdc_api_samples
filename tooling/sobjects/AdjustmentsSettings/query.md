# Sample Description
Simple request of an AdjustmentsSettings record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, DurableId, IsAdjustmentsEnabled, IsOwnerAdjustmentsEnabled from AdjustmentsSettings where DurableId = '{DurableId}'
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
  "entityTypeName": "AdjustmentsSettings",
  "queryLocator": null,
  "records": [
    {
      "DurableId": "{DurableId}",
      "Id": "000000000000000AAA",
      "IsAdjustmentsEnabled": false,
      "IsOwnerAdjustmentsEnabled": false,
      "attributes": {
        "type": "AdjustmentsSettings",
        "url": "/services/data/v39.0/tooling/sobjects/AdjustmentsSettings/{DurableId}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
