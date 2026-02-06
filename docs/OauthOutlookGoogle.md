# OauthOutlookGoogle

Start the authentication intent with Oauth provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider that use Oauth as authentication method.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook. | 
**oauth_callback_redirect_uri** | **str** | The URL to redirect to after the user has authenticated using the Provider&#39;s oAuth screen. | 
**login_hint** | **str** | Uses the hint to simplify the login flow either by prefilling the email / username / phone number field in the authentication form. | [optional] 
**config** | [**OauthOutlookGoogleConfig**](OauthOutlookGoogleConfig.md) |  | [optional] 

## Example

```python
from unipile.models.oauth_outlook_google import OauthOutlookGoogle

# TODO update the JSON string below
json = "{}"
# create an instance of OauthOutlookGoogle from a JSON string
oauth_outlook_google_instance = OauthOutlookGoogle.from_json(json)
# print the JSON string representation of the object
print(OauthOutlookGoogle.to_json())

# convert the object into a dict
oauth_outlook_google_dict = oauth_outlook_google_instance.to_dict()
# create an instance of OauthOutlookGoogle from a dict
oauth_outlook_google_from_dict = OauthOutlookGoogle.from_dict(oauth_outlook_google_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


