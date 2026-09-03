# UpdateAccountRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_scope_id** | **str** | The Scope to permanently assign to an unscoped Account. This field requires a Service API Key, and the Scope cannot be removed or replaced after assignment. | [optional] 
**metadata** | **Dict[str, Optional[str]]** | Custom key-value data for the account. Replaces the account &#x60;metadata.custom_data&#x60; field; other metadata fields are not modified. Any fields not provided will be removed. | [optional] 
**auto_proxy_country** | **str** | The country to use for Automatic Proxy Protection. | [optional] 
**proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 

## Example

```python
from unipile.models.update_account_request import UpdateAccountRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateAccountRequest from a JSON string
update_account_request_instance = UpdateAccountRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateAccountRequest.to_json())

# convert the object into a dict
update_account_request_dict = update_account_request_instance.to_dict()
# create an instance of UpdateAccountRequest from a dict
update_account_request_from_dict = UpdateAccountRequest.from_dict(update_account_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


