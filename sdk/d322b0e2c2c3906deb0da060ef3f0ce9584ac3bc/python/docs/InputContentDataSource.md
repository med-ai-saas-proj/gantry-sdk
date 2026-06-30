# InputContentDataSource

Inline base64-encoded source.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'data']
**value** | **str** |  | 
**mime_type** | **str** |  | 

## Example

```python
from openapi_client.models.input_content_data_source import InputContentDataSource

# TODO update the JSON string below
json = "{}"
# create an instance of InputContentDataSource from a JSON string
input_content_data_source_instance = InputContentDataSource.from_json(json)
# print the JSON string representation of the object
print(InputContentDataSource.to_json())

# convert the object into a dict
input_content_data_source_dict = input_content_data_source_instance.to_dict()
# create an instance of InputContentDataSource from a dict
input_content_data_source_from_dict = InputContentDataSource.from_dict(input_content_data_source_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


