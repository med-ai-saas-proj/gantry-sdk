# NLTKTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**separator** | **str** |  | [optional] 
**language** | **str** |  | [optional] 
**use_span_tokenize** | **bool** |  | [optional] 
**chunk_size** | **int** |  | [optional] 
**chunk_overlap** | **int** |  | [optional] 

## Example

```python
from openapi_client.models.nltk_text_splitter_options import NLTKTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of NLTKTextSplitterOptions from a JSON string
nltk_text_splitter_options_instance = NLTKTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(NLTKTextSplitterOptions.to_json())

# convert the object into a dict
nltk_text_splitter_options_dict = nltk_text_splitter_options_instance.to_dict()
# create an instance of NLTKTextSplitterOptions from a dict
nltk_text_splitter_options_from_dict = NLTKTextSplitterOptions.from_dict(nltk_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


