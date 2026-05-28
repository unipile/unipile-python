# AccountMetadata


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auto_proxy_country** | **str** | The chosen country for the automatic proxy selection. | [optional] 
**v1_account_id** | **str** | The ID of the account in the v1 if the account is migrated from v1. | [optional] 
**products_connection_status** | **Dict[str, str]** | The status of the connection to a product, if the account is connected to multiple products. | [optional] 
**custom_data** | **Dict[str, Optional[str]]** | Custom data of the account. This is where you can store custom data using \&quot;Update an account\&quot; method. | [optional] 

## Example

```python
from unipile.models.account_metadata import AccountMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of AccountMetadata from a JSON string
account_metadata_instance = AccountMetadata.from_json(json)
# print the JSON string representation of the object
print(AccountMetadata.to_json())

# convert the object into a dict
account_metadata_dict = account_metadata_instance.to_dict()
# create an instance of AccountMetadata from a dict
account_metadata_from_dict = AccountMetadata.from_dict(account_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


