# Sample Description
Simple request of an EmailServicesFunction record

## PATH
```
/services/data/{version}/query/?q=Select Id, AddressInactiveAction, ApexClassId, AttachmentOption, AuthenticationFailureAction, AuthorizationFailureAction, AuthorizedSenders, ErrorRoutingAddress, FunctionInactiveAction, FunctionName, IsActive, IsAuthenticationRequired, IsErrorRoutingEnabled, IsTextAttachmentsAsBinary, IsTlsRequired, OverLimitAction  from EmailServicesFunction where Id = '{ID}'
```
## Supported Versions
38.0, 39.0, 40.0, 41.0, 42.0, 43.0

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
        "url": "/services/data/{version}/sobjects/EmailServicesFunction/{ID}"
      }
    }
  ],
  "totalSize": 1
}
```
