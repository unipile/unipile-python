# OauthOutlookGoogleConfig

Oauth authentication configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**oauth_scope** | **List[Optional[str]]** | Override of the list of authorizations to request from the Provider. Use this field to narrow the scope of API access. For example, if your application only uses the Calendar API, you may request authorization solely for the calendar, excluding email access for providers like Google. Make sure to give only authorizations accepted by your registered provider application. If left unspecified, all authorizations defined in the Provider OAuth settings section will be requested. | [optional] 

## Example

```python
from unipile.models.oauth_outlook_google_config import OauthOutlookGoogleConfig

# TODO update the JSON string below
json = "{}"
# create an instance of OauthOutlookGoogleConfig from a JSON string
oauth_outlook_google_config_instance = OauthOutlookGoogleConfig.from_json(json)
# print the JSON string representation of the object
print(OauthOutlookGoogleConfig.to_json())

# convert the object into a dict
oauth_outlook_google_config_dict = oauth_outlook_google_config_instance.to_dict()
# create an instance of OauthOutlookGoogleConfig from a dict
oauth_outlook_google_config_from_dict = OauthOutlookGoogleConfig.from_dict(oauth_outlook_google_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


