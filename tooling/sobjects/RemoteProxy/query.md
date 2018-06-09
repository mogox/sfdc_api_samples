# Sample Description
Simple request of an RemoteProxy record

## PATH
```
/services/data/{version}/tooling/query/?q=select Id, Description, SiteName, IsActive from RemoteProxy
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

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
        "url": "/services/data/{version}/tooling/sobjects/RemoteProxy/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
