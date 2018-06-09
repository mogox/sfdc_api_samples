# Sample Description
Simple request of an ApexCodeCoverageAggregate record

## PATH
```
/services/data/{version}/tooling/sobjects/ApexCodeCoverageAggregate/{Id}
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
  "ApexClassOrTriggerId": "{ApexClassOrTriggerId}",
  "Coverage": {
    "coveredLines": [
      3,
      8,
      9
    ],
    "uncoveredLines": []
  },
  "CoverageLastModifiedDate": null,
  "CreatedById": "00541000000uEgSAAU",
  "CreatedDate": "2016-09-17T00:02:09.000+0000",
  "Id": "{ID}",
  "IsDeleted": false,
  "LastModifiedById": "00541000000uEgSAAU",
  "LastModifiedDate": "2017-03-28T00:11:36.000+0000",
  "NumLinesCovered": 3,
  "NumLinesUncovered": 0,
  "SystemModstamp": "2017-03-28T00:11:36.000+0000",
  "attributes": {
    "type": "ApexCodeCoverageAggregate",
    "url": "/services/data/{version}/tooling/sobjects/ApexCodeCoverageAggregate/{ID}"
  }
}
```
