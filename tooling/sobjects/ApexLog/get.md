# Sample Description
Simple request of an ApexLog record

## PATH
```
/services/data/{version}/tooling/sobjects/ApexLog/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{}
```

## response
```json
{
  "Application": "Unknown",
  "DurationMilliseconds": 361,
  "Id": "{ID}",
  "LastModifiedDate": "2017-03-28T01:47:24.000+0000",
  "Location": "Monitoring",
  "LogLength": 14106,
  "LogUserId": "{UserID}",
  "Operation": "/services/data/{version}/tooling/executeAnonymous/",
  "Request": "Api",
  "StartTime": "2017-03-28T01:47:24.000+0000",
  "Status": "Success",
  "SystemModstamp": "2017-03-28T01:47:24.000+0000",
  "attributes": {
    "type": "ApexLog",
    "url": "/services/data/{version}/tooling/sobjects/ApexLog/{ID}"
  }
}
```
