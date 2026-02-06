# LinkedInConfig

LinkedIn specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**products** | **List[str]** | Specifies which LinkedIn products to connect to (if available on the users account). This allows you to disable access to certain product data within Unipile and avoid receiving events related to them. Note: This field does not require the user to be subscribed to the selected products — accounts without access will still be linked successfully. ⚠️ If you plan to access &#x60;recruiter&#x60; data, we recommend using the Cookie Authentication method for better compatibility. Leave undefined when re-authenticating an already linked account to keep the original configuration or specify a new list of products to augment / reduce the scope.       &#x60;classic&#x60; : LinkedInSocial network       &#x60;recruiter&#x60; : Recruiter       &#x60;sales_navigator&#x60; : Sales navigator       &#x60;company&#x60; : Company Pages        | [optional] [default to ["classic"]]

## Example

```python
from unipile.models.linked_in_config import LinkedInConfig

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInConfig from a JSON string
linked_in_config_instance = LinkedInConfig.from_json(json)
# print the JSON string representation of the object
print(LinkedInConfig.to_json())

# convert the object into a dict
linked_in_config_dict = linked_in_config_instance.to_dict()
# create an instance of LinkedInConfig from a dict
linked_in_config_from_dict = LinkedInConfig.from_dict(linked_in_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


