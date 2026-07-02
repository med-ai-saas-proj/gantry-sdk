# ResponseAgUiGatewayAiGatewayAgUiModelPost


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'TEXT_MESSAGE_START']
**timestamp** | **int** |  | [optional] 
**raw_event** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message_id** | **str** |  | 
**role** | **str** |  | 
**name** | **str** |  | 
**delta** | **str** |  | 
**tool_call_id** | **str** |  | 
**tool_call_name** | **str** |  | 
**parent_message_id** | **str** |  | [optional] 
**content** | **object** |  | 
**title** | **str** |  | [optional] 
**snapshot** | **object** |  | 
**messages** | [**List[MessagesInner]**](MessagesInner.md) |  | 
**activity_type** | **str** |  | 
**replace** | **bool** |  | [optional] [default to True]
**patch** | **List[object]** |  | 
**event** | **object** |  | 
**source** | **str** |  | [optional] 
**value** | **object** |  | 
**thread_id** | **str** |  | 
**run_id** | **str** |  | 
**parent_run_id** | **str** |  | [optional] 
**input** | [**RunAgentInput**](RunAgentInput.md) |  | [optional] 
**result** | [**AnyOf**](AnyOf.md) |  | [optional] 
**message** | **str** |  | 
**code** | **str** |  | [optional] 
**step_name** | **str** |  | 
**subtype** | **str** |  | 
**entity_id** | **str** |  | 
**encrypted_value** | **str** |  | 

## Example

```python
from openapi_client.models.response_ag_ui_gateway_ai_gateway_ag_ui_model_post import ResponseAgUiGatewayAiGatewayAgUiModelPost

# TODO update the JSON string below
json = "{}"
# create an instance of ResponseAgUiGatewayAiGatewayAgUiModelPost from a JSON string
response_ag_ui_gateway_ai_gateway_ag_ui_model_post_instance = ResponseAgUiGatewayAiGatewayAgUiModelPost.from_json(json)
# print the JSON string representation of the object
print(ResponseAgUiGatewayAiGatewayAgUiModelPost.to_json())

# convert the object into a dict
response_ag_ui_gateway_ai_gateway_ag_ui_model_post_dict = response_ag_ui_gateway_ai_gateway_ag_ui_model_post_instance.to_dict()
# create an instance of ResponseAgUiGatewayAiGatewayAgUiModelPost from a dict
response_ag_ui_gateway_ai_gateway_ag_ui_model_post_from_dict = ResponseAgUiGatewayAiGatewayAgUiModelPost.from_dict(response_ag_ui_gateway_ai_gateway_ag_ui_model_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


