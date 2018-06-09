# Sample Description
QUERY request of an ApexEmailNotification record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, UserId, Email from ApexEmailNotification where Id = '{ID}'
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
  "done": true,
  "entityTypeName": "ApexEmailNotification",
  "queryLocator": null,
  "records": [
    {
      "Email": null,
      "Id": "{ID}",
      "UserId": "{UserID}",
      "attributes": {
        "type": "ApexEmailNotification",
        "url": "/services/data/{version}/tooling/sobjects/ApexEmailNotification/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
