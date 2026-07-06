# AiGatewayApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**agUiGatewayAiGatewayAgUiModelPost**](AiGatewayApi.md#aguigatewayaigatewayaguimodelpost) | **POST** /ai-gateway/ag-ui/{model} | Ag Ui Gateway |
| [**getModelsAiGatewayModelsGet**](AiGatewayApi.md#getmodelsaigatewaymodelsget) | **GET** /ai-gateway/models | Get Models |



## agUiGatewayAiGatewayAgUiModelPost

> ResponseAgUiGatewayAiGatewayAgUiModelPost agUiGatewayAiGatewayAgUiModelPost(model, projectId, runAgentInputWithModelSettings)

Ag Ui Gateway

### Example

```ts
import {
  Configuration,
  AiGatewayApi,
} from '';
import type { AgUiGatewayAiGatewayAgUiModelPostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new AiGatewayApi();

  const body = {
    // string
    model: model_example,
    // string
    projectId: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // RunAgentInputWithModelSettings
    runAgentInputWithModelSettings: ...,
  } satisfies AgUiGatewayAiGatewayAgUiModelPostRequest;

  try {
    const data = await api.agUiGatewayAiGatewayAgUiModelPost(body);
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
| **model** | `string` |  | [Defaults to `undefined`] |
| **projectId** | `string` |  | [Defaults to `undefined`] |
| **runAgentInputWithModelSettings** | [RunAgentInputWithModelSettings](RunAgentInputWithModelSettings.md) |  | |

### Return type

[**ResponseAgUiGatewayAiGatewayAgUiModelPost**](ResponseAgUiGatewayAiGatewayAgUiModelPost.md)

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


## getModelsAiGatewayModelsGet

> Array&lt;string&gt; getModelsAiGatewayModelsGet()

Get Models

### Example

```ts
import {
  Configuration,
  AiGatewayApi,
} from '';
import type { GetModelsAiGatewayModelsGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new AiGatewayApi();

  try {
    const data = await api.getModelsAiGatewayModelsGet();
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters

This endpoint does not need any parameter.

### Return type

**Array<string>**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)

