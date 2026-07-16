# \FileStorageAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteFileFileStorageFileIdDelete**](FileStorageAPI.md#DeleteFileFileStorageFileIdDelete) | **Delete** /file-storage/{file_id} | Delete a file by file ID.
[**DownloadFileFileStorageFileIdDownloadGet**](FileStorageAPI.md#DownloadFileFileStorageFileIdDownloadGet) | **Get** /file-storage/{file_id}/download | Download a file by file ID.
[**GetFileInfoAndPresignedUrlFileStorageFileIdGet**](FileStorageAPI.md#GetFileInfoAndPresignedUrlFileStorageFileIdGet) | **Get** /file-storage/{file_id} | Get file info and presigned URL by file ID.
[**GetFileInfoFileStorageFileIdInfoGet**](FileStorageAPI.md#GetFileInfoFileStorageFileIdInfoGet) | **Get** /file-storage/{file_id}/info | Get file info by file ID.
[**GetFilePresignedUrlFileStorageFileIdPresignedUrlGet**](FileStorageAPI.md#GetFilePresignedUrlFileStorageFileIdPresignedUrlGet) | **Get** /file-storage/{file_id}/presigned-url | Get presigned URL for file download.
[**ListFilesFileStorageGet**](FileStorageAPI.md#ListFilesFileStorageGet) | **Get** /file-storage/ | List files in the file storage service.
[**UpdateFileMetadataFileStorageFileIdMetadataPut**](FileStorageAPI.md#UpdateFileMetadataFileStorageFileIdMetadataPut) | **Put** /file-storage/{file_id}/metadata | Update file metadata by file ID.
[**UploadFileFileStoragePost**](FileStorageAPI.md#UploadFileFileStoragePost) | **Post** /file-storage/ | Upload a file to the file storage service.



## DeleteFileFileStorageFileIdDelete

> DeleteFileFileStorageFileIdDelete(ctx, fileId).ProjectUuid(projectUuid).Execute()

Delete a file by file ID.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FileStorageAPI.DeleteFileFileStorageFileIdDelete(context.Background(), fileId).ProjectUuid(projectUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FileStorageAPI.DeleteFileFileStorageFileIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteFileFileStorageFileIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectUuid** | **string** |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadFileFileStorageFileIdDownloadGet

> interface{} DownloadFileFileStorageFileIdDownloadGet(ctx, fileId).ProjectUuid(projectUuid).Execute()

Download a file by file ID.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FileStorageAPI.DownloadFileFileStorageFileIdDownloadGet(context.Background(), fileId).ProjectUuid(projectUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FileStorageAPI.DownloadFileFileStorageFileIdDownloadGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadFileFileStorageFileIdDownloadGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `FileStorageAPI.DownloadFileFileStorageFileIdDownloadGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadFileFileStorageFileIdDownloadGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectUuid** | **string** |  | 

### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFileInfoAndPresignedUrlFileStorageFileIdGet

> FileInfoWithPresignedURLResponse GetFileInfoAndPresignedUrlFileStorageFileIdGet(ctx, fileId).ProjectUuid(projectUuid).Execute()

Get file info and presigned URL by file ID.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FileStorageAPI.GetFileInfoAndPresignedUrlFileStorageFileIdGet(context.Background(), fileId).ProjectUuid(projectUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FileStorageAPI.GetFileInfoAndPresignedUrlFileStorageFileIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFileInfoAndPresignedUrlFileStorageFileIdGet`: FileInfoWithPresignedURLResponse
	fmt.Fprintf(os.Stdout, "Response from `FileStorageAPI.GetFileInfoAndPresignedUrlFileStorageFileIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFileInfoAndPresignedUrlFileStorageFileIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectUuid** | **string** |  | 

### Return type

[**FileInfoWithPresignedURLResponse**](FileInfoWithPresignedURLResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFileInfoFileStorageFileIdInfoGet

> FileInfoResponse GetFileInfoFileStorageFileIdInfoGet(ctx, fileId).ProjectUuid(projectUuid).Execute()

Get file info by file ID.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FileStorageAPI.GetFileInfoFileStorageFileIdInfoGet(context.Background(), fileId).ProjectUuid(projectUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FileStorageAPI.GetFileInfoFileStorageFileIdInfoGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFileInfoFileStorageFileIdInfoGet`: FileInfoResponse
	fmt.Fprintf(os.Stdout, "Response from `FileStorageAPI.GetFileInfoFileStorageFileIdInfoGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFileInfoFileStorageFileIdInfoGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectUuid** | **string** |  | 

### Return type

[**FileInfoResponse**](FileInfoResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFilePresignedUrlFileStorageFileIdPresignedUrlGet

> FilePresignedURLResponse GetFilePresignedUrlFileStorageFileIdPresignedUrlGet(ctx, fileId).ProjectUuid(projectUuid).Execute()

Get presigned URL for file download.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FileStorageAPI.GetFilePresignedUrlFileStorageFileIdPresignedUrlGet(context.Background(), fileId).ProjectUuid(projectUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FileStorageAPI.GetFilePresignedUrlFileStorageFileIdPresignedUrlGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFilePresignedUrlFileStorageFileIdPresignedUrlGet`: FilePresignedURLResponse
	fmt.Fprintf(os.Stdout, "Response from `FileStorageAPI.GetFilePresignedUrlFileStorageFileIdPresignedUrlGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFilePresignedUrlFileStorageFileIdPresignedUrlGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectUuid** | **string** |  | 

### Return type

[**FilePresignedURLResponse**](FilePresignedURLResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListFilesFileStorageGet

> []FileInfoResponse ListFilesFileStorageGet(ctx).ProjectUuid(projectUuid).Execute()

List files in the file storage service.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FileStorageAPI.ListFilesFileStorageGet(context.Background()).ProjectUuid(projectUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FileStorageAPI.ListFilesFileStorageGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListFilesFileStorageGet`: []FileInfoResponse
	fmt.Fprintf(os.Stdout, "Response from `FileStorageAPI.ListFilesFileStorageGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListFilesFileStorageGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectUuid** | **string** |  | 

### Return type

[**[]FileInfoResponse**](FileInfoResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateFileMetadataFileStorageFileIdMetadataPut

> UpdateFileMetadataFileStorageFileIdMetadataPut(ctx, fileId).ProjectUuid(projectUuid).UpdateFileMetadataRequest(updateFileMetadataRequest).Execute()

Update file metadata by file ID.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	updateFileMetadataRequest := *openapiclient.NewUpdateFileMetadataRequest(map[string]UpdateFileMetadataRequestExtraMetadataValue{"key": *openapiclient.NewUpdateFileMetadataRequestExtraMetadataValue()}) // UpdateFileMetadataRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FileStorageAPI.UpdateFileMetadataFileStorageFileIdMetadataPut(context.Background(), fileId).ProjectUuid(projectUuid).UpdateFileMetadataRequest(updateFileMetadataRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FileStorageAPI.UpdateFileMetadataFileStorageFileIdMetadataPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateFileMetadataFileStorageFileIdMetadataPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectUuid** | **string** |  | 
 **updateFileMetadataRequest** | [**UpdateFileMetadataRequest**](UpdateFileMetadataRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadFileFileStoragePost

> FileUploadResponse UploadFileFileStoragePost(ctx).ProjectUuid(projectUuid).File(file).Execute()

Upload a file to the file storage service.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	file := "file_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FileStorageAPI.UploadFileFileStoragePost(context.Background()).ProjectUuid(projectUuid).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FileStorageAPI.UploadFileFileStoragePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadFileFileStoragePost`: FileUploadResponse
	fmt.Fprintf(os.Stdout, "Response from `FileStorageAPI.UploadFileFileStoragePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadFileFileStoragePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectUuid** | **string** |  | 
 **file** | **string** |  | 

### Return type

[**FileUploadResponse**](FileUploadResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

