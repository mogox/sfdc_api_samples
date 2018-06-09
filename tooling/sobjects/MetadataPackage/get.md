# Sample Description
Simple request of an MetadataPackage Get

## PATH
```
/services/data/{version}/tooling/sobjects/MetadataPackage/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{ }
```

## request description
Get details for a specific MetadataPackage record.

## response
```json
{
  "attributes": {
    "type": "MetadataPackage",
    "url": "/services/data/{version}/tooling/sobjects/MetadataPackage/{ID}"
  },
  "Id": "{ID}",
  "Name": "{Package_Name}",
  "NamespacePrefix": "{Package_Namespace}"
}
```
