# StepFinishedEvent

Event indicating that a step has finished.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'STEP_FINISHED']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**step_name** | **str** |  | 

## Example

```python
from openapi_client.models.step_finished_event import StepFinishedEvent

# TODO update the JSON string below
json = "{}"
# create an instance of StepFinishedEvent from a JSON string
step_finished_event_instance = StepFinishedEvent.from_json(json)
# print the JSON string representation of the object
print(StepFinishedEvent.to_json())

# convert the object into a dict
step_finished_event_dict = step_finished_event_instance.to_dict()
# create an instance of StepFinishedEvent from a dict
step_finished_event_from_dict = StepFinishedEvent.from_dict(step_finished_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


