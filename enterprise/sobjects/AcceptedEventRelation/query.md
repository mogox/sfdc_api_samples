# Sample Description
Simple request of an AcceptedEventRelation record

## PATH
```
/services/data/{version}/query/?q=Select eventId, type, response from AcceptedEventRelation where eventId = '{eventId}'
```
## Supported Versions
39.0

## request
 ```json
 { }
```

## response
```json
{
  "totalSize" : 1,
  "done" : true,
  "records" : [ ]
}
```
