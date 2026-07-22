# openapi_client.FileStorageApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**delete_file_file_storage_file_id_delete**](FileStorageApi.md#delete_file_file_storage_file_id_delete) | **DELETE** /file-storage/{file_id} | Delete a file by file ID.
[**download_file_file_storage_file_id_download_get**](FileStorageApi.md#download_file_file_storage_file_id_download_get) | **GET** /file-storage/{file_id}/download | Download a file by file ID.
[**get_file_info_and_presigned_url_file_storage_file_id_get**](FileStorageApi.md#get_file_info_and_presigned_url_file_storage_file_id_get) | **GET** /file-storage/{file_id} | Get file info and presigned URL by file ID.
[**get_file_info_file_storage_file_id_info_get**](FileStorageApi.md#get_file_info_file_storage_file_id_info_get) | **GET** /file-storage/{file_id}/info | Get file info by file ID.
[**get_file_presigned_url_file_storage_file_id_presigned_url_get**](FileStorageApi.md#get_file_presigned_url_file_storage_file_id_presigned_url_get) | **GET** /file-storage/{file_id}/presigned-url | Get presigned URL for file download.
[**list_files_file_storage_get**](FileStorageApi.md#list_files_file_storage_get) | **GET** /file-storage/ | List files in the file storage service.
[**update_file_metadata_file_storage_file_id_metadata_put**](FileStorageApi.md#update_file_metadata_file_storage_file_id_metadata_put) | **PUT** /file-storage/{file_id}/metadata | Update file metadata by file ID.
[**upload_file_file_storage_post**](FileStorageApi.md#upload_file_file_storage_post) | **POST** /file-storage/ | Upload a file to the file storage service.


# **delete_file_file_storage_file_id_delete**
> delete_file_file_storage_file_id_delete(file_id, project_uuid)

Delete a file by file ID.

Endpoint to delete a file from storage by its file ID.

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
    api_instance = openapi_client.FileStorageApi(api_client)
    file_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 

    try:
        # Delete a file by file ID.
        api_instance.delete_file_file_storage_file_id_delete(file_id, project_uuid)
    except Exception as e:
        print("Exception when calling FileStorageApi->delete_file_file_storage_file_id_delete: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file_id** | **UUID**|  | 
 **project_uuid** | **UUID**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **download_file_file_storage_file_id_download_get**
> object download_file_file_storage_file_id_download_get(file_id, project_uuid)

Download a file by file ID.

Endpoint to download a file by its file ID.

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
    api_instance = openapi_client.FileStorageApi(api_client)
    file_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 

    try:
        # Download a file by file ID.
        api_response = api_instance.download_file_file_storage_file_id_download_get(file_id, project_uuid)
        print("The response of FileStorageApi->download_file_file_storage_file_id_download_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FileStorageApi->download_file_file_storage_file_id_download_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file_id** | **UUID**|  | 
 **project_uuid** | **UUID**|  | 

### Return type

**object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**302** | Redirect to object storage presigned URL for file download. |  * Location - The URL to redirect to <br>  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_file_info_and_presigned_url_file_storage_file_id_get**
> FileInfoWithPresignedURLResponse get_file_info_and_presigned_url_file_storage_file_id_get(file_id, project_uuid)

Get file info and presigned URL by file ID.

Endpoint to retrieve file info and a presigned URL for downloading the file by file ID.

### Example


```python
import openapi_client
from openapi_client.models.file_info_with_presigned_url_response import FileInfoWithPresignedURLResponse
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
    api_instance = openapi_client.FileStorageApi(api_client)
    file_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 

    try:
        # Get file info and presigned URL by file ID.
        api_response = api_instance.get_file_info_and_presigned_url_file_storage_file_id_get(file_id, project_uuid)
        print("The response of FileStorageApi->get_file_info_and_presigned_url_file_storage_file_id_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FileStorageApi->get_file_info_and_presigned_url_file_storage_file_id_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file_id** | **UUID**|  | 
 **project_uuid** | **UUID**|  | 

### Return type

[**FileInfoWithPresignedURLResponse**](FileInfoWithPresignedURLResponse.md)

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

# **get_file_info_file_storage_file_id_info_get**
> FileInfoResponse get_file_info_file_storage_file_id_info_get(file_id, project_uuid)

Get file info by file ID.

Endpoint to retrieve file info by file ID.

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
    api_instance = openapi_client.FileStorageApi(api_client)
    file_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 

    try:
        # Get file info by file ID.
        api_response = api_instance.get_file_info_file_storage_file_id_info_get(file_id, project_uuid)
        print("The response of FileStorageApi->get_file_info_file_storage_file_id_info_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FileStorageApi->get_file_info_file_storage_file_id_info_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file_id** | **UUID**|  | 
 **project_uuid** | **UUID**|  | 

### Return type

[**FileInfoResponse**](FileInfoResponse.md)

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

# **get_file_presigned_url_file_storage_file_id_presigned_url_get**
> FilePresignedURLResponse get_file_presigned_url_file_storage_file_id_presigned_url_get(file_id, project_uuid)

Get presigned URL for file download.

Endpoint to generate a presigned URL for downloading the file.

### Example


```python
import openapi_client
from openapi_client.models.file_presigned_url_response import FilePresignedURLResponse
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
    api_instance = openapi_client.FileStorageApi(api_client)
    file_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 

    try:
        # Get presigned URL for file download.
        api_response = api_instance.get_file_presigned_url_file_storage_file_id_presigned_url_get(file_id, project_uuid)
        print("The response of FileStorageApi->get_file_presigned_url_file_storage_file_id_presigned_url_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FileStorageApi->get_file_presigned_url_file_storage_file_id_presigned_url_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file_id** | **UUID**|  | 
 **project_uuid** | **UUID**|  | 

### Return type

[**FilePresignedURLResponse**](FilePresignedURLResponse.md)

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

# **list_files_file_storage_get**
> List[FileInfoResponse] list_files_file_storage_get(project_uuid)

List files in the file storage service.

Endpoint to list files in the file storage service.

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
    api_instance = openapi_client.FileStorageApi(api_client)
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 

    try:
        # List files in the file storage service.
        api_response = api_instance.list_files_file_storage_get(project_uuid)
        print("The response of FileStorageApi->list_files_file_storage_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FileStorageApi->list_files_file_storage_get: %s\n" % e)
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

# **update_file_metadata_file_storage_file_id_metadata_put**
> update_file_metadata_file_storage_file_id_metadata_put(file_id, project_uuid, update_file_metadata_request)

Update file metadata by file ID.

Endpoint to update file metadata by file ID.

### Example


```python
import openapi_client
from openapi_client.models.update_file_metadata_request import UpdateFileMetadataRequest
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
    api_instance = openapi_client.FileStorageApi(api_client)
    file_id = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    update_file_metadata_request = openapi_client.UpdateFileMetadataRequest() # UpdateFileMetadataRequest | 

    try:
        # Update file metadata by file ID.
        api_instance.update_file_metadata_file_storage_file_id_metadata_put(file_id, project_uuid, update_file_metadata_request)
    except Exception as e:
        print("Exception when calling FileStorageApi->update_file_metadata_file_storage_file_id_metadata_put: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file_id** | **UUID**|  | 
 **project_uuid** | **UUID**|  | 
 **update_file_metadata_request** | [**UpdateFileMetadataRequest**](UpdateFileMetadataRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **upload_file_file_storage_post**
> FileUploadResponse upload_file_file_storage_post(project_uuid, file)

Upload a file to the file storage service.

Endpoint to upload a file to the file storage service.

### Example


```python
import openapi_client
from openapi_client.models.file_upload_response import FileUploadResponse
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
    api_instance = openapi_client.FileStorageApi(api_client)
    project_uuid = UUID('38400000-8cf0-11bd-b23e-10b96e4ef00d') # UUID | 
    file = 'file_example' # str | 

    try:
        # Upload a file to the file storage service.
        api_response = api_instance.upload_file_file_storage_post(project_uuid, file)
        print("The response of FileStorageApi->upload_file_file_storage_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling FileStorageApi->upload_file_file_storage_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_uuid** | **UUID**|  | 
 **file** | **str**|  | 

### Return type

[**FileUploadResponse**](FileUploadResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Successful Response |  -  |
**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

