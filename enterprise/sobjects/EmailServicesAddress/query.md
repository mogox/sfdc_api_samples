# Sample Description
Simple request of an EmailServicesAddress record

## PATH
```
/services/data/v40.0/query/?q=Select Id, AuthorizedSenders, EmailDomainName, FunctionId, IsActive, LocalPart, RunAsUserId from EmailServicesAddress where Id = '{ID}'
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
      "AuthorizedSenders": "admin@apiato.com",
      "EmailDomainName": "{GeneratedEmailDomain}",
      "FunctionId": "{EmailServicesFunction_ID}",
      "Id": "{ID}",
      "IsActive": true,
      "LocalPart": "{EmailServiceName}",
      "RunAsUserId": "{User_ID}",
      "attributes": {
        "type": "EmailServicesAddress",
        "url": "/services/data/v40.0/sobjects/EmailServicesAddress/{ID}"
      }
    }
  ],
  "totalSize": 1
}
```
