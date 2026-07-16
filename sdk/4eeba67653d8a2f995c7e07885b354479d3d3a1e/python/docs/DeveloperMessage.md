# DeveloperMessage

A developer message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**role** | **str** |  | [optional] [default to 'developer']
**content** | **str** |  | 
**name** | **str** |  | [optional] 
**encrypted_value** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.developer_message import DeveloperMessage

# TODO update the JSON string below
json = "{}"
# create an instance of DeveloperMessage from a JSON string
developer_message_instance = DeveloperMessage.from_json(json)
# print the JSON string representation of the object
print(DeveloperMessage.to_json())

# convert the object into a dict
developer_message_dict = developer_message_instance.to_dict()
# create an instance of DeveloperMessage from a dict
developer_message_from_dict = DeveloperMessage.from_dict(developer_message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


