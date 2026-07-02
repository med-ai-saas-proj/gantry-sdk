# AddTextToRagRequest

DTO for adding text (with embedding) to a RAG bucket without an associated file. This can be used for ad-hoc knowledge that doesn't come from a file.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | [**Text**](Text.md) |  | 
**lang** | **str** |  | [optional] [default to 'simple']
**chunk_splitter** | [**ChunkSplitterType**](ChunkSplitterType.md) |  | [optional] 
**chunk_splitter_options** | [**ChunkSplitterOptions**](ChunkSplitterOptions.md) |  | [optional] 
**chunk_size** | **int** |  | [optional] [default to 1000]
**chunk_overlap** | **int** |  | [optional] [default to 150]
**metadata** | **Dict[str, object]** |  | [optional] 

## Example

```python
from openapi_client.models.add_text_to_rag_request import AddTextToRagRequest

# TODO update the JSON string below
json = "{}"
# create an instance of AddTextToRagRequest from a JSON string
add_text_to_rag_request_instance = AddTextToRagRequest.from_json(json)
# print the JSON string representation of the object
print(AddTextToRagRequest.to_json())

# convert the object into a dict
add_text_to_rag_request_dict = add_text_to_rag_request_instance.to_dict()
# create an instance of AddTextToRagRequest from a dict
add_text_to_rag_request_from_dict = AddTextToRagRequest.from_dict(add_text_to_rag_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


