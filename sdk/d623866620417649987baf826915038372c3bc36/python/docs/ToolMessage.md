# ToolMessage

A tool result message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**role** | **str** |  | [optional] [default to 'tool']
**content** | **str** |  | 
**tool_call_id** | **str** |  | 
**error** | **str** |  | [optional] 
**encrypted_value** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.tool_message import ToolMessage

# TODO update the JSON string below
json = "{}"
# create an instance of ToolMessage from a JSON string
tool_message_instance = ToolMessage.from_json(json)
# print the JSON string representation of the object
print(ToolMessage.to_json())

# convert the object into a dict
tool_message_dict = tool_message_instance.to_dict()
# create an instance of ToolMessage from a dict
tool_message_from_dict = ToolMessage.from_dict(tool_message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


