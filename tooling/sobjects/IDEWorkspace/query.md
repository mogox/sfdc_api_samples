# Sample Description
Simple request of an IDEWorkspace record

## PATH
```
/services/data/v42.0/tooling/query/?q=Select Id, Name, Content, UserId, CreatedDate, LastModifiedDate from IDEWorkspace
```
## Supported Versions
39.0, 40.0, 41.0, 42.0

## request
```json
{ }
```

## request description
Query request for all IDEWorkspace records. NOTE: This is used internally by the Developer Console.

## response
```json
{
  "size": 1,
  "totalSize": 1,
  "done": true,
  "queryLocator": null,
  "entityTypeName": "IDEWorkspace",
  "records": [
    {
      "attributes": {
        "type": "IDEWorkspace",
        "url": "/services/data/v42.0/tooling/sobjects/IDEWorkspace/{ID}"
      },
      "Id": "{ID}",
      "Name": "DefaultWorkspace",
      "Content": "{}",
      "UserId": "{UserID}",
      "CreatedDate": "2016-09-15T22:21:35.000+0000",
      "LastModifiedDate": "2018-02-23T19:58:41.000+0000"
    }
  ]
}
```
