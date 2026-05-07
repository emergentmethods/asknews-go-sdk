# RateLimitStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequestRate** | **float32** | Configured tokens replenished per second | 
**RequestRateCapacity** | **float32** | Maximum burst token capacity | 
**RequestRateRemaining** | **float32** | Effective available tokens right now (accounts for time elapsed since last request) | 
**RetryAfter** | Pointer to **NullableFloat32** |  | [optional] 
**ConcurrencyLimit** | **int32** | Maximum allowed concurrent requests | 
**ConcurrencyRemaining** | **int32** | Available concurrent request slots right now | 

## Methods

### NewRateLimitStatusResponse

`func NewRateLimitStatusResponse(requestRate float32, requestRateCapacity float32, requestRateRemaining float32, concurrencyLimit int32, concurrencyRemaining int32, ) *RateLimitStatusResponse`

NewRateLimitStatusResponse instantiates a new RateLimitStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRateLimitStatusResponseWithDefaults

`func NewRateLimitStatusResponseWithDefaults() *RateLimitStatusResponse`

NewRateLimitStatusResponseWithDefaults instantiates a new RateLimitStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequestRate

`func (o *RateLimitStatusResponse) GetRequestRate() float32`

GetRequestRate returns the RequestRate field if non-nil, zero value otherwise.

### GetRequestRateOk

`func (o *RateLimitStatusResponse) GetRequestRateOk() (*float32, bool)`

GetRequestRateOk returns a tuple with the RequestRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestRate

`func (o *RateLimitStatusResponse) SetRequestRate(v float32)`

SetRequestRate sets RequestRate field to given value.


### GetRequestRateCapacity

`func (o *RateLimitStatusResponse) GetRequestRateCapacity() float32`

GetRequestRateCapacity returns the RequestRateCapacity field if non-nil, zero value otherwise.

### GetRequestRateCapacityOk

`func (o *RateLimitStatusResponse) GetRequestRateCapacityOk() (*float32, bool)`

GetRequestRateCapacityOk returns a tuple with the RequestRateCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestRateCapacity

`func (o *RateLimitStatusResponse) SetRequestRateCapacity(v float32)`

SetRequestRateCapacity sets RequestRateCapacity field to given value.


### GetRequestRateRemaining

`func (o *RateLimitStatusResponse) GetRequestRateRemaining() float32`

GetRequestRateRemaining returns the RequestRateRemaining field if non-nil, zero value otherwise.

### GetRequestRateRemainingOk

`func (o *RateLimitStatusResponse) GetRequestRateRemainingOk() (*float32, bool)`

GetRequestRateRemainingOk returns a tuple with the RequestRateRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestRateRemaining

`func (o *RateLimitStatusResponse) SetRequestRateRemaining(v float32)`

SetRequestRateRemaining sets RequestRateRemaining field to given value.


### GetRetryAfter

`func (o *RateLimitStatusResponse) GetRetryAfter() float32`

GetRetryAfter returns the RetryAfter field if non-nil, zero value otherwise.

### GetRetryAfterOk

`func (o *RateLimitStatusResponse) GetRetryAfterOk() (*float32, bool)`

GetRetryAfterOk returns a tuple with the RetryAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryAfter

`func (o *RateLimitStatusResponse) SetRetryAfter(v float32)`

SetRetryAfter sets RetryAfter field to given value.

### HasRetryAfter

`func (o *RateLimitStatusResponse) HasRetryAfter() bool`

HasRetryAfter returns a boolean if a field has been set.

### SetRetryAfterNil

`func (o *RateLimitStatusResponse) SetRetryAfterNil(b bool)`

 SetRetryAfterNil sets the value for RetryAfter to be an explicit nil

### UnsetRetryAfter
`func (o *RateLimitStatusResponse) UnsetRetryAfter()`

UnsetRetryAfter ensures that no value is present for RetryAfter, not even an explicit nil
### GetConcurrencyLimit

`func (o *RateLimitStatusResponse) GetConcurrencyLimit() int32`

GetConcurrencyLimit returns the ConcurrencyLimit field if non-nil, zero value otherwise.

### GetConcurrencyLimitOk

`func (o *RateLimitStatusResponse) GetConcurrencyLimitOk() (*int32, bool)`

GetConcurrencyLimitOk returns a tuple with the ConcurrencyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConcurrencyLimit

`func (o *RateLimitStatusResponse) SetConcurrencyLimit(v int32)`

SetConcurrencyLimit sets ConcurrencyLimit field to given value.


### GetConcurrencyRemaining

`func (o *RateLimitStatusResponse) GetConcurrencyRemaining() int32`

GetConcurrencyRemaining returns the ConcurrencyRemaining field if non-nil, zero value otherwise.

### GetConcurrencyRemainingOk

`func (o *RateLimitStatusResponse) GetConcurrencyRemainingOk() (*int32, bool)`

GetConcurrencyRemainingOk returns a tuple with the ConcurrencyRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConcurrencyRemaining

`func (o *RateLimitStatusResponse) SetConcurrencyRemaining(v int32)`

SetConcurrencyRemaining sets ConcurrencyRemaining field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


