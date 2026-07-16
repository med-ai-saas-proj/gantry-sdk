# SpacyTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**separator** | **str** |  | [optional] 
**pipeline** | **str** |  | [optional] 
**max_length** | **int** |  | [optional] 
**strip_whitespace** | **bool** |  | [optional] 
**chunk_size** | **int** |  | [optional] 
**chunk_overlap** | **int** |  | [optional] 

## Example

```python
from openapi_client.models.spacy_text_splitter_options import SpacyTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of SpacyTextSplitterOptions from a JSON string
spacy_text_splitter_options_instance = SpacyTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(SpacyTextSplitterOptions.to_json())

# convert the object into a dict
spacy_text_splitter_options_dict = spacy_text_splitter_options_instance.to_dict()
# create an instance of SpacyTextSplitterOptions from a dict
spacy_text_splitter_options_from_dict = SpacyTextSplitterOptions.from_dict(spacy_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


