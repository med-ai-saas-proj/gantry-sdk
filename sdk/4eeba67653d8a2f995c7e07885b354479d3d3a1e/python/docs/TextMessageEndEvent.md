# TextMessageEndEvent

Event indicating the end of a text message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TEXT_MESSAGE_END']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 

## Example

```python
from openapi_client.models.text_message_end_event import TextMessageEndEvent

# TODO update the JSON string below
json = "{}"
# create an instance of TextMessageEndEvent from a JSON string
text_message_end_event_instance = TextMessageEndEvent.from_json(json)
# print the JSON string representation of the object
print(TextMessageEndEvent.to_json())

# convert the object into a dict
text_message_end_event_dict = text_message_end_event_instance.to_dict()
# create an instance of TextMessageEndEvent from a dict
text_message_end_event_from_dict = TextMessageEndEvent.from_dict(text_message_end_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


