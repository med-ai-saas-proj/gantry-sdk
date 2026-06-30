# InputContentUrlSource

URL-referenced source.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'url']
**value** | **str** |  | 
**mime_type** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.input_content_url_source import InputContentUrlSource

# TODO update the JSON string below
json = "{}"
# create an instance of InputContentUrlSource from a JSON string
input_content_url_source_instance = InputContentUrlSource.from_json(json)
# print the JSON string representation of the object
print(InputContentUrlSource.to_json())

# convert the object into a dict
input_content_url_source_dict = input_content_url_source_instance.to_dict()
# create an instance of InputContentUrlSource from a dict
input_content_url_source_from_dict = InputContentUrlSource.from_dict(input_content_url_source_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


