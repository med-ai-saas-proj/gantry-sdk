# ActivityMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Role** | Pointer to **string** |  | [optional] [default to "activity"]
**ActivityType** | **string** |  | 
**Content** | **map[string]interface{}** |  | 

## Methods

### NewActivityMessage

`func NewActivityMessage(id string, activityType string, content map[string]interface{}, ) *ActivityMessage`

NewActivityMessage instantiates a new ActivityMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityMessageWithDefaults

`func NewActivityMessageWithDefaults() *ActivityMessage`

NewActivityMessageWithDefaults instantiates a new ActivityMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ActivityMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ActivityMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ActivityMessage) SetId(v string)`

SetId sets Id field to given value.


### GetRole

`func (o *ActivityMessage) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ActivityMessage) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ActivityMessage) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *ActivityMessage) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetActivityType

`func (o *ActivityMessage) GetActivityType() string`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ActivityMessage) GetActivityTypeOk() (*string, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ActivityMessage) SetActivityType(v string)`

SetActivityType sets ActivityType field to given value.


### GetContent

`func (o *ActivityMessage) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ActivityMessage) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ActivityMessage) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


