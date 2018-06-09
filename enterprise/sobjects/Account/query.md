# Sample Description
Simple request of an Account record

## PATH
```
/services/data/{version}/query/?q=Select Id, Name from Account where Id = '{ID}'
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
  "totalSize" : 1,
  "done" : true,
  "records" : [ {
    "attributes" : {
      "type" : "Account",
      "url" : "/services/data/{version}/sobjects/Account/{ID}"
    },
    "Id" : "{ID}",
    "Name" : "Vandelay Industries"
  } ]
}
```
