# openapi_client.BillingApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**capture_billing_transaction_uid_capture_post**](BillingApi.md#capture_billing_transaction_uid_capture_post) | **POST** /billing/{transaction_uid}/capture | Capture
[**post_billing_post**](BillingApi.md#post_billing_post) | **POST** /billing/ | Post


# **capture_billing_transaction_uid_capture_post**
> bool capture_billing_transaction_uid_capture_post(transaction_uid, capture_request)

Capture

### Example


```python
import openapi_client
from openapi_client.models.capture_request import CaptureRequest
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.BillingApi(api_client)
    transaction_uid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    capture_request = openapi_client.CaptureRequest() # CaptureRequest | 

    try:
        # Capture
        api_response = api_instance.capture_billing_transaction_uid_capture_post(transaction_uid, capture_request)
        print("The response of BillingApi->capture_billing_transaction_uid_capture_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling BillingApi->capture_billing_transaction_uid_capture_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **transaction_uid** | **UUID**|  | 
 **capture_request** | [**CaptureRequest**](CaptureRequest.md)|  | 

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **post_billing_post**
> UUID post_billing_post(post_request, idempotency_key=idempotency_key)

Post

### Example


```python
import openapi_client
from openapi_client.models.post_request import PostRequest
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "http://localhost"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.BillingApi(api_client)
    post_request = openapi_client.PostRequest() # PostRequest | 
    idempotency_key = 'idempotency_key_example' # str |  (optional)

    try:
        # Post
        api_response = api_instance.post_billing_post(post_request, idempotency_key=idempotency_key)
        print("The response of BillingApi->post_billing_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling BillingApi->post_billing_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_request** | [**PostRequest**](PostRequest.md)|  | 
 **idempotency_key** | **str**|  | [optional] 

### Return type

**UUID**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

