# LinkedInProjectsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the project. | 
**description** | **str** | Description of the project. | [optional] 
**contributors** | [**List[LinkedInProjectsInnerContributorsInner]**](LinkedInProjectsInnerContributorsInner.md) | Contributors to the project. | 
**skills** | **List[Optional[str]]** | Skills related to the project. | [optional] 
**skills_preview** | **str** | Insight of the skills related to the project. | [optional] 
**started_on** | **str** | Start date of the project in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the project in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.linked_in_projects_inner import LinkedInProjectsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInProjectsInner from a JSON string
linked_in_projects_inner_instance = LinkedInProjectsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedInProjectsInner.to_json())

# convert the object into a dict
linked_in_projects_inner_dict = linked_in_projects_inner_instance.to_dict()
# create an instance of LinkedInProjectsInner from a dict
linked_in_projects_inner_from_dict = LinkedInProjectsInner.from_dict(linked_in_projects_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


