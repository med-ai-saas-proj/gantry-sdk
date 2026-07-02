# EmbeddingTaskResponse

DTO for RAG embedding task status response.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**task_id** | **str** |  | 
**file_uid** | **UUID** |  | 
**text** | [**Text1**](Text1.md) |  | 
**metadata** | **Dict[str, object]** |  | 
**type** | **str** |  | 
**project_uuid** | **UUID** |  | 
**chunk_splitter** | [**ChunkSplitterType**](ChunkSplitterType.md) |  | 
**chunk_splitter_options** | [**ChunkSplitterOptions**](ChunkSplitterOptions.md) |  | [optional] 
**chunk_size** | **int** |  | 
**chunk_overlap** | **int** |  | 
**failed_reason** | **str** |  | [optional] 
**status** | **str** |  | 

## Example

```python
from openapi_client.models.embedding_task_response import EmbeddingTaskResponse

# TODO update the JSON string below
json = "{}"
# create an instance of EmbeddingTaskResponse from a JSON string
embedding_task_response_instance = EmbeddingTaskResponse.from_json(json)
# print the JSON string representation of the object
print(EmbeddingTaskResponse.to_json())

# convert the object into a dict
embedding_task_response_dict = embedding_task_response_instance.to_dict()
# create an instance of EmbeddingTaskResponse from a dict
embedding_task_response_from_dict = EmbeddingTaskResponse.from_dict(embedding_task_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


