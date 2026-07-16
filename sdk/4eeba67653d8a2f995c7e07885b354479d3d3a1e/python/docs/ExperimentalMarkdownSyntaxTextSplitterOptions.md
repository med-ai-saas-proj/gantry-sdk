# ExperimentalMarkdownSyntaxTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**headers_to_split_on** | **List[List[object]]** |  | [optional] 
**return_each_line** | **bool** |  | [optional] 
**strip_headers** | **bool** |  | [optional] 
**custom_header_patterns** | **Dict[str, int]** |  | [optional] 

## Example

```python
from openapi_client.models.experimental_markdown_syntax_text_splitter_options import ExperimentalMarkdownSyntaxTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of ExperimentalMarkdownSyntaxTextSplitterOptions from a JSON string
experimental_markdown_syntax_text_splitter_options_instance = ExperimentalMarkdownSyntaxTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(ExperimentalMarkdownSyntaxTextSplitterOptions.to_json())

# convert the object into a dict
experimental_markdown_syntax_text_splitter_options_dict = experimental_markdown_syntax_text_splitter_options_instance.to_dict()
# create an instance of ExperimentalMarkdownSyntaxTextSplitterOptions from a dict
experimental_markdown_syntax_text_splitter_options_from_dict = ExperimentalMarkdownSyntaxTextSplitterOptions.from_dict(experimental_markdown_syntax_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


