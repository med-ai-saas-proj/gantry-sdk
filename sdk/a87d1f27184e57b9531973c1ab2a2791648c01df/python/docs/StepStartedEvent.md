# StepStartedEvent

Event indicating that a step has started.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'STEP_STARTED']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**step_name** | **str** |  | 

## Example

```python
from openapi_client.models.step_started_event import StepStartedEvent

# TODO update the JSON string below
json = "{}"
# create an instance of StepStartedEvent from a JSON string
step_started_event_instance = StepStartedEvent.from_json(json)
# print the JSON string representation of the object
print(StepStartedEvent.to_json())

# convert the object into a dict
step_started_event_dict = step_started_event_instance.to_dict()
# create an instance of StepStartedEvent from a dict
step_started_event_from_dict = StepStartedEvent.from_dict(step_started_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


