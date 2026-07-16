# RecursiveJsonSplitterOptions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**max_chunk_size** | **int** |  | [optional] 
**min_chunk_size** | **int** |  | [optional] 
**convert_lists** | **bool** |  | [optional] 

## Example

```python
from openapi_client.models.recursive_json_splitter_options import RecursiveJsonSplitterOptions

# TODO update the JSON string below
json = "{}"
# create an instance of RecursiveJsonSplitterOptions from a JSON string
recursive_json_splitter_options_instance = RecursiveJsonSplitterOptions.from_json(json)
# print the JSON string representation of the object
print(RecursiveJsonSplitterOptions.to_json())

# convert the object into a dict
recursive_json_splitter_options_dict = recursive_json_splitter_options_instance.to_dict()
# create an instance of RecursiveJsonSplitterOptions from a dict
recursive_json_splitter_options_from_dict = RecursiveJsonSplitterOptions.from_dict(recursive_json_splitter_options_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


