# TextMessageStartEvent

Event indicating the start of a text message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TEXT_MESSAGE_START']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 
**role** | **str** |  | [optional] [default to 'assistant']
**name** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.text_message_start_event import TextMessageStartEvent

# TODO update the JSON string below
json = "{}"
# create an instance of TextMessageStartEvent from a JSON string
text_message_start_event_instance = TextMessageStartEvent.from_json(json)
# print the JSON string representation of the object
print(TextMessageStartEvent.to_json())

# convert the object into a dict
text_message_start_event_dict = text_message_start_event_instance.to_dict()
# create an instance of TextMessageStartEvent from a dict
text_message_start_event_from_dict = TextMessageStartEvent.from_dict(text_message_start_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


