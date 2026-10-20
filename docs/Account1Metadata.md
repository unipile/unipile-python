# Account1Metadata

Metadata associated with the Account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auto_proxy_country** | **str** | The preferred country for automatic proxy selection. A country inferred from an IP may be outside Unipile’s proxy offering. The current proxy may be in another country when fallback is allowed and no proxy is available in the preferred country. | [optional] 
**allow_country_fallback** | **bool** | Whether an available proxy from another country may be used when none is available in the rotation country, during authentication and throughout the account lifetime. Defaults to true. A country included in Unipile’s proxy offering may still have no proxy currently available. If false, authentication fails when no proxy is available in the rotation country. If the selected proxy later fails and no replacement is available there, the account enters Service interruption. Rotation to another available proxy in that country remains allowed. | [optional] 
**connection_method** | **str** | The authentication method that currently owns the account session lifecycle. | [optional] 
**v1_account_id** | **str** | The ID of the account in the v1 if the account is migrated from v1. | [optional] 
**v1_instance_port** | **float** | The port of the v1 instance from which the account was migrated. | [optional] 
**products_connection_status** | **Dict[str, str]** | The status of the connection to a product, if the account is connected to multiple products. | [optional] 
**custom_data** | **Dict[str, str]** | Custom data of the account. This is where you can store custom data using \&quot;Update an account\&quot; method. | [optional] 

## Example

```python
from unipile.models.account1_metadata import Account1Metadata

# TODO update the JSON string below
json = "{}"
# create an instance of Account1Metadata from a JSON string
account1_metadata_instance = Account1Metadata.from_json(json)
# print the JSON string representation of the object
print(Account1Metadata.to_json())

# convert the object into a dict
account1_metadata_dict = account1_metadata_instance.to_dict()
# create an instance of Account1Metadata from a dict
account1_metadata_from_dict = Account1Metadata.from_dict(account1_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


