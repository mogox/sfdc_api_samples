# Sample Description
Simple request of an EmailServicesFunction record

## PATH
```
/services/data/v40.0/query/?q=Select Id, AddressInactiveAction, ApexClassId, AttachmentOption, AuthenticationFailureAction, AuthorizationFailureAction, AuthorizedSenders, ErrorRoutingAddress, FunctionInactiveAction, FunctionName, IsActive, IsAuthenticationRequired, IsErrorRoutingEnabled, IsTextAttachmentsAsBinary, IsTlsRequired, OverLimitAction  from EmailServicesFunction where Id = '{ID}'
```
## Supported Versions
38.0, 39.0, 40.0

## request
 ```json
 { }
```

## response
```json
{
  "done": true,
  "records": [
    {
      "AddressInactiveAction": "2",
      "ApexClassId": "{ApexClass_ID}",
      "AttachmentOption": "0",
      "AuthenticationFailureAction": "2",
      "AuthorizationFailureAction": "2",
      "AuthorizedSenders": "mycompanydomain.com",
      "ErrorRoutingAddress": "{EmailAddress}",
      "FunctionInactiveAction": "2",
      "FunctionName": "{EmailServiceName}",
      "Id": "{ID}",
      "IsActive": true,
      "IsAuthenticationRequired": true,
      "IsErrorRoutingEnabled": true,
      "IsTextAttachmentsAsBinary": false,
      "IsTlsRequired": false,
      "OverLimitAction": "2",
      "attributes": {
        "type": "EmailServicesFunction",
        "url": "/services/data/v40.0/sobjects/EmailServicesFunction/{ID}"
      }
    }
  ],
  "totalSize": 1
}
```
