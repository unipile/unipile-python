# StartAuthIntentRequestAnyOf1Config

LinkedIn products and managed proxy selection. Credential-bearing custom_proxy configuration is not accepted in this asynchronous flow.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**products** | **List[str]** |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 

## Example

```python
from unipile.models.start_auth_intent_request_any_of1_config import StartAuthIntentRequestAnyOf1Config

# TODO update the JSON string below
json = "{}"
# create an instance of StartAuthIntentRequestAnyOf1Config from a JSON string
start_auth_intent_request_any_of1_config_instance = StartAuthIntentRequestAnyOf1Config.from_json(json)
# print the JSON string representation of the object
print(StartAuthIntentRequestAnyOf1Config.to_json())

# convert the object into a dict
start_auth_intent_request_any_of1_config_dict = start_auth_intent_request_any_of1_config_instance.to_dict()
# create an instance of StartAuthIntentRequestAnyOf1Config from a dict
start_auth_intent_request_any_of1_config_from_dict = StartAuthIntentRequestAnyOf1Config.from_dict(start_auth_intent_request_any_of1_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


