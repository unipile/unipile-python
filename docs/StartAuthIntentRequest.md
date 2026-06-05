# StartAuthIntentRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**Instagram1Credentials**](Instagram1Credentials.md) |  | 
**config** | [**Instagram1Config**](Instagram1Config.md) |  | [optional] 
**user_timezone** | **str** | The time zone of the current user can be used on a few specific features (e.g. scheduled actions). Setting it at authentication avoids having to do it on a case-by-case basis later on. | [optional] 
**oauth_callback_redirect_uri** | **str** | The URL to redirect to after the user has authenticated using the Provider&#39;s oAuth screen. | 
**login_hint** | **str** | Uses the hint to simplify the login flow either by prefilling the email / username / phone number field in the authentication form. | [optional] 
**state** | **str** | State data sent in the &#x60;account.add&#x60; / &#x60;account.reconnect&#x60; webhook payload after the authentication process. | [optional] 
**account_id** | **str** | The ID of the Account to re-authenticate. Must be a disconnected account, and &#x60;provider&#x60; must match the provider of the account. If not specified, will link as new account. | [optional] 

## Example

```python
from unipile.models.start_auth_intent_request import StartAuthIntentRequest

# TODO update the JSON string below
json = "{}"
# create an instance of StartAuthIntentRequest from a JSON string
start_auth_intent_request_instance = StartAuthIntentRequest.from_json(json)
# print the JSON string representation of the object
print(StartAuthIntentRequest.to_json())

# convert the object into a dict
start_auth_intent_request_dict = start_auth_intent_request_instance.to_dict()
# create an instance of StartAuthIntentRequest from a dict
start_auth_intent_request_from_dict = StartAuthIntentRequest.from_dict(start_auth_intent_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


