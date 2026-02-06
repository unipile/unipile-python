# NewEducation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**notify_network** | **bool** | Notify the network about the education. Turn on to notify your network of key profile changes (such as new education) and work anniversaries. | [optional] [default to False]
**school** | [**NewEducationSchool**](NewEducationSchool.md) |  | [optional] 
**degree** | [**NewEducationDegree**](NewEducationDegree.md) |  | [optional] 
**field_of_study** | [**NewEducationFieldOfStudy**](NewEducationFieldOfStudy.md) |  | [optional] 
**start_date** | [**NewEducationStartDate**](NewEducationStartDate.md) |  | 
**end_date** | [**NewEducationEndDate**](NewEducationEndDate.md) |  | [optional] 
**grade** | **str** | Grade of the education. | [optional] 
**activities** | **str** | Activities and societies. Ex: Alpha Phi Omega, Marching Brand, Volleyball | [optional] 
**description** | **str** | Description of the education. | [optional] 
**skills** | [**List[NewExperienceSkillsInner]**](NewExperienceSkillsInner.md) | List of skills. We recommend adding your top 5 used in this training. They’ll also appear in your profile Skills section. | [optional] 
**attachment** | [**NewExperienceAttachment**](NewExperienceAttachment.md) |  | [optional] 
**attachment_title** | **str** | Title of the attachment. | [optional] 
**attachment_description** | **str** | Description of the attachment. | [optional] 

## Example

```python
from unipile.models.new_education import NewEducation

# TODO update the JSON string below
json = "{}"
# create an instance of NewEducation from a JSON string
new_education_instance = NewEducation.from_json(json)
# print the JSON string representation of the object
print(NewEducation.to_json())

# convert the object into a dict
new_education_dict = new_education_instance.to_dict()
# create an instance of NewEducation from a dict
new_education_from_dict = NewEducation.from_dict(new_education_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


