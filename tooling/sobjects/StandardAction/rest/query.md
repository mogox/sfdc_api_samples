# Sample Description
Simple request of an StandardAction record

## PATH
```
/services/data/v39.0/tooling/query/?q=select Name from StandardAction where EntityDefinition.QualifiedApiName = 'Account'
```
## Supported Versions
39.0

## request
 ```json
 {}
```

## response
```json
{
  "done": true,
  "entityTypeName": "StandardAction",
  "queryLocator": null,
  "records": [
    {
      "Name": "Edit",
      "attributes": {
        "type": "StandardAction",
        "url": "/services/data/v39.0/tooling/sobjects/StandardAction/Account.Edit"
      }
    },
    {
      "Name": "New",
      "attributes": {
        "type": "StandardAction",
        "url": "/services/data/v39.0/tooling/sobjects/StandardAction/Account.New"
      }
    },
    {
      "Name": "Delete",
      "attributes": {
        "type": "StandardAction",
        "url": "/services/data/v39.0/tooling/sobjects/StandardAction/Account.Delete"
      }
    }
  ],
  "size": 11,
  "totalSize": 11
}
```