# Sample Description
Simple request of an MetadataPackage record

## PATH
```
/services/data/v42.0/tooling/query/?q=Select Id, Name, NamespacePrefix from MetadataPackage
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{ }
```

## request description
Query request for the MetadataPackage records.

## response
```json
{
  "size": 1,
  "totalSize": 1,
  "done": true,
  "queryLocator": null,
  "entityTypeName": "MetadataPackage",
  "records": [
    {
      "attributes": {
        "type": "MetadataPackage",
        "url": "/services/data/v42.0/tooling/sobjects/MetadataPackage/{ID}"
      },
      "Id": "{ID}",
      "Name": "{Package_Name}",
      "NamespacePrefix": {Package_Namespace}
    }
  ]
}
```
