# GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany

The company on whose behalf the Project was created.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the Company. | 
**name** | **str** | The name of the Company. | 
**location** | **str** | The location of the Company. | 
**description** | **str** | The description of the Company. | 
**url** | **str** | The website URL of the Company. | 
**industries** | **List[str]** | A list of industries associated with the the Company. | 

## Example

```python
from unipile.models.get_recruiter_hiring_project_list200_response_data_inner_metadata_company import GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany from a JSON string
get_recruiter_hiring_project_list200_response_data_inner_metadata_company_instance = GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany.to_json())

# convert the object into a dict
get_recruiter_hiring_project_list200_response_data_inner_metadata_company_dict = get_recruiter_hiring_project_list200_response_data_inner_metadata_company_instance.to_dict()
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany from a dict
get_recruiter_hiring_project_list200_response_data_inner_metadata_company_from_dict = GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany.from_dict(get_recruiter_hiring_project_list200_response_data_inner_metadata_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


