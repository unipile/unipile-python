# LinkNewAccountConfigLinkedin

LinkedIn specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**products** | **List[str]** | Specifies which LinkedIn products to connect to (if available on the users account). This allows you to disable access to certain product data within Unipile and avoid receiving events related to them. Note: This field does not require the user to be subscribed to the selected products — accounts without access will still be linked successfully. ⚠️ If you plan to access &#x60;recruiter&#x60; data, we recommend using the Cookie Authentication method for better compatibility. Leave undefined when re-authenticating an already linked account to keep the original configuration or specify a new list of products to augment / reduce the scope.       &#x60;classic&#x60; : LinkedInSocial network       &#x60;recruiter&#x60; : Recruiter       &#x60;sales_navigator&#x60; : Sales navigator       &#x60;company&#x60; : Company Pages        | [optional] [default to [classic]]
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


