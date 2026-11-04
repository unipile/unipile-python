# OAuthGoogleOutlook

Start browser-based authorization with Google or Outlook. No credentials are submitted in this request; the user authenticates on the provider authorization page.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider that use Oauth as authentication method.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook. | 
**oauth_callback_redirect_uri** | **str** | The URL to redirect to after the user has authenticated using the Provider&#39;s oAuth screen. | 
**login_hint** | **str** | Uses the hint to simplify the login flow either by prefilling the email / username / phone number field in the authentication form. | [optional] 
**config** | [**OAuthGoogleOutlookConfig**](OAuthGoogleOutlookConfig.md) |  | [optional] 

## Example

```python
from unipile.models.o_auth_google_outlook import OAuthGoogleOutlook

# TODO update the JSON string below
json = "{}"
# create an instance of OAuthGoogleOutlook from a JSON string
o_auth_google_outlook_instance = OAuthGoogleOutlook.from_json(json)
# print the JSON string representation of the object
print(OAuthGoogleOutlook.to_json())

# convert the object into a dict
o_auth_google_outlook_dict = o_auth_google_outlook_instance.to_dict()
# create an instance of OAuthGoogleOutlook from a dict
o_auth_google_outlook_from_dict = OAuthGoogleOutlook.from_dict(o_auth_google_outlook_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


