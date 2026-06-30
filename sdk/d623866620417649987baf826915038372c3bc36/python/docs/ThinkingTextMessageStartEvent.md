# ThinkingTextMessageStartEvent

Event indicating the start of a thinking text message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'THINKING_TEXT_MESSAGE_START']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 

## Example

```python
from openapi_client.models.thinking_text_message_start_event import ThinkingTextMessageStartEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ThinkingTextMessageStartEvent from a JSON string
thinking_text_message_start_event_instance = ThinkingTextMessageStartEvent.from_json(json)
# print the JSON string representation of the object
print(ThinkingTextMessageStartEvent.to_json())

# convert the object into a dict
thinking_text_message_start_event_dict = thinking_text_message_start_event_instance.to_dict()
# create an instance of ThinkingTextMessageStartEvent from a dict
thinking_text_message_start_event_from_dict = ThinkingTextMessageStartEvent.from_dict(thinking_text_message_start_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


