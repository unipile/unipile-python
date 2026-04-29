# CreateNewEducationFieldOfStudy

Field of study of the education.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The ID of the Company. | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;FIELD_OF_STUDY&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.create_new_education_field_of_study import CreateNewEducationFieldOfStudy

# TODO update the JSON string below
json = "{}"
# create an instance of CreateNewEducationFieldOfStudy from a JSON string
create_new_education_field_of_study_instance = CreateNewEducationFieldOfStudy.from_json(json)
# print the JSON string representation of the object
print(CreateNewEducationFieldOfStudy.to_json())

# convert the object into a dict
create_new_education_field_of_study_dict = create_new_education_field_of_study_instance.to_dict()
# create an instance of CreateNewEducationFieldOfStudy from a dict
create_new_education_field_of_study_from_dict = CreateNewEducationFieldOfStudy.from_dict(create_new_education_field_of_study_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


