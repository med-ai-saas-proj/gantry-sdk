# SentenceTransformersTokenTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chunk_overlap** | **int** |  | [optional] 
**model_name** | **str** |  | [optional] 
**tokens_per_chunk** | **int** |  | [optional] 
**model_kwargs** | **Dict[str, object]** |  | [optional] 
**chunk_size** | **int** |  | [optional] 

## Example

```python
from openapi_client.models.sentence_transformers_token_text_splitter_options import SentenceTransformersTokenTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of SentenceTransformersTokenTextSplitterOptions from a JSON string
sentence_transformers_token_text_splitter_options_instance = SentenceTransformersTokenTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(SentenceTransformersTokenTextSplitterOptions.to_json())

# convert the object into a dict
sentence_transformers_token_text_splitter_options_dict = sentence_transformers_token_text_splitter_options_instance.to_dict()
# create an instance of SentenceTransformersTokenTextSplitterOptions from a dict
sentence_transformers_token_text_splitter_options_from_dict = SentenceTransformersTokenTextSplitterOptions.from_dict(sentence_transformers_token_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


