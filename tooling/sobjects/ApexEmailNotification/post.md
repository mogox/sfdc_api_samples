# Sample Description
POST Request for ApexEmailNotification

## PATH
```
/services/data/v39.0/tooling/sobjects/ApexEmailNotification/
```
## Supported Versions
39.0

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
