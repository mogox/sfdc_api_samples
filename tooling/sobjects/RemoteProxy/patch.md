# Sample Description
PATCH Request for RemoteProxy

## PATH
```
/services/data/{version}/tooling/sobjects/RemoteProxy/{ID}
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
    "url": "https://na10.salesforce.com",
    "urls": null,
    "description": "Apiato RemoteProxy sample, patch."
  }
}
```

## request description
This will update an existing RemoteProxy record by changing its url value & description.

## response
```json
{}
```
