# Sample Description
Simple request of an PermissionSet record

## PATH
```
/services/data/v39.0/tooling/query/?q= select Id, Name, Label from PermissionSet where PermissionsApiEnabled = true
```
## Supported Versions
39.0

## request
 ```json
 { }
```

## request description
Query for all the PermissionSets that have API access enabled.

## response
```json
{
  "done": true,
  "entityTypeName": "PermissionSet",
  "queryLocator": null,
  "records": [
    {
      "Id": "{ID}",
      "Label": "Apiato PermSet",
      "Name": "Apiato_PermSet",
      "attributes": {
        "type": "PermissionSet",
        "url": "/services/data/v39.0/tooling/sobjects/PermissionSet/{ID}"
      }
    },
    {
      "Id": "{ID}",
      "Label": "Apiato Admin PermSet",
      "Name": "Apiato_Admin_PermSet",
      "attributes": {
        "type": "PermissionSet",
        "url": "/services/data/v39.0/tooling/sobjects/PermissionSet/{ID}"
      }
    }
  ],
  "size": 2,
  "totalSize": 2
}
```
