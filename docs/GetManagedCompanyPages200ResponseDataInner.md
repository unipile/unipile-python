# GetManagedCompanyPages200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the company. | 
**mailbox_id** | **str** | The messaging ID of the company. | 
**name** | **str** | The name of the company. | 
**messaging_enabled** | **bool** | Whether messaging features are enabled for this company. | [optional] 

## Example

```python
from unipile.models.get_managed_company_pages200_response_data_inner import GetManagedCompanyPages200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetManagedCompanyPages200ResponseDataInner from a JSON string
get_managed_company_pages200_response_data_inner_instance = GetManagedCompanyPages200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetManagedCompanyPages200ResponseDataInner.to_json())

# convert the object into a dict
get_managed_company_pages200_response_data_inner_dict = get_managed_company_pages200_response_data_inner_instance.to_dict()
# create an instance of GetManagedCompanyPages200ResponseDataInner from a dict
get_managed_company_pages200_response_data_inner_from_dict = GetManagedCompanyPages200ResponseDataInner.from_dict(get_managed_company_pages200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


