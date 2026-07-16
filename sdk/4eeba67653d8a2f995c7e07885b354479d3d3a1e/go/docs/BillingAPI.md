# \BillingAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CaptureBillingTransactionUidCapturePost**](BillingAPI.md#CaptureBillingTransactionUidCapturePost) | **Post** /billing/{transaction_uid}/capture | Capture
[**PostBillingPost**](BillingAPI.md#PostBillingPost) | **Post** /billing/ | Post



## CaptureBillingTransactionUidCapturePost

> bool CaptureBillingTransactionUidCapturePost(ctx, transactionUid).CaptureRequest(captureRequest).Execute()

Capture

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
	transactionUid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	captureRequest := *openapiclient.NewCaptureRequest(*openapiclient.NewScaledAmount(int32(123), int32(123))) // CaptureRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.CaptureBillingTransactionUidCapturePost(context.Background(), transactionUid).CaptureRequest(captureRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.CaptureBillingTransactionUidCapturePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CaptureBillingTransactionUidCapturePost`: bool
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.CaptureBillingTransactionUidCapturePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**transactionUid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCaptureBillingTransactionUidCapturePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **captureRequest** | [**CaptureRequest**](CaptureRequest.md) |  | 

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostBillingPost

> string PostBillingPost(ctx).PostRequest(postRequest).IdempotencyKey(idempotencyKey).Execute()

Post

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
	postRequest := *openapiclient.NewPostRequest("ApiKeyUuid_example", *openapiclient.NewScaledAmount(int32(123), int32(123))) // PostRequest | 
	idempotencyKey := "idempotencyKey_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.PostBillingPost(context.Background()).PostRequest(postRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.PostBillingPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostBillingPost`: string
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.PostBillingPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostBillingPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **postRequest** | [**PostRequest**](PostRequest.md) |  | 
 **idempotencyKey** | **string** |  | 

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

