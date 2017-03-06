# Sample Description
Simple request of an Publisher record

## PATH
```
/services/data/v39.0/tooling/query/?q=select durableId, Id, Name from Publisher
```
## Supported Versions
39.0

## request
 ```json
 { }
```

## response
```json
{
  "done": true,
  "entityTypeName": "Publisher",
  "queryLocator": null,
  "records": [
    {
      "DurableId": "System",
      "Id": "{ID}",
      "Name": "System",
      "attributes": {
        "type": "Publisher",
        "url": "/services/data/v39.0/tooling/sobjects/Publisher/System"
      }
    }
  ],
  "size": 44,
  "totalSize": 44
}
```