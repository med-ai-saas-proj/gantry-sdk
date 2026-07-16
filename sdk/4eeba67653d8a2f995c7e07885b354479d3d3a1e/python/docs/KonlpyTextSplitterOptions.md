# KonlpyTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**separator** | **str** |  | [optional] 
**chunk_size** | **int** |  | [optional] 
**chunk_overlap** | **int** |  | [optional] 

## Example

```python
from openapi_client.models.konlpy_text_splitter_options import KonlpyTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of KonlpyTextSplitterOptions from a JSON string
konlpy_text_splitter_options_instance = KonlpyTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(KonlpyTextSplitterOptions.to_json())

# convert the object into a dict
konlpy_text_splitter_options_dict = konlpy_text_splitter_options_instance.to_dict()
# create an instance of KonlpyTextSplitterOptions from a dict
konlpy_text_splitter_options_from_dict = KonlpyTextSplitterOptions.from_dict(konlpy_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


