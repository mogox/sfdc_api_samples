# Sample Description
POST Request for EmailServicesAddress

## PATH
```
/services/data/{version}/sobjects/EmailServicesAddress
```
## Supported Versions
38.0, 39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "AuthorizedSenders": "admin@mycompanydomain.com",
  "FunctionId": "{EmailServicesFunction_ID}",
  "IsActive": true,
  "LocalPart": "{EmailServiceName}",
  "RunAsUserId": "{User_ID}"
}
```
## response
```json
{
  "id": "{ID}",
  "success": true,
  "errors": [],
  "warnings": []
}
```
