# EditExistingEducationSchool

School of the education.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SCHOOL&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.edit_existing_education_school import EditExistingEducationSchool

# TODO update the JSON string below
json = "{}"
# create an instance of EditExistingEducationSchool from a JSON string
edit_existing_education_school_instance = EditExistingEducationSchool.from_json(json)
# print the JSON string representation of the object
print(EditExistingEducationSchool.to_json())

# convert the object into a dict
edit_existing_education_school_dict = edit_existing_education_school_instance.to_dict()
# create an instance of EditExistingEducationSchool from a dict
edit_existing_education_school_from_dict = EditExistingEducationSchool.from_dict(edit_existing_education_school_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


