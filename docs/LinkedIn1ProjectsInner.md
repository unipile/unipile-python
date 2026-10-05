# LinkedIn1ProjectsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the project. | 
**description** | **str** | Description of the project. | [optional] 
**contributors** | [**List[LinkedIn1ProjectsInnerContributorsInner]**](LinkedIn1ProjectsInnerContributorsInner.md) | Contributors to the project. | 
**skills** | **List[Optional[str]]** | Skills related to the project. | [optional] 
**skills_preview** | **str** | Insight of the skills related to the project. | [optional] 
**started_on** | **str** | Start date of the project in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the project in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.linked_in1_projects_inner import LinkedIn1ProjectsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1ProjectsInner from a JSON string
linked_in1_projects_inner_instance = LinkedIn1ProjectsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1ProjectsInner.to_json())

# convert the object into a dict
linked_in1_projects_inner_dict = linked_in1_projects_inner_instance.to_dict()
# create an instance of LinkedIn1ProjectsInner from a dict
linked_in1_projects_inner_from_dict = LinkedIn1ProjectsInner.from_dict(linked_in1_projects_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


