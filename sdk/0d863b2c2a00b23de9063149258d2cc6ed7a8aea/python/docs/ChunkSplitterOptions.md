# ChunkSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**separator** | **str** |  | [optional] 
**is_separator_regex** | **bool** |  | [optional] 
**chunk_size** | **int** |  | [optional] 
**chunk_overlap** | **int** |  | [optional] 
**keep_separator** | [**KeepSeparator**](KeepSeparator.md) |  | [optional] 
**separators** | **List[str]** |  | [optional] 
**encoding_name** | **str** |  | [optional] 
**model_name** | **str** |  | [optional] 
**allowed_special** | [**AllowedSpecial**](AllowedSpecial.md) |  | [optional] 
**disallowed_special** | [**DisallowedSpecial**](DisallowedSpecial.md) |  | [optional] 
**headers_to_split_on** | **List[List[object]]** |  | [optional] 
**return_each_line** | **bool** |  | [optional] 
**strip_headers** | **bool** |  | [optional] 
**custom_header_patterns** | **Dict[str, int]** |  | [optional] 
**return_each_element** | **bool** |  | [optional] 
**max_chunk_size** | **int** |  | [optional] 
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
**min_chunk_size** | **int** |  | [optional] 
**convert_lists** | **bool** |  | [optional] 
**language** | **str** |  | [optional] 
**use_span_tokenize** | **bool** |  | [optional] 
**pipeline** | **str** |  | [optional] 
**max_length** | **int** |  | [optional] 
**strip_whitespace** | **bool** |  | [optional] 
**tokens_per_chunk** | **int** |  | [optional] 
**model_kwargs** | **Dict[str, object]** |  | [optional] 

## Example

```python
from openapi_client.models.chunk_splitter_options import ChunkSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of ChunkSplitterOptions from a JSON string
chunk_splitter_options_instance = ChunkSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(ChunkSplitterOptions.to_json())

# convert the object into a dict
chunk_splitter_options_dict = chunk_splitter_options_instance.to_dict()
# create an instance of ChunkSplitterOptions from a dict
chunk_splitter_options_from_dict = ChunkSplitterOptions.from_dict(chunk_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


