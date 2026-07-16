# MessagesSnapshotEvent

Event containing a snapshot of the messages.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'MESSAGES_SNAPSHOT']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**messages** | [**List[MessagesInner]**](MessagesInner.md) |  | 

## Example

```python
from openapi_client.models.messages_snapshot_event import MessagesSnapshotEvent

# TODO update the JSON string below
json = "{}"
# create an instance of MessagesSnapshotEvent from a JSON string
messages_snapshot_event_instance = MessagesSnapshotEvent.from_json(json)
# print the JSON string representation of the object
print(MessagesSnapshotEvent.to_json())

# convert the object into a dict
messages_snapshot_event_dict = messages_snapshot_event_instance.to_dict()
# create an instance of MessagesSnapshotEvent from a dict
messages_snapshot_event_from_dict = MessagesSnapshotEvent.from_dict(messages_snapshot_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


