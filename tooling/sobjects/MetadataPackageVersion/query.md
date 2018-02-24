# Sample Description
Simple request of an MetadataPackageVersion record

## PATH
```
/services/data/v42.0/tooling/query/?q=Select Id, MetadataPackageId, Name, ReleaseState, MajorVersion, MinorVersion, PatchVersion, BuildNumber from MetadataPackageVersion
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{ }
```

## request description
Query request for the MetadataPackageVersion records.

## response
```json
{
  "size": 1,
  "totalSize": 1,
  "done": true,
  "queryLocator": null,
  "entityTypeName": "MetadataPackageVersion",
  "records": [
    {
      "attributes": {
        "type": "MetadataPackageVersion",
        "url": "/services/data/v42.0/tooling/sobjects/MetadataPackageVersion/{ID}"
      },
      "Id": "{ID}",
      "MetadataPackageId": "{MetadataPackageID}",
      "Name": "Spring 2016",
      "ReleaseState": "Beta",
      "MajorVersion": 1,
      "MinorVersion": 0,
      "PatchVersion": 0,
      "BuildNumber": 1
    }
  ]
}
```
