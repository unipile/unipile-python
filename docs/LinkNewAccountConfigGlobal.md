# LinkNewAccountConfigGlobal

Configuration applied to all providers

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**login_hint** | **str** | If your application knows which user is trying to authenticate, it can use this parameter to provide a hint to the Hosted Auth. It uses the hint to simplify the login flow either by prefilling the email / username / phone number field in the authentication forms. | [optional] 
**allow_user_proxy_override** | **bool** | If true, the Hosted Auth UI will show a field where the user can provide their own proxy settings. When filled, the user-defined proxy takes precedence over any custom_proxy defined in the configuration and over automatic proxy detection (if the provider supports it). | [optional] [default to False]
**allow_user_country_override** | **bool** | If true, the Hosted Auth UI will allow the user to manually select a country for automatic proxy configuration (when supported by the provider). This selection overrides the detected country and any auto_proxy_config value. Note: if a custom_proxy is explicitly configured for a provider, this option has no effect for that provider (no country selection will be shown). | [optional] [default to False]
**wait_initial_sync** | **bool** | When true, the hosted authentication will wait for the initial sync to complete before redirecting. Only supported for providers with initial sync capability (whatsapp and imap). The hosted UI will display a loading screen until the initial sync is completed. | [optional] [default to False]

## Example

```python
from unipile.models.link_new_account_config_global import LinkNewAccountConfigGlobal

# TODO update the JSON string below
json = "{}"
# create an instance of LinkNewAccountConfigGlobal from a JSON string
link_new_account_config_global_instance = LinkNewAccountConfigGlobal.from_json(json)
# print the JSON string representation of the object
print(LinkNewAccountConfigGlobal.to_json())

# convert the object into a dict
link_new_account_config_global_dict = link_new_account_config_global_instance.to_dict()
# create an instance of LinkNewAccountConfigGlobal from a dict
link_new_account_config_global_from_dict = LinkNewAccountConfigGlobal.from_dict(link_new_account_config_global_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


