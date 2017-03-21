# Sample Description
QUERY Request for Account

## PATH
```
/services/data/v39.0/sobjects/Account
```
## Supported Versions
39.0

## request
```xml
<?xml version="1.0" encoding="utf-8"?>  
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
 xmlns:urn="urn:enterprise.soap.sforce.com">
<soapenv:Header>
   <urn:SessionHeader>
      <urn:sessionId>QwWsHJyTPW.1pd0_jXlNKOSU</urn:sessionId>
   </urn:SessionHeader>
</soapenv:Header>
<soapenv:Body>
   <urn:query>
      <urn:queryString>SELECT Id, Name, BillingStreet FROM Account WHERE Name LIKE '%a%'</urn:queryString>
   </urn:query>
</soapenv:Body>
</soapenv:Envelope>
```
