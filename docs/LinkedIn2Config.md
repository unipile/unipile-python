# LinkedIn2Config

LinkedIn specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**products** | **List[str]** | Specifies which LinkedIn products are allowed to be activated (as long as the account actually has the relevant subscriptions). By default, all products are made available.&lt;br&gt;When reconnecting an account, just omit this field to keep allowing access to the same products, or provide new values to expand or narrow the scope. &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/docs/linkedin-link-accounts\&quot;&gt;Learn more about Linkedin products&lt;/a&gt;       &#x60;classic&#x60; : Personnal Social network&lt;br&gt;       &#x60;recruiter&#x60; : Recruiter&lt;br&gt;       &#x60;sales_navigator&#x60; : Sales Navigator&lt;br&gt;       &#x60;company&#x60; : Company Pages        | [optional] [default to ["classic","company","recruiter","sales_navigator"]]
**allow_product_selection** | **bool** | When true, return a product selection checkpoint after authentication, even when only one LinkedIn product is available. When false, all available products are selected automatically, except Recruiter when Sales Navigator is also available. | [optional] [default to False]

## Example

```python
from unipile.models.linked_in2_config import LinkedIn2Config

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2Config from a JSON string
linked_in2_config_instance = LinkedIn2Config.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2Config.to_json())

# convert the object into a dict
linked_in2_config_dict = linked_in2_config_instance.to_dict()
# create an instance of LinkedIn2Config from a dict
linked_in2_config_from_dict = LinkedIn2Config.from_dict(linked_in2_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


