# Sample Description
PATCH request of an ApexEmailNotification record

## PATH
```
/services/data/{version}/tooling/sobjects/ApexEmailNotification/{ID}
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "UserId": "",
  "Email": "user@apiato.com"
}
```
## request description
You need to use either a user ID or an email address, not both.

## response
```json
{}
```
