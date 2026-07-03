# \RagAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddFileRagFilesPost**](RagAPI.md#AddFileRagFilesPost) | **Post** /rag/files | Add a file to a RAG.
[**AddTextRagTextPost**](RagAPI.md#AddTextRagTextPost) | **Post** /rag/text | Add text to a RAG.
[**GetFilesRagFilesGet**](RagAPI.md#GetFilesRagFilesGet) | **Get** /rag/files | List files in a RAG.
[**GetTaskStatusRagFilesTaskIdGet**](RagAPI.md#GetTaskStatusRagFilesTaskIdGet) | **Get** /rag/files/{task_id} | Get RAG file embedding task status.
[**QuerySimilarByTextRagQueryTextPost**](RagAPI.md#QuerySimilarByTextRagQueryTextPost) | **Post** /rag/query/text | Query a RAG by text.



## AddFileRagFilesPost

> string AddFileRagFilesPost(ctx).ProjectUuid(projectUuid).AddRagFileRequest(addRagFileRequest).Execute()

Add a file to a RAG.



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
	addRagFileRequest := *openapiclient.NewAddRagFileRequest("FileUid_example") // AddRagFileRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RagAPI.AddFileRagFilesPost(context.Background()).ProjectUuid(projectUuid).AddRagFileRequest(addRagFileRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RagAPI.AddFileRagFilesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddFileRagFilesPost`: string
	fmt.Fprintf(os.Stdout, "Response from `RagAPI.AddFileRagFilesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAddFileRagFilesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectUuid** | **string** |  | 
 **addRagFileRequest** | [**AddRagFileRequest**](AddRagFileRequest.md) |  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AddTextRagTextPost

> string AddTextRagTextPost(ctx).ProjectUuid(projectUuid).AddTextToRagRequest(addTextToRagRequest).Execute()

Add text to a RAG.



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
	addTextToRagRequest := *openapiclient.NewAddTextToRagRequest(*openapiclient.NewText()) // AddTextToRagRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RagAPI.AddTextRagTextPost(context.Background()).ProjectUuid(projectUuid).AddTextToRagRequest(addTextToRagRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RagAPI.AddTextRagTextPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddTextRagTextPost`: string
	fmt.Fprintf(os.Stdout, "Response from `RagAPI.AddTextRagTextPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAddTextRagTextPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectUuid** | **string** |  | 
 **addTextToRagRequest** | [**AddTextToRagRequest**](AddTextToRagRequest.md) |  | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFilesRagFilesGet

> []FileInfoResponse GetFilesRagFilesGet(ctx).ProjectUuid(projectUuid).Execute()

List files in a RAG.



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
	resp, r, err := apiClient.RagAPI.GetFilesRagFilesGet(context.Background()).ProjectUuid(projectUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RagAPI.GetFilesRagFilesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFilesRagFilesGet`: []FileInfoResponse
	fmt.Fprintf(os.Stdout, "Response from `RagAPI.GetFilesRagFilesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetFilesRagFilesGetRequest struct via the builder pattern


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


## GetTaskStatusRagFilesTaskIdGet

> EmbeddingTaskResponse GetTaskStatusRagFilesTaskIdGet(ctx, taskId).ProjectUuid(projectUuid).Execute()

Get RAG file embedding task status.



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
	taskId := "taskId_example" // string | 
	projectUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RagAPI.GetTaskStatusRagFilesTaskIdGet(context.Background(), taskId).ProjectUuid(projectUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RagAPI.GetTaskStatusRagFilesTaskIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskStatusRagFilesTaskIdGet`: EmbeddingTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `RagAPI.GetTaskStatusRagFilesTaskIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskStatusRagFilesTaskIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectUuid** | **string** |  | 

### Return type

[**EmbeddingTaskResponse**](EmbeddingTaskResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## QuerySimilarByTextRagQueryTextPost

> []RagQueryResponse QuerySimilarByTextRagQueryTextPost(ctx).ProjectUuid(projectUuid).QueryRagQueryByTextRequest(queryRagQueryByTextRequest).IncludeEmbedding(includeEmbedding).Execute()

Query a RAG by text.



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
	queryRagQueryByTextRequest := *openapiclient.NewQueryRagQueryByTextRequest("QueryText_example") // QueryRagQueryByTextRequest | 
	includeEmbedding := true // bool | Whether to include embeddings in the response. Embeddings can be large, so they are excluded by default. (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RagAPI.QuerySimilarByTextRagQueryTextPost(context.Background()).ProjectUuid(projectUuid).QueryRagQueryByTextRequest(queryRagQueryByTextRequest).IncludeEmbedding(includeEmbedding).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RagAPI.QuerySimilarByTextRagQueryTextPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `QuerySimilarByTextRagQueryTextPost`: []RagQueryResponse
	fmt.Fprintf(os.Stdout, "Response from `RagAPI.QuerySimilarByTextRagQueryTextPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiQuerySimilarByTextRagQueryTextPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectUuid** | **string** |  | 
 **queryRagQueryByTextRequest** | [**QueryRagQueryByTextRequest**](QueryRagQueryByTextRequest.md) |  | 
 **includeEmbedding** | **bool** | Whether to include embeddings in the response. Embeddings can be large, so they are excluded by default. | [default to false]

### Return type

[**[]RagQueryResponse**](RagQueryResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

