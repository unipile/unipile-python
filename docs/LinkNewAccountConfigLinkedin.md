# LinkNewAccountConfigLinkedin

LinkedIn specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**products** | [**LinkedIn1ConfigProducts**](LinkedIn1ConfigProducts.md) |  | [optional] 
**allow_methods** | **List[str]** | The authentication methods to show in the hosted auth.             &#x60;credentials&#x60; : Credentials Authentication             &#x60;cookies&#x60; : Cookies Authentication            | [optional] [default to ["credentials"]]

## Example

```python
from unipile.models.link_new_account_config_linkedin import LinkNewAccountConfigLinkedin

# TODO update the JSON string below
json = "{}"
# create an instance of LinkNewAccountConfigLinkedin from a JSON string
link_new_account_config_linkedin_instance = LinkNewAccountConfigLinkedin.from_json(json)
# print the JSON string representation of the object
print(LinkNewAccountConfigLinkedin.to_json())

# convert the object into a dict
link_new_account_config_linkedin_dict = link_new_account_config_linkedin_instance.to_dict()
# create an instance of LinkNewAccountConfigLinkedin from a dict
link_new_account_config_linkedin_from_dict = LinkNewAccountConfigLinkedin.from_dict(link_new_account_config_linkedin_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


