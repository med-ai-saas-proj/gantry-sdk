# ToolCallResultEvent

Event containing the result of a tool call.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TOOL_CALL_RESULT']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 
**tool_call_id** | **str** |  | 
**content** | **str** |  | 
**role** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.tool_call_result_event import ToolCallResultEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ToolCallResultEvent from a JSON string
tool_call_result_event_instance = ToolCallResultEvent.from_json(json)
# print the JSON string representation of the object
print(ToolCallResultEvent.to_json())

# convert the object into a dict
tool_call_result_event_dict = tool_call_result_event_instance.to_dict()
# create an instance of ToolCallResultEvent from a dict
tool_call_result_event_from_dict = ToolCallResultEvent.from_dict(tool_call_result_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


