# PostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKeyUuid** | **string** |  | 
**Amount** | [**ScaledAmount**](ScaledAmount.md) |  | 
**Details** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**Capture** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewPostRequest

`func NewPostRequest(apiKeyUuid string, amount ScaledAmount, ) *PostRequest`

NewPostRequest instantiates a new PostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostRequestWithDefaults

`func NewPostRequestWithDefaults() *PostRequest`

NewPostRequestWithDefaults instantiates a new PostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKeyUuid

`func (o *PostRequest) GetApiKeyUuid() string`

GetApiKeyUuid returns the ApiKeyUuid field if non-nil, zero value otherwise.

### GetApiKeyUuidOk

`func (o *PostRequest) GetApiKeyUuidOk() (*string, bool)`

GetApiKeyUuidOk returns a tuple with the ApiKeyUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKeyUuid

`func (o *PostRequest) SetApiKeyUuid(v string)`

SetApiKeyUuid sets ApiKeyUuid field to given value.


### GetAmount

`func (o *PostRequest) GetAmount() ScaledAmount`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PostRequest) GetAmountOk() (*ScaledAmount, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PostRequest) SetAmount(v ScaledAmount)`

SetAmount sets Amount field to given value.


### GetDetails

`func (o *PostRequest) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *PostRequest) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *PostRequest) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *PostRequest) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetCapture

`func (o *PostRequest) GetCapture() bool`

GetCapture returns the Capture field if non-nil, zero value otherwise.

### GetCaptureOk

`func (o *PostRequest) GetCaptureOk() (*bool, bool)`

GetCaptureOk returns a tuple with the Capture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapture

`func (o *PostRequest) SetCapture(v bool)`

SetCapture sets Capture field to given value.

### HasCapture

`func (o *PostRequest) HasCapture() bool`

HasCapture returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


