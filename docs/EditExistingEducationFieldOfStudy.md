# EditExistingEducationFieldOfStudy

Field of study of the education.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;FIELD_OF_STUDY&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.edit_existing_education_field_of_study import EditExistingEducationFieldOfStudy

# TODO update the JSON string below
json = "{}"
# create an instance of EditExistingEducationFieldOfStudy from a JSON string
edit_existing_education_field_of_study_instance = EditExistingEducationFieldOfStudy.from_json(json)
# print the JSON string representation of the object
print(EditExistingEducationFieldOfStudy.to_json())

# convert the object into a dict
edit_existing_education_field_of_study_dict = edit_existing_education_field_of_study_instance.to_dict()
# create an instance of EditExistingEducationFieldOfStudy from a dict
edit_existing_education_field_of_study_from_dict = EditExistingEducationFieldOfStudy.from_dict(edit_existing_education_field_of_study_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


