# LinkedIn2EducationInnerSchool


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the school. | 
**name** | **str** | Name of the school. | [optional] 
**picture_url** | **str** | Public url to the profile picture of the school. | [optional] 
**profile_url** | **str** | Public url to the profile of the school. | [optional] 

## Example

```python
from unipile.models.linked_in2_education_inner_school import LinkedIn2EducationInnerSchool

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2EducationInnerSchool from a JSON string
linked_in2_education_inner_school_instance = LinkedIn2EducationInnerSchool.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2EducationInnerSchool.to_json())

# convert the object into a dict
linked_in2_education_inner_school_dict = linked_in2_education_inner_school_instance.to_dict()
# create an instance of LinkedIn2EducationInnerSchool from a dict
linked_in2_education_inner_school_from_dict = LinkedIn2EducationInnerSchool.from_dict(linked_in2_education_inner_school_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


