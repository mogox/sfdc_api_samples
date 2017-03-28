# Sample Description
QUERY request of an ApexEmailNotification record

## PATH
```
/services/data/v39.0/tooling/query/?q=Select Id, UserId, Email from ApexEmailNotification where Id = '{ID}'
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
  "entityTypeName": "ApexEmailNotification",
  "queryLocator": null,
  "records": [
    {
      "Email": null,
      "Id": "{ID}",
      "UserId": "{UserID}",
      "attributes": {
        "type": "ApexEmailNotification",
        "url": "/services/data/v39.0/tooling/sobjects/ApexEmailNotification/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
