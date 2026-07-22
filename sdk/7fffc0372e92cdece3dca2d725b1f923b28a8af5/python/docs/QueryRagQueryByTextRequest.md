# QueryRagQueryByTextRequest

DTO for querying RAG embeddings by text.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**query_text** | **str** |  | 
**top_k** | **int** |  | [optional] [default to 5]
**filters** | [**Filters**](Filters.md) |  | [optional] 
**hybrid_search** | **bool** | Whether to perform a hybrid search that combines vector similarity and BM25 text search. If true, the service will first use BM25 + semantic search to filter candidates and then rerank them using vector similarity. | [optional] [default to False]
**hybrid_search_bm25_top_k** | **int** | When hybrid_search is true, this parameter controls the number of top candidates to retrieve using BM25 before reranking with vector similarity. A higher value may improve recall but increase latency. | [optional] [default to 5]
**hybrid_search_semantic_top_k** | **int** | When hybrid_search is true, this parameter controls the number of top candidates to retrieve using semantic search before reranking with vector similarity. A higher value may improve recall but increase latency. | [optional] [default to 5]
**hybrid_search_bm25_lang** | **str** | When hybrid_search is true, this parameter specifies the language to use for BM25 search. This can affect tokenization and stopword removal, which in turn can impact search results. The default &#39;simple&#39; option applies basic tokenization and is suitable for many languages, but you may want to specify a particular language for better results with certain languages. | [optional] [default to 'simple']

## Example

```python
from openapi_client.models.query_rag_query_by_text_request import QueryRagQueryByTextRequest

# TODO update the JSON string below
json = "{}"
# create an instance of QueryRagQueryByTextRequest from a JSON string
query_rag_query_by_text_request_instance = QueryRagQueryByTextRequest.from_json(json)
# print the JSON string representation of the object
print(QueryRagQueryByTextRequest.to_json())

# convert the object into a dict
query_rag_query_by_text_request_dict = query_rag_query_by_text_request_instance.to_dict()
# create an instance of QueryRagQueryByTextRequest from a dict
query_rag_query_by_text_request_from_dict = QueryRagQueryByTextRequest.from_dict(query_rag_query_by_text_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


