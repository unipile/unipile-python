# CreateRecruiterHiringProjectRequestCompany

The company on whose behalf the project is created.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name** | **str** | The name of the company. | [optional] 

## Example

```python
from unipile.models.create_recruiter_hiring_project_request_company import CreateRecruiterHiringProjectRequestCompany

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRecruiterHiringProjectRequestCompany from a JSON string
create_recruiter_hiring_project_request_company_instance = CreateRecruiterHiringProjectRequestCompany.from_json(json)
# print the JSON string representation of the object
print(CreateRecruiterHiringProjectRequestCompany.to_json())

# convert the object into a dict
create_recruiter_hiring_project_request_company_dict = create_recruiter_hiring_project_request_company_instance.to_dict()
# create an instance of CreateRecruiterHiringProjectRequestCompany from a dict
create_recruiter_hiring_project_request_company_from_dict = CreateRecruiterHiringProjectRequestCompany.from_dict(create_recruiter_hiring_project_request_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


