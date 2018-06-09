# Sample Description
Simple request of an DataType record

## PATH
```
/services/data/{version}/tooling/query/?q=select Id, DurableId from DataType
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
  "entityTypeName": "DataType",
  "queryLocator": null,
  "records": [
    {
      "DurableId": "string",
      "Id": "{ID}",
      "attributes": {
        "type": "DataType",
        "url": "/services/data/{version}/tooling/sobjects/DataType/string"
      }
    },
    {
      "DurableId": "boolean",
      "Id": "{ID}",
      "attributes": {
        "type": "DataType",
        "url": "/services/data/{version}/tooling/sobjects/DataType/boolean"
      }
    },
    {
      "DurableId": "integer",
      "Id": "{ID}",
      "attributes": {
        "type": "DataType",
        "url": "/services/data/{version}/tooling/sobjects/DataType/integer"
      }
    }
  ],
  "size": 661,
  "totalSize": 661
}
```
