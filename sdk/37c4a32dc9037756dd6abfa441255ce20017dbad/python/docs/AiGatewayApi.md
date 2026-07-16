# openapi_client.AiGatewayApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ag_ui_gateway_ai_gateway_ag_ui_model_post**](AiGatewayApi.md#ag_ui_gateway_ai_gateway_ag_ui_model_post) | **POST** /ai-gateway/ag-ui/{model} | Ag Ui Gateway
[**get_models_ai_gateway_models_get**](AiGatewayApi.md#get_models_ai_gateway_models_get) | **GET** /ai-gateway/models | Get Models


# **ag_ui_gateway_ai_gateway_ag_ui_model_post**
> ResponseAgUiGatewayAiGatewayAgUiModelPost ag_ui_gateway_ai_gateway_ag_ui_model_post(model, project_id, run_agent_input_with_model_settings)

Ag Ui Gateway

### Example


```python
import openapi_client
from openapi_client.models.response_ag_ui_gateway_ai_gateway_ag_ui_model_post import ResponseAgUiGatewayAiGatewayAgUiModelPost
from openapi_client.models.run_agent_input_with_model_settings import RunAgentInputWithModelSettings
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
    api_instance = openapi_client.AiGatewayApi(api_client)
    model = 'model_example' # str | 
    project_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    run_agent_input_with_model_settings = openapi_client.RunAgentInputWithModelSettings() # RunAgentInputWithModelSettings | 

    try:
        # Ag Ui Gateway
        api_response = api_instance.ag_ui_gateway_ai_gateway_ag_ui_model_post(model, project_id, run_agent_input_with_model_settings)
        print("The response of AiGatewayApi->ag_ui_gateway_ai_gateway_ag_ui_model_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AiGatewayApi->ag_ui_gateway_ai_gateway_ag_ui_model_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **model** | **str**|  | 
 **project_id** | **UUID**|  | 
 **run_agent_input_with_model_settings** | [**RunAgentInputWithModelSettings**](RunAgentInputWithModelSettings.md)|  | 

### Return type

[**ResponseAgUiGatewayAiGatewayAgUiModelPost**](ResponseAgUiGatewayAiGatewayAgUiModelPost.md)

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

# **get_models_ai_gateway_models_get**
> List[str] get_models_ai_gateway_models_get()

Get Models

### Example


```python
import openapi_client
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
    api_instance = openapi_client.AiGatewayApi(api_client)

    try:
        # Get Models
        api_response = api_instance.get_models_ai_gateway_models_get()
        print("The response of AiGatewayApi->get_models_ai_gateway_models_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling AiGatewayApi->get_models_ai_gateway_models_get: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

**List[str]**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

