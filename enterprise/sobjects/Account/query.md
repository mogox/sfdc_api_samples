# Sample Description
Simple request of an Account record

## PATH
```
/services/data/v39.0/query/?q=Select Id, Name from Account where Id = '{ID}'
```
## Supported Versions
38.0

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
      "url" : "/services/data/v39.0/sobjects/Account/{ID}"
    },
    "Id" : "{ID}",
    "Name" : "Vandelay Industries"
  } ]
}
```
