# BinaryInputContent

A deprecated binary payload reference in a multimodal user message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'binary']
**mime_type** | **str** |  | 
**id** | **str** |  | [optional] 
**url** | **str** |  | [optional] 
**data** | **str** |  | [optional] 
**filename** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.binary_input_content import BinaryInputContent

# TODO update the JSON string below
json = "{}"
# create an instance of BinaryInputContent from a JSON string
binary_input_content_instance = BinaryInputContent.from_json(json)
# print the JSON string representation of the object
print(BinaryInputContent.to_json())

# convert the object into a dict
binary_input_content_dict = binary_input_content_instance.to_dict()
# create an instance of BinaryInputContent from a dict
binary_input_content_from_dict = BinaryInputContent.from_dict(binary_input_content_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


