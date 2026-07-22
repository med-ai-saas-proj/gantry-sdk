# \AiGatewayAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AgUiGatewayAiGatewayAgUiModelPost**](AiGatewayAPI.md#AgUiGatewayAiGatewayAgUiModelPost) | **Post** /ai-gateway/ag-ui/{model} | Ag Ui Gateway
[**GetModelsAiGatewayModelsGet**](AiGatewayAPI.md#GetModelsAiGatewayModelsGet) | **Get** /ai-gateway/models | Get Models



## AgUiGatewayAiGatewayAgUiModelPost

> ResponseAgUiGatewayAiGatewayAgUiModelPost AgUiGatewayAiGatewayAgUiModelPost(ctx, model).ProjectId(projectId).RunAgentInputWithModelSettings(runAgentInputWithModelSettings).Execute()

Ag Ui Gateway

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
	model := "model_example" // string | 
	projectId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	runAgentInputWithModelSettings := *openapiclient.NewRunAgentInputWithModelSettings("ThreadId_example", "RunId_example", interface{}(123), []openapiclient.MessagesInner{openapiclient.Messages_inner{ActivityMessage: openapiclient.NewActivityMessage("Id_example", "ActivityType_example", map[string]interface{}{"key": interface{}(123)})}}, []openapiclient.Tool{*openapiclient.NewTool("Name_example", "Description_example")}, []openapiclient.Context{*openapiclient.NewContext("Description_example", "Value_example")}, interface{}(123)) // RunAgentInputWithModelSettings | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiGatewayAPI.AgUiGatewayAiGatewayAgUiModelPost(context.Background(), model).ProjectId(projectId).RunAgentInputWithModelSettings(runAgentInputWithModelSettings).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiGatewayAPI.AgUiGatewayAiGatewayAgUiModelPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AgUiGatewayAiGatewayAgUiModelPost`: ResponseAgUiGatewayAiGatewayAgUiModelPost
	fmt.Fprintf(os.Stdout, "Response from `AiGatewayAPI.AgUiGatewayAiGatewayAgUiModelPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**model** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAgUiGatewayAiGatewayAgUiModelPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectId** | **string** |  | 
 **runAgentInputWithModelSettings** | [**RunAgentInputWithModelSettings**](RunAgentInputWithModelSettings.md) |  | 

### Return type

[**ResponseAgUiGatewayAiGatewayAgUiModelPost**](ResponseAgUiGatewayAiGatewayAgUiModelPost.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetModelsAiGatewayModelsGet

> []string GetModelsAiGatewayModelsGet(ctx).Execute()

Get Models

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiGatewayAPI.GetModelsAiGatewayModelsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiGatewayAPI.GetModelsAiGatewayModelsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetModelsAiGatewayModelsGet`: []string
	fmt.Fprintf(os.Stdout, "Response from `AiGatewayAPI.GetModelsAiGatewayModelsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetModelsAiGatewayModelsGetRequest struct via the builder pattern


### Return type

**[]string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

