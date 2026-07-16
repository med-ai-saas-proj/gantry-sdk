# MarkdownTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**separators** | **List[str]** |  | [optional] 
**keep_separator** | [**KeepSeparator**](KeepSeparator.md) |  | [optional] 
**is_separator_regex** | **bool** |  | [optional] 
**chunk_size** | **int** |  | [optional] 
**chunk_overlap** | **int** |  | [optional] 

## Example

```python
from openapi_client.models.markdown_text_splitter_options import MarkdownTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of MarkdownTextSplitterOptions from a JSON string
markdown_text_splitter_options_instance = MarkdownTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(MarkdownTextSplitterOptions.to_json())

# convert the object into a dict
markdown_text_splitter_options_dict = markdown_text_splitter_options_instance.to_dict()
# create an instance of MarkdownTextSplitterOptions from a dict
markdown_text_splitter_options_from_dict = MarkdownTextSplitterOptions.from_dict(markdown_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


