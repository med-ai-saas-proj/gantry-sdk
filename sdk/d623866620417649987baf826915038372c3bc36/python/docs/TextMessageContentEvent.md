# TextMessageContentEvent

Event containing a piece of text message content.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TEXT_MESSAGE_CONTENT']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 
**delta** | **str** |  | 

## Example

```python
from openapi_client.models.text_message_content_event import TextMessageContentEvent

# TODO update the JSON string below
json = "{}"
# create an instance of TextMessageContentEvent from a JSON string
text_message_content_event_instance = TextMessageContentEvent.from_json(json)
# print the JSON string representation of the object
print(TextMessageContentEvent.to_json())

# convert the object into a dict
text_message_content_event_dict = text_message_content_event_instance.to_dict()
# create an instance of TextMessageContentEvent from a dict
text_message_content_event_from_dict = TextMessageContentEvent.from_dict(text_message_content_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


