# TokenTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**encoding_name** | **str** |  | [optional] 
**model_name** | **str** |  | [optional] 
**allowed_special** | [**AllowedSpecial**](AllowedSpecial.md) |  | [optional] 
**disallowed_special** | [**DisallowedSpecial**](DisallowedSpecial.md) |  | [optional] 
**chunk_size** | **int** |  | [optional] 
**chunk_overlap** | **int** |  | [optional] 

## Example

```python
from openapi_client.models.token_text_splitter_options import TokenTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of TokenTextSplitterOptions from a JSON string
token_text_splitter_options_instance = TokenTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(TokenTextSplitterOptions.to_json())

# convert the object into a dict
token_text_splitter_options_dict = token_text_splitter_options_instance.to_dict()
# create an instance of TokenTextSplitterOptions from a dict
token_text_splitter_options_from_dict = TokenTextSplitterOptions.from_dict(token_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


