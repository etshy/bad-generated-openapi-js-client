# Xxx.UsersApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addThings**](UsersApi.md#addThings) | **POST** /user/{id}/things | 



## addThings

> AddThingsCommandResponse addThings(id, addThingsCommand)



### Example

```javascript
import Xxx from 'xxx';
let defaultClient = Xxx.ApiClient.instance;
// Configure Bearer access token for authorization: Bearer
let Bearer = defaultClient.authentications['Bearer'];
Bearer.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new Xxx.UsersApi();
let id = 56; // Number | 
let addThingsCommand = new Xxx.AddThingsCommand(); // AddThingsCommand | 
apiInstance.addThings(id, addThingsCommand, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**|  | 
 **addThingsCommand** | [**AddThingsCommand**](AddThingsCommand.md)|  | 

### Return type

[**AddThingsCommandResponse**](AddThingsCommandResponse.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

