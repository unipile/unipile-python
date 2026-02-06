# AccountList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[AccountListDataInner]**](AccountListDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.account_list import AccountList

# TODO update the JSON string below
json = "{}"
# create an instance of AccountList from a JSON string
account_list_instance = AccountList.from_json(json)
# print the JSON string representation of the object
print(AccountList.to_json())

# convert the object into a dict
account_list_dict = account_list_instance.to_dict()
# create an instance of AccountList from a dict
account_list_from_dict = AccountList.from_dict(account_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


