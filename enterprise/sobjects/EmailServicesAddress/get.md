# Sample Description
Simple request of an EmailServicesAddress record

## PATH
```
/services/data/{version}/sobjects/EmailServicesAddress/{ID}
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
  "AuthorizedSenders": "admin@sutro.com",
  "CreatedById": "{User_ID}",
  "CreatedDate": "2017-09-26T17:18:38.000+0000",
  "EmailDomainName": "{GeneratedEmailDomain}",
  "FunctionId": "{EmailServicesFunction_ID}",
  "Id": "{ID}",
  "IsActive": true,
  "LastModifiedById": "{User_ID}",
  "LastModifiedDate": "2017-09-26T17:24:20.000+0000",
  "LocalPart": "{EmailServiceName}",
  "RunAsUserId": "{User_ID}",
  "SystemModstamp": "2017-09-26T17:24:20.000+0000",
  "attributes": {
    "type": "EmailServicesAddress",
    "url": "/services/data/{version}/sobjects/EmailServicesAddress/{ID}"
  }
}
```
