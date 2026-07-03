# openapi_client.RagApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_file_rag_files_post**](RagApi.md#add_file_rag_files_post) | **POST** /rag/files | Add a file to a RAG.
[**add_text_rag_text_post**](RagApi.md#add_text_rag_text_post) | **POST** /rag/text | Add text to a RAG.
[**get_files_rag_files_get**](RagApi.md#get_files_rag_files_get) | **GET** /rag/files | List files in a RAG.
[**get_task_status_rag_files_task_id_get**](RagApi.md#get_task_status_rag_files_task_id_get) | **GET** /rag/files/{task_id} | Get RAG file embedding task status.
[**query_similar_by_text_rag_query_text_post**](RagApi.md#query_similar_by_text_rag_query_text_post) | **POST** /rag/query/text | Query a RAG by text.


# **add_file_rag_files_post**
> str add_file_rag_files_post(project_uuid, add_rag_file_request)

Add a file to a RAG.

Endpoint to add a new file to a RAG.

### Example


```python
import openapi_client
from openapi_client.models.add_rag_file_request import AddRagFileRequest
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
    api_instance = openapi_client.RagApi(api_client)
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    add_rag_file_request = openapi_client.AddRagFileRequest() # AddRagFileRequest | 

    try:
        # Add a file to a RAG.
        api_response = api_instance.add_file_rag_files_post(project_uuid, add_rag_file_request)
        print("The response of RagApi->add_file_rag_files_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling RagApi->add_file_rag_files_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_uuid** | **UUID**|  | 
 **add_rag_file_request** | [**AddRagFileRequest**](AddRagFileRequest.md)|  | 

### Return type

**str**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_text_rag_text_post**
> str add_text_rag_text_post(project_uuid, add_text_to_rag_request)

Add text to a RAG.

Endpoint to add new text (without an associated file) to a RAG. The text will be chunked and embedded asynchronously.

### Example


```python
import openapi_client
from openapi_client.models.add_text_to_rag_request import AddTextToRagRequest
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
    api_instance = openapi_client.RagApi(api_client)
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    add_text_to_rag_request = openapi_client.AddTextToRagRequest() # AddTextToRagRequest | 

    try:
        # Add text to a RAG.
        api_response = api_instance.add_text_rag_text_post(project_uuid, add_text_to_rag_request)
        print("The response of RagApi->add_text_rag_text_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling RagApi->add_text_rag_text_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_uuid** | **UUID**|  | 
 **add_text_to_rag_request** | [**AddTextToRagRequest**](AddTextToRagRequest.md)|  | 

### Return type

**str**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_files_rag_files_get**
> List[FileInfoResponse] get_files_rag_files_get(project_uuid)

List files in a RAG.

Endpoint to list distinct file ids stored in a RAG.

### Example


```python
import openapi_client
from openapi_client.models.file_info_response import FileInfoResponse
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
    api_instance = openapi_client.RagApi(api_client)
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 

    try:
        # List files in a RAG.
        api_response = api_instance.get_files_rag_files_get(project_uuid)
        print("The response of RagApi->get_files_rag_files_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling RagApi->get_files_rag_files_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_uuid** | **UUID**|  | 

### Return type

[**List[FileInfoResponse]**](FileInfoResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_task_status_rag_files_task_id_get**
> EmbeddingTaskResponse get_task_status_rag_files_task_id_get(task_id, project_uuid)

Get RAG file embedding task status.

Endpoint to get the status of an asynchronous RAG file embedding task.

### Example


```python
import openapi_client
from openapi_client.models.embedding_task_response import EmbeddingTaskResponse
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
    api_instance = openapi_client.RagApi(api_client)
    task_id = 'task_id_example' # str | 
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 

    try:
        # Get RAG file embedding task status.
        api_response = api_instance.get_task_status_rag_files_task_id_get(task_id, project_uuid)
        print("The response of RagApi->get_task_status_rag_files_task_id_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling RagApi->get_task_status_rag_files_task_id_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **task_id** | **str**|  | 
 **project_uuid** | **UUID**|  | 

### Return type

[**EmbeddingTaskResponse**](EmbeddingTaskResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **query_similar_by_text_rag_query_text_post**
> List[RagQueryResponse] query_similar_by_text_rag_query_text_post(project_uuid, query_rag_query_by_text_request, include_embedding=include_embedding)

Query a RAG by text.

Endpoint to run a similarity search against a RAG by text. The service will generate an embedding for the query text and then run the similarity search.

### Example


```python
import openapi_client
from openapi_client.models.query_rag_query_by_text_request import QueryRagQueryByTextRequest
from openapi_client.models.rag_query_response import RagQueryResponse
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
    api_instance = openapi_client.RagApi(api_client)
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    query_rag_query_by_text_request = openapi_client.QueryRagQueryByTextRequest() # QueryRagQueryByTextRequest | 
    include_embedding = False # bool | Whether to include embeddings in the response. Embeddings can be large, so they are excluded by default. (optional) (default to False)

    try:
        # Query a RAG by text.
        api_response = api_instance.query_similar_by_text_rag_query_text_post(project_uuid, query_rag_query_by_text_request, include_embedding=include_embedding)
        print("The response of RagApi->query_similar_by_text_rag_query_text_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling RagApi->query_similar_by_text_rag_query_text_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_uuid** | **UUID**|  | 
 **query_rag_query_by_text_request** | [**QueryRagQueryByTextRequest**](QueryRagQueryByTextRequest.md)|  | 
 **include_embedding** | **bool**| Whether to include embeddings in the response. Embeddings can be large, so they are excluded by default. | [optional] [default to False]

### Return type

[**List[RagQueryResponse]**](RagQueryResponse.md)

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

