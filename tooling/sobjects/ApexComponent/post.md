# Sample Description
POST request of an ApexComponent record

## PATH
```
/services/data/{version}/tooling/sobjects/ApexComponent
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{
  "Description": "Apiato Test Component",
  "Markup": "<apex:component >\n  <h1>Apiato VF Component</h1>\n</apex:component>",
  "MasterLabel": "ApiatoComponent",
  "Name": "ApiatoComponent"
}
```
## response
```json
{
  "errors": [],
  "id": "{ID}",
  "success": true
}
```
