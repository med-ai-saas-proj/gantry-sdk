# RagApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**addFileRagFilesPost**](RagApi.md#addfileragfilespost) | **POST** /rag/files | Add a file to a RAG. |
| [**addTextRagTextPost**](RagApi.md#addtextragtextpost) | **POST** /rag/text | Add text to a RAG. |
| [**getFilesRagFilesGet**](RagApi.md#getfilesragfilesget) | **GET** /rag/files | List files in a RAG. |
| [**getTaskStatusRagFilesTaskIdGet**](RagApi.md#gettaskstatusragfilestaskidget) | **GET** /rag/files/{task_id} | Get RAG file embedding task status. |
| [**querySimilarByTextRagQueryTextPost**](RagApi.md#querysimilarbytextragquerytextpost) | **POST** /rag/query/text | Query a RAG by text. |



## addFileRagFilesPost

> string addFileRagFilesPost(projectUuid, addRagFileRequest)

Add a file to a RAG.

Endpoint to add a new file to a RAG.

### Example

```ts
import {
  Configuration,
  RagApi,
} from '';
import type { AddFileRagFilesPostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new RagApi();

  const body = {
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // AddRagFileRequest
    addRagFileRequest: ...,
  } satisfies AddFileRagFilesPostRequest;

  try {
    const data = await api.addFileRagFilesPost(body);
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
| **addRagFileRequest** | [AddRagFileRequest](AddRagFileRequest.md) |  | |

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
| **201** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## addTextRagTextPost

> string addTextRagTextPost(projectUuid, addTextToRagRequest)

Add text to a RAG.

Endpoint to add new text (without an associated file) to a RAG. The text will be chunked and embedded asynchronously.

### Example

```ts
import {
  Configuration,
  RagApi,
} from '';
import type { AddTextRagTextPostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new RagApi();

  const body = {
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // AddTextToRagRequest
    addTextToRagRequest: ...,
  } satisfies AddTextRagTextPostRequest;

  try {
    const data = await api.addTextRagTextPost(body);
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
| **addTextToRagRequest** | [AddTextToRagRequest](AddTextToRagRequest.md) |  | |

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
| **201** | Successful Response |  -  |
| **422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## getFilesRagFilesGet

> Array&lt;FileInfoResponse&gt; getFilesRagFilesGet(projectUuid)

List files in a RAG.

Endpoint to list distinct file ids stored in a RAG.

### Example

```ts
import {
  Configuration,
  RagApi,
} from '';
import type { GetFilesRagFilesGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new RagApi();

  const body = {
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies GetFilesRagFilesGetRequest;

  try {
    const data = await api.getFilesRagFilesGet(body);
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


## getTaskStatusRagFilesTaskIdGet

> EmbeddingTaskResponse getTaskStatusRagFilesTaskIdGet(taskId, projectUuid)

Get RAG file embedding task status.

Endpoint to get the status of an asynchronous RAG file embedding task.

### Example

```ts
import {
  Configuration,
  RagApi,
} from '';
import type { GetTaskStatusRagFilesTaskIdGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new RagApi();

  const body = {
    // string
    taskId: taskId_example,
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies GetTaskStatusRagFilesTaskIdGetRequest;

  try {
    const data = await api.getTaskStatusRagFilesTaskIdGet(body);
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
| **taskId** | `string` |  | [Defaults to `undefined`] |
| **projectUuid** | `string` |  | [Defaults to `undefined`] |

### Return type

[**EmbeddingTaskResponse**](EmbeddingTaskResponse.md)

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


## querySimilarByTextRagQueryTextPost

> Array&lt;RagQueryResponse&gt; querySimilarByTextRagQueryTextPost(projectUuid, queryRagQueryByTextRequest, includeEmbedding)

Query a RAG by text.

Endpoint to run a similarity search against a RAG by text. The service will generate an embedding for the query text and then run the similarity search.

### Example

```ts
import {
  Configuration,
  RagApi,
} from '';
import type { QuerySimilarByTextRagQueryTextPostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new RagApi();

  const body = {
    // string
    projectUuid: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
    // QueryRagQueryByTextRequest
    queryRagQueryByTextRequest: ...,
    // boolean | Whether to include embeddings in the response. Embeddings can be large, so they are excluded by default. (optional)
    includeEmbedding: true,
  } satisfies QuerySimilarByTextRagQueryTextPostRequest;

  try {
    const data = await api.querySimilarByTextRagQueryTextPost(body);
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
| **queryRagQueryByTextRequest** | [QueryRagQueryByTextRequest](QueryRagQueryByTextRequest.md) |  | |
| **includeEmbedding** | `boolean` | Whether to include embeddings in the response. Embeddings can be large, so they are excluded by default. | [Optional] [Defaults to `false`] |

### Return type

[**Array&lt;RagQueryResponse&gt;**](RagQueryResponse.md)

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

