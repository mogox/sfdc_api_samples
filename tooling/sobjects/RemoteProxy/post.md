# Sample Description
POST Request for RemoteProxy

## PATH
```
/services/data/{version}/tooling/sobjects/RemoteProxy
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "FullName": "Apiato_RemoteProxy",
  "Metadata": {
    "disableProtocolSecurity": false,
    "isActive": true,
    "url": "https://na7.salesforce.com",
    "urls": null,
    "description": "Apiato RemoteProxy sample."
  }
}
```

## request description
This will create a new RemoteProxy record and set it as active.

## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
