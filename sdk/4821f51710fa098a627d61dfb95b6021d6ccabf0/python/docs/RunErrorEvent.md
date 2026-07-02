# RunErrorEvent

Event indicating that a run has encountered an error.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'RUN_ERROR']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message** | **str** |  | 
**code** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.run_error_event import RunErrorEvent

# TODO update the JSON string below
json = "{}"
# create an instance of RunErrorEvent from a JSON string
run_error_event_instance = RunErrorEvent.from_json(json)
# print the JSON string representation of the object
print(RunErrorEvent.to_json())

# convert the object into a dict
run_error_event_dict = run_error_event_instance.to_dict()
# create an instance of RunErrorEvent from a dict
run_error_event_from_dict = RunErrorEvent.from_dict(run_error_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


