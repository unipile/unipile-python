# PerformClassicPeopleSearchRequestAdvancedKeywords

A set of advanced keywords based filters.    Native filter : Keywords   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_name** | **str** |     Native filter : First name    | [optional] 
**last_name** | **str** |     Native filter : Last name    | [optional] 
**title** | **str** |     Native filter : Title    | [optional] 
**company** | **str** |     Native filter : Company    | [optional] 
**school** | **str** |     Native filter : School    | [optional] 

## Example

```python
from unipile.models.perform_classic_people_search_request_advanced_keywords import PerformClassicPeopleSearchRequestAdvancedKeywords

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicPeopleSearchRequestAdvancedKeywords from a JSON string
perform_classic_people_search_request_advanced_keywords_instance = PerformClassicPeopleSearchRequestAdvancedKeywords.from_json(json)
# print the JSON string representation of the object
print(PerformClassicPeopleSearchRequestAdvancedKeywords.to_json())

# convert the object into a dict
perform_classic_people_search_request_advanced_keywords_dict = perform_classic_people_search_request_advanced_keywords_instance.to_dict()
# create an instance of PerformClassicPeopleSearchRequestAdvancedKeywords from a dict
perform_classic_people_search_request_advanced_keywords_from_dict = PerformClassicPeopleSearchRequestAdvancedKeywords.from_dict(perform_classic_people_search_request_advanced_keywords_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


