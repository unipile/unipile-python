# StartAuthIntentRequestAnyOf1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to connect with UniLogin. | 
**account_id** | **str** | The existing LinkedIn, Instagram or Facebook Account to reconnect. Omit it to link a new Account. | [optional] 
**account_scope_id** | **str** | The Scope assigned to a newly linked Account. | [optional] 
**state** | **str** | State data sent in the account.add or account.reconnect webhook after completion. | [optional] 
**config** | [**StartAuthIntentRequestAnyOf1Config**](StartAuthIntentRequestAnyOf1Config.md) |  | [optional] 
**unilogin** | **bool** | Use the UniLogin extension instead of submitting credentials. | 

## Example

```python
from unipile.models.start_auth_intent_request_any_of1 import StartAuthIntentRequestAnyOf1

# TODO update the JSON string below
json = "{}"
# create an instance of StartAuthIntentRequestAnyOf1 from a JSON string
start_auth_intent_request_any_of1_instance = StartAuthIntentRequestAnyOf1.from_json(json)
# print the JSON string representation of the object
print(StartAuthIntentRequestAnyOf1.to_json())

# convert the object into a dict
start_auth_intent_request_any_of1_dict = start_auth_intent_request_any_of1_instance.to_dict()
# create an instance of StartAuthIntentRequestAnyOf1 from a dict
start_auth_intent_request_any_of1_from_dict = StartAuthIntentRequestAnyOf1.from_dict(start_auth_intent_request_any_of1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


