# Sample Description
POST Request for RemoteProxy

## PATH
```
/services/data/v40.0/tooling/sobjects/RemoteProxy
```
## Supported Versions
39.0, 40.0

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
