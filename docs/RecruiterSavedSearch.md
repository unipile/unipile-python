# RecruiterSavedSearch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**query** | **str** | The ID of the Company. | 
**new_results_count** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**project** | [**RecruiterSavedSearchProject**](RecruiterSavedSearchProject.md) |  | [optional] 

## Example

```python
from unipile.models.recruiter_saved_search import RecruiterSavedSearch

# TODO update the JSON string below
json = "{}"
# create an instance of RecruiterSavedSearch from a JSON string
recruiter_saved_search_instance = RecruiterSavedSearch.from_json(json)
# print the JSON string representation of the object
print(RecruiterSavedSearch.to_json())

# convert the object into a dict
recruiter_saved_search_dict = recruiter_saved_search_instance.to_dict()
# create an instance of RecruiterSavedSearch from a dict
recruiter_saved_search_from_dict = RecruiterSavedSearch.from_dict(recruiter_saved_search_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


