# FacebookConfig

Facebook provider specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**surface** | **str** | Meta web surface used to bootstrap the session. &#x60;facebook&#x60; uses facebook.com/messages (default), &#x60;messenger&#x60; uses messenger.com. | [optional] [default to 'facebook']
**products** | **List[str]** | Specifies which Facebook products are allowed to be activated (as long as the account actually has access to them). By default, all products are made available. &#x60;messaging&#x60; is always activated.       &#x60;messaging&#x60; : Messenger inbox of the account&lt;br&gt;       &#x60;page&#x60; : Facebook Pages administered by the account — each Page is an inbox (&#x60;PAGE_&lt;page_id&gt;_INBOX&#x60;) whose chats are answered as the Page        | [optional] [default to ["messaging","page"]]
**page_ids** | **List[Optional[str]]** | With the &#x60;page&#x60; product: the Facebook Pages that can be activated, by id (the Page messaging id, as in &#x60;PAGE_&lt;page_id&gt;_INBOX&#x60;). By default, every Page the account administers. Without &#x60;allow_product_selection&#x60; they are all activated; with it, they are the ones offered for selection. Each activated Page runs as its own product &#x60;page_&lt;page_id&gt;&#x60;, with its own connection status. | [optional] 
**allow_product_selection** | **bool** | When true, return a product selection checkpoint after authentication, even when the account administers no Facebook Page. When false, all available products are selected automatically. | [optional] [default to False]
**allow_methods** | **List[str]** | The authentication methods to show in Hosted Auth.           &#x60;credentials&#x60;: Credentials authentication           &#x60;cookies&#x60;: Cookie authentication           &#x60;unilogin&#x60;: Connect the active browser session through the UniLogin extension          | [optional] [default to ["credentials","cookies","unilogin"]]

## Example

```python
from unipile.models.facebook_config import FacebookConfig

# TODO update the JSON string below
json = "{}"
# create an instance of FacebookConfig from a JSON string
facebook_config_instance = FacebookConfig.from_json(json)
# print the JSON string representation of the object
print(FacebookConfig.to_json())

# convert the object into a dict
facebook_config_dict = facebook_config_instance.to_dict()
# create an instance of FacebookConfig from a dict
facebook_config_from_dict = FacebookConfig.from_dict(facebook_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


