# CharacterTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**separator** | **str** |  | [optional] 
**is_separator_regex** | **bool** |  | [optional] 
**chunk_size** | **int** |  | [optional] 
**chunk_overlap** | **int** |  | [optional] 
**keep_separator** | [**KeepSeparator**](KeepSeparator.md) |  | [optional] 

## Example

```python
from openapi_client.models.character_text_splitter_options import CharacterTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of CharacterTextSplitterOptions from a JSON string
character_text_splitter_options_instance = CharacterTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(CharacterTextSplitterOptions.to_json())

# convert the object into a dict
character_text_splitter_options_dict = character_text_splitter_options_instance.to_dict()
# create an instance of CharacterTextSplitterOptions from a dict
character_text_splitter_options_from_dict = CharacterTextSplitterOptions.from_dict(character_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


