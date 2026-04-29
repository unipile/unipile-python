# CreateNewEducationDegree

Degree of the education.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The ID of the Company. | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;DEGREE&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.create_new_education_degree import CreateNewEducationDegree

# TODO update the JSON string below
json = "{}"
# create an instance of CreateNewEducationDegree from a JSON string
create_new_education_degree_instance = CreateNewEducationDegree.from_json(json)
# print the JSON string representation of the object
print(CreateNewEducationDegree.to_json())

# convert the object into a dict
create_new_education_degree_dict = create_new_education_degree_instance.to_dict()
# create an instance of CreateNewEducationDegree from a dict
create_new_education_degree_from_dict = CreateNewEducationDegree.from_dict(create_new_education_degree_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


