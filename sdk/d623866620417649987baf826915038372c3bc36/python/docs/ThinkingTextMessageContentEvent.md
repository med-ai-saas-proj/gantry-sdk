# ThinkingTextMessageContentEvent

Event indicating a piece of a thinking text message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'THINKING_TEXT_MESSAGE_CONTENT']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**delta** | **str** |  | 

## Example

```python
from openapi_client.models.thinking_text_message_content_event import ThinkingTextMessageContentEvent

# TODO update the JSON string below
json = "{}"
# create an instance of ThinkingTextMessageContentEvent from a JSON string
thinking_text_message_content_event_instance = ThinkingTextMessageContentEvent.from_json(json)
# print the JSON string representation of the object
print(ThinkingTextMessageContentEvent.to_json())

# convert the object into a dict
thinking_text_message_content_event_dict = thinking_text_message_content_event_instance.to_dict()
# create an instance of ThinkingTextMessageContentEvent from a dict
thinking_text_message_content_event_from_dict = ThinkingTextMessageContentEvent.from_dict(thinking_text_message_content_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


