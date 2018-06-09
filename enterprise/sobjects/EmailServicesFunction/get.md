# Sample Description
Simple request of an EmailServicesFunction record

## PATH
```
/services/data/{version}/sobjects/EmailServicesFunction/{ID}
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
  "AddressInactiveAction": "2",
  "ApexClassId": "{ApexClass_ID}",
  "AttachmentOption": "0",
  "AuthenticationFailureAction": "2",
  "AuthorizationFailureAction": "2",
  "AuthorizedSenders": "gmail.com",
  "CreatedById": "{User_ID}",
  "CreatedDate": "2017-09-26T17:18:14.000+0000",
  "ErrorRoutingAddress": "myuser@sutro.com",
  "FunctionInactiveAction": "2",
  "FunctionName": "{EmailServiceName}",
  "Id": "{ID}",
  "IsActive": true,
  "IsAuthenticationRequired": true,
  "IsErrorRoutingEnabled": true,
  "IsTextAttachmentsAsBinary": false,
  "IsTlsRequired": false,
  "LastModifiedById": "{User_ID}",
  "LastModifiedDate": "2017-09-26T17:18:14.000+0000",
  "OverLimitAction": "2",
  "SystemModstamp": "2017-09-26T17:18:14.000+0000",
  "attributes": {
    "type": "EmailServicesFunction",
    "url": "/services/data/{version}/sobjects/EmailServicesFunction/{ID}"
  }
}
```
