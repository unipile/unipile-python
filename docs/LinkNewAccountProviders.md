# LinkNewAccountProviders

Required to link a new account with Unipile. The list of providers to show in the selection list.         - `*` to list all providers.         - `*:EMAILS` to list providers with Emails API support only.         - `*:MESSAGING` to list providers with Messaging API support only.         - `*:CALENDAR` to list providers with Calendar API support only.         - `*:SOCIAL` to list providers with Social API (Users, Posts, etc.) support only.         - a specific provider to list only that provider.         - give an array of specific providers.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.link_new_account_providers import LinkNewAccountProviders

# TODO update the JSON string below
json = "{}"
# create an instance of LinkNewAccountProviders from a JSON string
link_new_account_providers_instance = LinkNewAccountProviders.from_json(json)
# print the JSON string representation of the object
print(LinkNewAccountProviders.to_json())

# convert the object into a dict
link_new_account_providers_dict = link_new_account_providers_instance.to_dict()
# create an instance of LinkNewAccountProviders from a dict
link_new_account_providers_from_dict = LinkNewAccountProviders.from_dict(link_new_account_providers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


