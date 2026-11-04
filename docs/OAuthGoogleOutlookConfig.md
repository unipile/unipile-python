# OAuthGoogleOutlookConfig

Oauth authentication configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**oauth_scope** | **List[Optional[str]]** | The final list of authorizations to request from the Provider. Use this field to expand or narrow the scope of API access. For example, if your application only uses the Calendar API, you may request authorization solely for the calendar, excluding email access for providers like Google. Make sure to give only authorizations accepted by your registered provider application. For a new account, omitting this field requests the authorizations defined in the Provider OAuth settings. For a reconnect, omitting it preserves already granted authorizations and adds the authorizations currently defined in the Provider OAuth settings. | [optional] 

## Example

```python
from unipile.models.o_auth_google_outlook_config import OAuthGoogleOutlookConfig

# TODO update the JSON string below
json = "{}"
# create an instance of OAuthGoogleOutlookConfig from a JSON string
o_auth_google_outlook_config_instance = OAuthGoogleOutlookConfig.from_json(json)
# print the JSON string representation of the object
print(OAuthGoogleOutlookConfig.to_json())

# convert the object into a dict
o_auth_google_outlook_config_dict = o_auth_google_outlook_config_instance.to_dict()
# create an instance of OAuthGoogleOutlookConfig from a dict
o_auth_google_outlook_config_from_dict = OAuthGoogleOutlookConfig.from_dict(o_auth_google_outlook_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


