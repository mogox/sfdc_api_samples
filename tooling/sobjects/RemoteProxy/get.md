# Sample Description
Simple request of an RemoteProxy Get

## PATH
```
/services/data/{version}/tooling/sobjects/RemoteProxy/{ID}
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
  "CreatedById": "{User ID}",
  "CreatedDate": "2016-09-15T22:21:35.000+0000",
  "Description": null,
  "EndpointUrl": "http://www.apexdevnet.com",
  "FullName": "ApexDevNet",
  "Id": "{ID}",
  "IsActive": true,
  "LastModifiedById": "{User ID}",
  "LastModifiedDate": "2016-09-15T22:21:35.000+0000",
  "ManageableState": "unmanaged",
  "Metadata": {
    "description": null,
    "disableProtocolSecurity": false,
    "isActive": true,
    "url": "http://www.apexdevnet.com",
    "urls": null
  },
  "NamespacePrefix": null,
  "ProtocolMismatch": false,
  "SiteName": "ApexDevNet",
  "SystemModstamp": "2016-09-15T22:21:35.000+0000",
  "attributes": {
    "type": "RemoteProxy",
    "url": "/services/data/{version}/tooling/sobjects/RemoteProxy/{ID}"
  }
}
```
