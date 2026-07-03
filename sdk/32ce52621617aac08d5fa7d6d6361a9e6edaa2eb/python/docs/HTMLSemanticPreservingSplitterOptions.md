# HTMLSemanticPreservingSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**headers_to_split_on** | **List[List[object]]** |  | [optional] 
**max_chunk_size** | **int** |  | [optional] 
**chunk_overlap** | **int** |  | [optional] 
**separators** | **List[str]** |  | [optional] 
**elements_to_preserve** | **List[str]** |  | [optional] 
**preserve_links** | **bool** |  | [optional] 
**preserve_images** | **bool** |  | [optional] 
**preserve_videos** | **bool** |  | [optional] 
**preserve_audio** | **bool** |  | [optional] 
**custom_handlers** | **Dict[str, object]** |  | [optional] 
**stopword_removal** | **bool** |  | [optional] 
**stopword_lang** | **str** |  | [optional] 
**normalize_text** | **bool** |  | [optional] 
**external_metadata** | **Dict[str, str]** |  | [optional] 
**allowlist_tags** | **List[str]** |  | [optional] 
**denylist_tags** | **List[str]** |  | [optional] 
**preserve_parent_metadata** | **bool** |  | [optional] 
**keep_separator** | [**KeepSeparator**](KeepSeparator.md) |  | [optional] 

## Example

```python
from openapi_client.models.html_semantic_preserving_splitter_options import HTMLSemanticPreservingSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of HTMLSemanticPreservingSplitterOptions from a JSON string
html_semantic_preserving_splitter_options_instance = HTMLSemanticPreservingSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(HTMLSemanticPreservingSplitterOptions.to_json())

# convert the object into a dict
html_semantic_preserving_splitter_options_dict = html_semantic_preserving_splitter_options_instance.to_dict()
# create an instance of HTMLSemanticPreservingSplitterOptions from a dict
html_semantic_preserving_splitter_options_from_dict = HTMLSemanticPreservingSplitterOptions.from_dict(html_semantic_preserving_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


