# FullProfileProjectsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the project. | 
**description** | **str** | Description of the project. | [optional] 
**contributors** | [**List[LinkedInProjectsInnerContributorsInner]**](LinkedInProjectsInnerContributorsInner.md) | Contributors to the project. | 
**skills** | **List[str]** | Skills related to the project. | [optional] 
**skills_preview** | **str** | Insight of the skills related to the project. | [optional] 
**started_on** | **str** | Start date of the project in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the project in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.full_profile_projects_inner import FullProfileProjectsInner

# TODO update the JSON string below
json = "{}"
# create an instance of FullProfileProjectsInner from a JSON string
full_profile_projects_inner_instance = FullProfileProjectsInner.from_json(json)
# print the JSON string representation of the object
print(FullProfileProjectsInner.to_json())

# convert the object into a dict
full_profile_projects_inner_dict = full_profile_projects_inner_instance.to_dict()
# create an instance of FullProfileProjectsInner from a dict
full_profile_projects_inner_from_dict = FullProfileProjectsInner.from_dict(full_profile_projects_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


