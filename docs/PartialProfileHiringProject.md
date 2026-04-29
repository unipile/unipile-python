# PartialProfileHiringProject

The hiring project where the User is a candidate.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the project. | 
**name** | **str** | The name of the project. | 
**pipeline_stage** | **str** | The pipeline stage at which the User is (contacted, replied, etc.). | 

## Example

```python
from unipile.models.partial_profile_hiring_project import PartialProfileHiringProject

# TODO update the JSON string below
json = "{}"
# create an instance of PartialProfileHiringProject from a JSON string
partial_profile_hiring_project_instance = PartialProfileHiringProject.from_json(json)
# print the JSON string representation of the object
print(PartialProfileHiringProject.to_json())

# convert the object into a dict
partial_profile_hiring_project_dict = partial_profile_hiring_project_instance.to_dict()
# create an instance of PartialProfileHiringProject from a dict
partial_profile_hiring_project_from_dict = PartialProfileHiringProject.from_dict(partial_profile_hiring_project_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


