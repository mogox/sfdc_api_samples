# Sample Description
Simple request of an ApexLog record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, Application, DurationMilliseconds, Location, LogLength, LogUserId, Operation, Request, StartTime, Status from ApexLog where Id = {ID}
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
  "entityTypeName": "ApexLog",
  "queryLocator": null,
  "records": [
    {
      "Application": "Unknown",
      "DurationMilliseconds": 361,
      "Id": "{ID}",
      "Location": "Monitoring",
      "LogLength": 14106,
      "LogUserId": "{UserID}",
      "Operation": "/services/data/v39.0/tooling/executeAnonymous/",
      "Request": "Api",
      "StartTime": "2017-03-28T01:47:24.000+0000",
      "Status": "Success",
      "attributes": {
        "type": "ApexLog",
        "url": "/services/data/v39.0/tooling/sobjects/ApexLog/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
