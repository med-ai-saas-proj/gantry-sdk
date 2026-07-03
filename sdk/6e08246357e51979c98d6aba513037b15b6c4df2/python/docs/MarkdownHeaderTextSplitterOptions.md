# MarkdownHeaderTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**headers_to_split_on** | **List[List[object]]** |  | [optional] 
**return_each_line** | **bool** |  | [optional] 
**strip_headers** | **bool** |  | [optional] 
**custom_header_patterns** | **Dict[str, int]** |  | [optional] 

## Example

```python
from openapi_client.models.markdown_header_text_splitter_options import MarkdownHeaderTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of MarkdownHeaderTextSplitterOptions from a JSON string
markdown_header_text_splitter_options_instance = MarkdownHeaderTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(MarkdownHeaderTextSplitterOptions.to_json())

# convert the object into a dict
markdown_header_text_splitter_options_dict = markdown_header_text_splitter_options_instance.to_dict()
# create an instance of MarkdownHeaderTextSplitterOptions from a dict
markdown_header_text_splitter_options_from_dict = MarkdownHeaderTextSplitterOptions.from_dict(markdown_header_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


