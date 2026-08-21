# GetManagedCompanyPages200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[GetManagedCompanyPages200ResponseDataInner]**](GetManagedCompanyPages200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.get_managed_company_pages200_response import GetManagedCompanyPages200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetManagedCompanyPages200Response from a JSON string
get_managed_company_pages200_response_instance = GetManagedCompanyPages200Response.from_json(json)
# print the JSON string representation of the object
print(GetManagedCompanyPages200Response.to_json())

# convert the object into a dict
get_managed_company_pages200_response_dict = get_managed_company_pages200_response_instance.to_dict()
# create an instance of GetManagedCompanyPages200Response from a dict
get_managed_company_pages200_response_from_dict = GetManagedCompanyPages200Response.from_dict(get_managed_company_pages200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


