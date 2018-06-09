# Sample Description
Simple request of an IDEWorkspace Get

## PATH
```
/services/data/{version}/tooling/sobjects/IDEWorkspace/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
 { }
```

## request description
Get details for a specific IDEWorkspace record. NOTE: This is used internally by the Developer Console.

## response
```json
{
  "attributes": {
    "type": "IDEWorkspace",
    "url": "/services/data/{version}/tooling/sobjects/IDEWorkspace/{ID}"
  },
  "Id": "{ID}",
  "IsDeleted": false,
  "CreatedDate": "2018-02-23T21:27:19.000+0000",
  "CreatedById": "{UserID}",
  "LastModifiedDate": "2018-02-23T21:31:50.000+0000",
  "LastModifiedById": "{UserID}",
  "SystemModstamp": "2018-02-23T21:31:50.000+0000",
  "UserId": "{UserID}",
  "Name": "DefaultWorkspace",
  "Content": "{}"
}
```
