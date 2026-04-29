# CreateNewEducation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**notify_network** | **bool** | Notify the network about the education. Turn on to notify your network of key profile changes (such as new education) and work anniversaries. | [optional] [default to False]
**school** | [**CreateNewEducationSchool**](CreateNewEducationSchool.md) |  | 
**degree** | [**CreateNewEducationDegree**](CreateNewEducationDegree.md) |  | [optional] 
**field_of_study** | [**CreateNewEducationFieldOfStudy**](CreateNewEducationFieldOfStudy.md) |  | [optional] 
**start_date** | [**CreateNewEducationStartDate**](CreateNewEducationStartDate.md) |  | 
**end_date** | [**CreateNewEducationEndDate**](CreateNewEducationEndDate.md) |  | [optional] 
**grade** | **str** | Grade of the education. | [optional] 
**activities** | **str** | Activities and societies. Ex: Alpha Phi Omega, Marching Brand, Volleyball | [optional] 
**description** | **str** | Description of the education. | [optional] 
**skills** | [**List[CreateNewExperienceSkillsInner]**](CreateNewExperienceSkillsInner.md) | List of skills. We recommend adding your top 5 used in this training. They’ll also appear in your profile Skills section. | [optional] 
**media** | [**CreateNewExperienceMedia**](CreateNewExperienceMedia.md) |  | [optional] 
**operation** | **str** |  | 

## Example

```python
from unipile.models.create_new_education import CreateNewEducation

# TODO update the JSON string below
json = "{}"
# create an instance of CreateNewEducation from a JSON string
create_new_education_instance = CreateNewEducation.from_json(json)
# print the JSON string representation of the object
print(CreateNewEducation.to_json())

# convert the object into a dict
create_new_education_dict = create_new_education_instance.to_dict()
# create an instance of CreateNewEducation from a dict
create_new_education_from_dict = CreateNewEducation.from_dict(create_new_education_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


