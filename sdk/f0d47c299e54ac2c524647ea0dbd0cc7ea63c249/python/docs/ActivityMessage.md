# ActivityMessage

An activity progress message emitted between chat messages.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**role** | **str** |  | [optional] [default to 'activity']
**activity_type** | **str** |  | 
**content** | **Dict[str, object]** |  | 

## Example

```python
from openapi_client.models.activity_message import ActivityMessage

# TODO update the JSON string below
json = "{}"
# create an instance of ActivityMessage from a JSON string
activity_message_instance = ActivityMessage.from_json(json)
# print the JSON string representation of the object
print(ActivityMessage.to_json())

# convert the object into a dict
activity_message_dict = activity_message_instance.to_dict()
# create an instance of ActivityMessage from a dict
activity_message_from_dict = ActivityMessage.from_dict(activity_message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


