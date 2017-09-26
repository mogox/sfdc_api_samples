# Sample Description
PATCH Request for EmailServicesFunction

## PATH
```
/services/data/v40.0/sobjects/EmailServicesFunction/{ID}
```
## Supported Versions
38.0, 39.0, 40.0

## request
```json
{
  "ApexClassId": "{ApexClass_ID}",
  "AttachmentOption": "0",
  "AuthenticationFailureAction": "2",
  "AuthorizationFailureAction": "2",
  "AuthorizedSenders": "mycompanydomain.com",
  "ErrorRoutingAddress": "{EmailAddress}",
  "FunctionInactiveAction": "2",
  "FunctionName": "{EmailServiceName}",
  "IsActive": true,
  "IsAuthenticationRequired": true,
  "IsErrorRoutingEnabled": true,
  "IsTextAttachmentsAsBinary": false,
  "IsTlsRequired": false,
  "OverLimitAction": "2"
}
```
## response
```json
{
  "status" : "204",
  "message" : "No Content"
}
```
