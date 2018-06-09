# Sample Description
PATCH Request for EmailServicesAddress

## PATH
```
/services/data/{version}/sobjects/EmailServicesAddress/{ID}
```
## Supported Versions
38.0, 39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "AuthorizedSenders": "admin@sutro.com",
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
