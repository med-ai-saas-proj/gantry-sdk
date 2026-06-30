# AddRagFileRequest

DTO for adding a file (with embedding) to a RAG bucket.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_uid** | **UUID** |  | 
**lang** | **str** |  | [optional] [default to 'simple']
**chunk_splitter** | [**ChunkSplitterType**](ChunkSplitterType.md) |  | [optional] 
**chunk_splitter_options** | [**ChunkSplitterOptions**](ChunkSplitterOptions.md) |  | [optional] 
**chunk_size** | **int** |  | [optional] [default to 1000]
**chunk_overlap** | **int** |  | [optional] [default to 150]

## Example

```python
from openapi_client.models.add_rag_file_request import AddRagFileRequest

# TODO update the JSON string below
json = "{}"
# create an instance of AddRagFileRequest from a JSON string
add_rag_file_request_instance = AddRagFileRequest.from_json(json)
# print the JSON string representation of the object
print(AddRagFileRequest.to_json())

# convert the object into a dict
add_rag_file_request_dict = add_rag_file_request_instance.to_dict()
# create an instance of AddRagFileRequest from a dict
add_rag_file_request_from_dict = AddRagFileRequest.from_dict(add_rag_file_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


