# ReasoningMessage

A reasoning message containing the agent's internal reasoning process.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**role** | **str** |  | [optional] [default to 'reasoning']
**content** | **str** |  | 
**encrypted_value** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.reasoning_message import ReasoningMessage

# TODO update the JSON string below
json = "{}"
# create an instance of ReasoningMessage from a JSON string
reasoning_message_instance = ReasoningMessage.from_json(json)
# print the JSON string representation of the object
print(ReasoningMessage.to_json())

# convert the object into a dict
reasoning_message_dict = reasoning_message_instance.to_dict()
# create an instance of ReasoningMessage from a dict
reasoning_message_from_dict = ReasoningMessage.from_dict(reasoning_message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


