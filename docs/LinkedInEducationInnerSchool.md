# LinkedInEducationInnerSchool


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the school. | 
**name** | **str** | Name of the school. | [optional] 
**picture_url** | **str** | Public url to the profile picture of the school. | [optional] 
**profile_url** | **str** | Public url to the profile of the school. | [optional] 

## Example

```python
from unipile.models.linked_in_education_inner_school import LinkedInEducationInnerSchool

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInEducationInnerSchool from a JSON string
linked_in_education_inner_school_instance = LinkedInEducationInnerSchool.from_json(json)
# print the JSON string representation of the object
print(LinkedInEducationInnerSchool.to_json())

# convert the object into a dict
linked_in_education_inner_school_dict = linked_in_education_inner_school_instance.to_dict()
# create an instance of LinkedInEducationInnerSchool from a dict
linked_in_education_inner_school_from_dict = LinkedInEducationInnerSchool.from_dict(linked_in_education_inner_school_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


