# BillingApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**captureBillingTransactionUidCapturePost**](BillingApi.md#capturebillingtransactionuidcapturepost) | **POST** /billing/{transaction_uid}/capture | Capture |
| [**postBillingPost**](BillingApi.md#postbillingpost) | **POST** /billing/ | Post |



## captureBillingTransactionUidCapturePost

> boolean captureBillingTransactionUidCapturePost(transactionUid, captureRequest)

Capture

### Example

```ts
import {
  Configuration,
  BillingApi,
} from '';
import type { CaptureBillingTransactionUidCapturePostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new BillingApi();

  const body = {
    // string
    transactionUid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // CaptureRequest
    captureRequest: ...,
  } satisfies CaptureBillingTransactionUidCapturePostRequest;

  try {
    const data = await api.captureBillingTransactionUidCapturePost(body);
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
| **transactionUid** | `string` |  | [Defaults to `undefined`] |
| **captureRequest** | [CaptureRequest](CaptureRequest.md) |  | |

### Return type

**boolean**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## postBillingPost

> string postBillingPost(postRequest, idempotencyKey)

Post

### Example

```ts
import {
  Configuration,
  BillingApi,
} from '';
import type { PostBillingPostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new BillingApi();

  const body = {
    // PostRequest
    postRequest: ...,
    // string (optional)
    idempotencyKey: idempotencyKey_example,
  } satisfies PostBillingPostRequest;

  try {
    const data = await api.postBillingPost(body);
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
| **postRequest** | [PostRequest](PostRequest.md) |  | |
| **idempotencyKey** | `string` |  | [Optional] [Defaults to `undefined`] |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)

