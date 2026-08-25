# LinkNewAccountConfigGoogle

Oauth authentication configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**oauth_scope** | **List[str]** | The final list of authorizations to request from the Provider. Use this field to expand or narrow the scope of API access. For example, if your application only uses the Calendar API, you may request authorization solely for the calendar, excluding email access for providers like Google. Make sure to give only authorizations accepted by your registered provider application. For a new account, omitting this field requests the authorizations defined in the Provider OAuth settings. For a reconnect, omitting it preserves already granted authorizations and adds the authorizations currently defined in the Provider OAuth settings. | [optional] 

## Example

```python
from unipile.models.link_new_account_config_google import LinkNewAccountConfigGoogle

# TODO update the JSON string below
json = "{}"
# create an instance of LinkNewAccountConfigGoogle from a JSON string
link_new_account_config_google_instance = LinkNewAccountConfigGoogle.from_json(json)
# print the JSON string representation of the object
print(LinkNewAccountConfigGoogle.to_json())

# convert the object into a dict
link_new_account_config_google_dict = link_new_account_config_google_instance.to_dict()
# create an instance of LinkNewAccountConfigGoogle from a dict
link_new_account_config_google_from_dict = LinkNewAccountConfigGoogle.from_dict(link_new_account_config_google_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


