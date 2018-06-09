# Sample Description
POST Request for ApexEmailNotification

## PATH
```
/services/data/{version}/tooling/sobjects/ApexEmailNotification/
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "UserId": "{UserID}"
}
```
## request description
You need to use either a user ID or an email address, not both.

## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
