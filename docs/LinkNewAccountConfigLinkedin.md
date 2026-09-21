# LinkNewAccountConfigLinkedin

LinkedIn specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**products** | **List[str]** | Specifies which LinkedIn products are allowed to be activated (as long as the account actually has the relevant subscriptions). By default, all products are made available.&lt;br&gt;When reconnecting an account, just omit this field to keep allowing access to the same products, or provide new values to expand or narrow the scope. &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/docs/linkedin-link-accounts\&quot;&gt;Learn more about Linkedin products&lt;/a&gt;       &#x60;classic&#x60; : Personnal Social network&lt;br&gt;       &#x60;recruiter&#x60; : Recruiter&lt;br&gt;       &#x60;sales_navigator&#x60; : Sales Navigator&lt;br&gt;       &#x60;company&#x60; : Company Pages        | [optional] [default to [classic, company, recruiter, sales_navigator]]
**allow_product_selection** | **bool** | When true, show the product selection screen after authentication, even when only one LinkedIn product is available; this screen also displays the requested scopes. When false, products are selected automatically and scope consent is collected before authentication. | [optional] [default to True]
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


