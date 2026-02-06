# PerformSalesPeopleSearchRequestRecentInteraction

    Native filter : Workflow / People you interacted with   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**viewed_profile** | **bool** | Whether you recently visited the users&#39;s profiles.                  Explicitely set True or False to include or exclude the option.    Native filter : Viewed profile    | [optional] 
**messaged** | **bool** | Whether you recently sent a message to the users.                  Explicitely set True or False to include or exclude the option.    Native filter : Messaged    | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_recent_interaction import PerformSalesPeopleSearchRequestRecentInteraction

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestRecentInteraction from a JSON string
perform_sales_people_search_request_recent_interaction_instance = PerformSalesPeopleSearchRequestRecentInteraction.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestRecentInteraction.to_json())

# convert the object into a dict
perform_sales_people_search_request_recent_interaction_dict = perform_sales_people_search_request_recent_interaction_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestRecentInteraction from a dict
perform_sales_people_search_request_recent_interaction_from_dict = PerformSalesPeopleSearchRequestRecentInteraction.from_dict(perform_sales_people_search_request_recent_interaction_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


