# RagQueryResponse

DTO for RAG query response.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_info** | [**FileInfoResponse**](FileInfoResponse.md) |  | 
**text** | **str** |  | 
**embedding** | **List[float]** |  | 
**created_at** | **datetime** |  | 
**metadata** | **Dict[str, object]** |  | [optional] 
**vector_distance** | **float** |  | [optional] 
**bm25_score** | **float** |  | [optional] 
**rerank_score** | **float** |  | [optional] 

## Example

```python
from openapi_client.models.rag_query_response import RagQueryResponse

# TODO update the JSON string below
json = "{}"
# create an instance of RagQueryResponse from a JSON string
rag_query_response_instance = RagQueryResponse.from_json(json)
# print the JSON string representation of the object
print(RagQueryResponse.to_json())

# convert the object into a dict
rag_query_response_dict = rag_query_response_instance.to_dict()
# create an instance of RagQueryResponse from a dict
rag_query_response_from_dict = RagQueryResponse.from_dict(rag_query_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


