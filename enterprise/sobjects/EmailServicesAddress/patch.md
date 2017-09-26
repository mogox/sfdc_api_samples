# Sample Description
PATCH Request for EmailServicesAddress

## PATH
```
/services/data/v40.0/sobjects/EmailServicesAddress/{ID}
```
## Supported Versions
38.0, 39.0, 40.0

## request
```json
{
  "AuthorizedSenders": "admin@apiato.com",
  "FunctionId": "{EmailServicesFunction_ID}",
  "IsActive": true,
  "LocalPart": "{EmailServiceName}",
  "RunAsUserId": "{User_ID}"
}
```
## response
```json
{
  "status" : "204",
  "message" : "No Content"
}
```
