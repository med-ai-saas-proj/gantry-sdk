# HTMLHeaderTextSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**headers_to_split_on** | **List[List[object]]** |  | [optional] 
**return_each_element** | **bool** |  | [optional] 

## Example

```python
from openapi_client.models.html_header_text_splitter_options import HTMLHeaderTextSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of HTMLHeaderTextSplitterOptions from a JSON string
html_header_text_splitter_options_instance = HTMLHeaderTextSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(HTMLHeaderTextSplitterOptions.to_json())

# convert the object into a dict
html_header_text_splitter_options_dict = html_header_text_splitter_options_instance.to_dict()
# create an instance of HTMLHeaderTextSplitterOptions from a dict
html_header_text_splitter_options_from_dict = HTMLHeaderTextSplitterOptions.from_dict(html_header_text_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


