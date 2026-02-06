# GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the project. | 
**description** | **str** | Description of the project. | [optional] 
**contributors** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInnerContributorsInner.md) | Contributors to the project. | 
**skills** | **List[Optional[str]]** | Skills related to the project. | [optional] 
**skills_preview** | **str** | Insight of the skills related to the project. | [optional] 
**started_on** | **str** | Start date of the project in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the project in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.get_user_profile200_response_specifics_all_of_any_of_projects_inner import GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner from a JSON string
get_user_profile200_response_specifics_all_of_any_of_projects_inner_instance = GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_projects_inner_dict = get_user_profile200_response_specifics_all_of_any_of_projects_inner_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner from a dict
get_user_profile200_response_specifics_all_of_any_of_projects_inner_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner.from_dict(get_user_profile200_response_specifics_all_of_any_of_projects_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


