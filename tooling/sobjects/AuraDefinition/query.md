# Sample Description
Simple request of an AuraDefinition record

## PATH
```
/services/data/{version}/tooling/query/?q=select id, ManageableState, AuraDefinitionBundleId, DefType, Format, Source from AuraDefinition
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{ }
```

## request description
Query request for AuraDefinition records.

## response
```json
{
  "size": 1,
  "totalSize": 1,
  "done": true,
  "queryLocator": null,
  "entityTypeName": "AuraDefinition",
  "records": [
    {
      "attributes": {
        "type": "AuraDefinition",
        "url": "/services/data/{version}/tooling/sobjects/AuraDefinition/{ID}"
      },
      "Id": "{ID}",
      "ManageableState": "unmanaged",
      "AuraDefinitionBundleId": "{AuraDefinitionBundleID}",
      "DefType": "APPLICATION",
      "Format": "XML",
      "Source": "<aura:application >\n\t\n</aura:application>"
    }
  ]
}
```
