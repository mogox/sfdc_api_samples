# Sample Description
Simple request of an MetadataPackageVersion Get

## PATH
```
/services/data/{version}/tooling/sobjects/MetadataPackageVersion/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{ }
```

## request description
Get details for a specific MetadataPackageVersion record.

## response
```json
{
  "attributes": {
    "type": "MetadataPackageVersion",
    "url": "/services/data/{version}/tooling/sobjects/MetadataPackageVersion/{ID}"
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
```
