# ProviderAuthentication

Choose a provider, then its supported authentication method: password, cookies, OAuth, QR code or pairing code. OAuth starts a browser authorization flow without submitting credentials. Omit unilogin for this flow.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**FacebookCredentials**](FacebookCredentials.md) |  | 
**config** | [**FacebookConfig**](FacebookConfig.md) |  | [optional] 
**user_timezone** | **str** | The time zone of the current user can be used on a few specific features (e.g. scheduled actions). Setting it at authentication avoids having to do it on a case-by-case basis later on. | [optional] 
**user_language** | **str** | Primary browser language captured with the session cookies. | [optional] 
**user_languages** | **List[str]** | Ordered browser language preferences captured with the session cookies. | [optional] 
**oauth_callback_redirect_uri** | **str** | The URL to redirect to after the user has authenticated using the Provider&#39;s oAuth screen. | 
**login_hint** | **str** | Uses the hint to simplify the login flow either by prefilling the email / username / phone number field in the authentication form. | [optional] 
**user_agent** | **str** | The exact user agent of the browser used to retrieve the cookies. You can get it in the browser&#39;s console with &#x60;console.log(navigator.userAgent)&#x60;. In Hosted Auth, this is collected automatically from the user&#39;s browser. When reconnecting an Account, the user agent it already uses is kept. | [optional] 
**account_scope_id** | **str** | The Scope assigned to a newly linked account. Cannot be specified when reconnecting an existing account. | [optional] 
**state** | **str** | State data sent in the &#x60;account.add&#x60; / &#x60;account.reconnect&#x60; webhook payload after the authentication process. | [optional] 
**account_id** | **str** | The ID of the Account to re-authenticate or reconfigure. The account may be running, partially connected, or disconnected, and &#x60;provider&#x60; must match its provider. Reconnecting always refreshes the entire account and restarts all configured products. If not specified, a new account is linked. | [optional] 

## Example

```python
from unipile.models.provider_authentication import ProviderAuthentication

# TODO update the JSON string below
json = "{}"
# create an instance of ProviderAuthentication from a JSON string
provider_authentication_instance = ProviderAuthentication.from_json(json)
# print the JSON string representation of the object
print(ProviderAuthentication.to_json())

# convert the object into a dict
provider_authentication_dict = provider_authentication_instance.to_dict()
# create an instance of ProviderAuthentication from a dict
provider_authentication_from_dict = ProviderAuthentication.from_dict(provider_authentication_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


