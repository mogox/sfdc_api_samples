# Sample Description
Simple request of an ApexOrgWideCoverage record

## PATH
```
/services/data/{version}/tooling/query/?q=Select Id, PercentCovered from ApexOrgWideCoverage where Id = '{ID}'
```
## Supported Versions
39.0, 40.0, 41.0, 42.0, 43.0

## request
```json
{}
```

## response
```json
{
  "done": true,
  "entityTypeName": "ApexOrgWideCoverage",
  "queryLocator": null,
  "records": [
    {
      "Id": "{ID}",
      "PercentCovered": 83,
      "attributes": {
        "type": "ApexOrgWideCoverage",
        "url": "/services/data/{version}/tooling/sobjects/ApexOrgWideCoverage/{ID}"
      }
    }
  ],
  "size": 1,
  "totalSize": 1
}
```
