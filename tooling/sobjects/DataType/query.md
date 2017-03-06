# Sample Description
Simple request of an DataType record

## PATH
```
/services/data/v39.0/tooling/query/?q=select Id, DurableId from DataType
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
  "entityTypeName": "DataType",
  "queryLocator": null,
  "records": [
    {
      "DurableId": "string",
      "Id": "{ID}",
      "attributes": {
        "type": "DataType",
        "url": "/services/data/v39.0/tooling/sobjects/DataType/string"
      }
    },
    {
      "DurableId": "boolean",
      "Id": "{ID}",
      "attributes": {
        "type": "DataType",
        "url": "/services/data/v39.0/tooling/sobjects/DataType/boolean"
      }
    },
    {
      "DurableId": "integer",
      "Id": "{ID}",
      "attributes": {
        "type": "DataType",
        "url": "/services/data/v39.0/tooling/sobjects/DataType/integer"
      }
    }
  ],
  "size": 661,
  "totalSize": 661
}
```