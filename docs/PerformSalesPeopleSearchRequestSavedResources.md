# PerformSalesPeopleSearchRequestSavedResources

    Native filter : Workflow / Saved leads and accounts   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**saved_leads** | **bool** | Whether the users should be included in one of your lists.                  Explicitely set True or False to include or exclude the option.    Native filter : All my saved leads    | [optional] 
**saved_accounts** | **bool** | Whether the users should be included in one of your lists.                  Explicitely set True or False to include or exclude the option.    Native filter : All my saved accounts    | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_saved_resources import PerformSalesPeopleSearchRequestSavedResources

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestSavedResources from a JSON string
perform_sales_people_search_request_saved_resources_instance = PerformSalesPeopleSearchRequestSavedResources.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestSavedResources.to_json())

# convert the object into a dict
perform_sales_people_search_request_saved_resources_dict = perform_sales_people_search_request_saved_resources_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestSavedResources from a dict
perform_sales_people_search_request_saved_resources_from_dict = PerformSalesPeopleSearchRequestSavedResources.from_dict(perform_sales_people_search_request_saved_resources_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


