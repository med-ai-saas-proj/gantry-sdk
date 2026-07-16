# AssistantMessage

An assistant message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**role** | **str** |  | [optional] [default to 'assistant']
**content** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**encrypted_value** | **str** |  | [optional] 
**tool_calls** | [**List[ToolCall]**](ToolCall.md) |  | [optional] 

## Example

```python
from openapi_client.models.assistant_message import AssistantMessage

# TODO update the JSON string below
json = "{}"
# create an instance of AssistantMessage from a JSON string
assistant_message_instance = AssistantMessage.from_json(json)
# print the JSON string representation of the object
print(AssistantMessage.to_json())

# convert the object into a dict
assistant_message_dict = assistant_message_instance.to_dict()
# create an instance of AssistantMessage from a dict
assistant_message_from_dict = AssistantMessage.from_dict(assistant_message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


