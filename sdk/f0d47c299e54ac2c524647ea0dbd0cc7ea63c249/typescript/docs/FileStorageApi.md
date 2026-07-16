# FileStorageApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**deleteFileFileStorageFileIdDelete**](FileStorageApi.md#deletefilefilestoragefileiddelete) | **DELETE** /file-storage/{file_id} | Delete a file by file ID. |
| [**downloadFileFileStorageFileIdDownloadGet**](FileStorageApi.md#downloadfilefilestoragefileiddownloadget) | **GET** /file-storage/{file_id}/download | Download a file by file ID. |
| [**getFileInfoAndPresignedUrlFileStorageFileIdGet**](FileStorageApi.md#getfileinfoandpresignedurlfilestoragefileidget) | **GET** /file-storage/{file_id} | Get file info and presigned URL by file ID. |
| [**getFileInfoFileStorageFileIdInfoGet**](FileStorageApi.md#getfileinfofilestoragefileidinfoget) | **GET** /file-storage/{file_id}/info | Get file info by file ID. |
| [**getFilePresignedUrlFileStorageFileIdPresignedUrlGet**](FileStorageApi.md#getfilepresignedurlfilestoragefileidpresignedurlget) | **GET** /file-storage/{file_id}/presigned-url | Get presigned URL for file download. |
| [**listFilesFileStorageGet**](FileStorageApi.md#listfilesfilestorageget) | **GET** /file-storage/ | List files in the file storage service. |
| [**updateFileMetadataFileStorageFileIdMetadataPut**](FileStorageApi.md#updatefilemetadatafilestoragefileidmetadataput) | **PUT** /file-storage/{file_id}/metadata | Update file metadata by file ID. |
| [**uploadFileFileStoragePost**](FileStorageApi.md#uploadfilefilestoragepost) | **POST** /file-storage/ | Upload a file to the file storage service. |



## deleteFileFileStorageFileIdDelete

> deleteFileFileStorageFileIdDelete(fileId, projectUuid)

Delete a file by file ID.

Endpoint to delete a file from storage by its file ID.

### Example

```ts
import {
  Configuration,
  FileStorageApi,
} from '';
import type { DeleteFileFileStorageFileIdDeleteRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new FileStorageApi();

  const body = {
    // string
    fileId: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies DeleteFileFileStorageFileIdDeleteRequest;

  try {
    const data = await api.deleteFileFileStorageFileIdDelete(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **fileId** | `string` |  | [Defaults to `undefined`] |
| **projectUuid** | `string` |  | [Defaults to `undefined`] |

### Return type

`void` (Empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **204** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## downloadFileFileStorageFileIdDownloadGet

> any downloadFileFileStorageFileIdDownloadGet(fileId, projectUuid)

Download a file by file ID.

Endpoint to download a file by its file ID.

### Example

```ts
import {
  Configuration,
  FileStorageApi,
} from '';
import type { DownloadFileFileStorageFileIdDownloadGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new FileStorageApi();

  const body = {
    // string
    fileId: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies DownloadFileFileStorageFileIdDownloadGetRequest;

  try {
    const data = await api.downloadFileFileStorageFileIdDownloadGet(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **fileId** | `string` |  | [Defaults to `undefined`] |
| **projectUuid** | `string` |  | [Defaults to `undefined`] |

### Return type

**any**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful Response |  -  |
| **302** | Redirect to object storage presigned URL for file download. |  * Location - The URL to redirect to <br>  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## getFileInfoAndPresignedUrlFileStorageFileIdGet

> FileInfoWithPresignedURLResponse getFileInfoAndPresignedUrlFileStorageFileIdGet(fileId, projectUuid)

Get file info and presigned URL by file ID.

Endpoint to retrieve file info and a presigned URL for downloading the file by file ID.

### Example

```ts
import {
  Configuration,
  FileStorageApi,
} from '';
import type { GetFileInfoAndPresignedUrlFileStorageFileIdGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new FileStorageApi();

  const body = {
    // string
    fileId: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies GetFileInfoAndPresignedUrlFileStorageFileIdGetRequest;

  try {
    const data = await api.getFileInfoAndPresignedUrlFileStorageFileIdGet(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **fileId** | `string` |  | [Defaults to `undefined`] |
| **projectUuid** | `string` |  | [Defaults to `undefined`] |

### Return type

[**FileInfoWithPresignedURLResponse**](FileInfoWithPresignedURLResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## getFileInfoFileStorageFileIdInfoGet

> FileInfoResponse getFileInfoFileStorageFileIdInfoGet(fileId, projectUuid)

Get file info by file ID.

Endpoint to retrieve file info by file ID.

### Example

```ts
import {
  Configuration,
  FileStorageApi,
} from '';
import type { GetFileInfoFileStorageFileIdInfoGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new FileStorageApi();

  const body = {
    // string
    fileId: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies GetFileInfoFileStorageFileIdInfoGetRequest;

  try {
    const data = await api.getFileInfoFileStorageFileIdInfoGet(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **fileId** | `string` |  | [Defaults to `undefined`] |
| **projectUuid** | `string` |  | [Defaults to `undefined`] |

### Return type

[**FileInfoResponse**](FileInfoResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## getFilePresignedUrlFileStorageFileIdPresignedUrlGet

> FilePresignedURLResponse getFilePresignedUrlFileStorageFileIdPresignedUrlGet(fileId, projectUuid)

Get presigned URL for file download.

Endpoint to generate a presigned URL for downloading the file.

### Example

```ts
import {
  Configuration,
  FileStorageApi,
} from '';
import type { GetFilePresignedUrlFileStorageFileIdPresignedUrlGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new FileStorageApi();

  const body = {
    // string
    fileId: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies GetFilePresignedUrlFileStorageFileIdPresignedUrlGetRequest;

  try {
    const data = await api.getFilePresignedUrlFileStorageFileIdPresignedUrlGet(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **fileId** | `string` |  | [Defaults to `undefined`] |
| **projectUuid** | `string` |  | [Defaults to `undefined`] |

### Return type

[**FilePresignedURLResponse**](FilePresignedURLResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## listFilesFileStorageGet

> Array&lt;FileInfoResponse&gt; listFilesFileStorageGet(projectUuid)

List files in the file storage service.

Endpoint to list files in the file storage service.

### Example

```ts
import {
  Configuration,
  FileStorageApi,
} from '';
import type { ListFilesFileStorageGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new FileStorageApi();

  const body = {
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies ListFilesFileStorageGetRequest;

  try {
    const data = await api.listFilesFileStorageGet(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **projectUuid** | `string` |  | [Defaults to `undefined`] |

### Return type

[**Array&lt;FileInfoResponse&gt;**](FileInfoResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## updateFileMetadataFileStorageFileIdMetadataPut

> updateFileMetadataFileStorageFileIdMetadataPut(fileId, projectUuid, updateFileMetadataRequest)

Update file metadata by file ID.

Endpoint to update file metadata by file ID.

### Example

```ts
import {
  Configuration,
  FileStorageApi,
} from '';
import type { UpdateFileMetadataFileStorageFileIdMetadataPutRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new FileStorageApi();

  const body = {
    // string
    fileId: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // UpdateFileMetadataRequest
    updateFileMetadataRequest: ...,
  } satisfies UpdateFileMetadataFileStorageFileIdMetadataPutRequest;

  try {
    const data = await api.updateFileMetadataFileStorageFileIdMetadataPut(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **fileId** | `string` |  | [Defaults to `undefined`] |
| **projectUuid** | `string` |  | [Defaults to `undefined`] |
| **updateFileMetadataRequest** | [UpdateFileMetadataRequest](UpdateFileMetadataRequest.md) |  | |

### Return type

`void` (Empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **204** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## uploadFileFileStoragePost

> FileUploadResponse uploadFileFileStoragePost(projectUuid, file)

Upload a file to the file storage service.

Endpoint to upload a file to the file storage service.

### Example

```ts
import {
  Configuration,
  FileStorageApi,
} from '';
import type { UploadFileFileStoragePostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new FileStorageApi();

  const body = {
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // string
    file: file_example,
  } satisfies UploadFileFileStoragePostRequest;

  try {
    const data = await api.uploadFileFileStoragePost(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **projectUuid** | `string` |  | [Defaults to `undefined`] |
| **file** | `string` |  | [Defaults to `undefined`] |

### Return type

[**FileUploadResponse**](FileUploadResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `multipart/form-data`
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)

