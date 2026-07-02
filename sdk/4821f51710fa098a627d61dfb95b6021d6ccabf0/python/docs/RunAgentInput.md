# RunAgentInput

Input for running an agent.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**thread_id** | **str** |  | 
**run_id** | **str** |  | 
**parent_run_id** | **str** |  | [optional] 
**state** | **object** |  | 
**messages** | [**List[MessagesInner]**](MessagesInner.md) |  | 
**tools** | [**List[Tool]**](Tool.md) |  | 
**context** | [**List[Context]**](Context.md) |  | 
**forwarded_props** | **object** |  | 

## Example

```python
from openapi_client.models.run_agent_input import RunAgentInput

# TODO update the JSON string below
json = "{}"
# create an instance of RunAgentInput from a JSON string
run_agent_input_instance = RunAgentInput.from_json(json)
# print the JSON string representation of the object
print(RunAgentInput.to_json())

# convert the object into a dict
run_agent_input_dict = run_agent_input_instance.to_dict()
# create an instance of RunAgentInput from a dict
run_agent_input_from_dict = RunAgentInput.from_dict(run_agent_input_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


