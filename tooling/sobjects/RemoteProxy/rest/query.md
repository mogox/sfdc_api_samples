# Sample Description
Simple request of an RemoteProxy record

## PATH
```
/services/data/v39.0/tooling/query/?q=select Id, Description, SiteName, IsActive from RemoteProxy
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
  "entityTypeName": "RemoteProxy",
  "queryLocator": null,
  "records": [
    {
      "Description": null,
      "Id": "{ID}",
      "IsActive": true,
      "SiteName": "ApexDevNet",
      "attributes": {
        "type": "RemoteProxy",
        "url": "/services/data/v39.0/tooling/sobjects/RemoteProxy/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```