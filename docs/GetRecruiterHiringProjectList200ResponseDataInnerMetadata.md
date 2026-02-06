# GetRecruiterHiringProjectList200ResponseDataInnerMetadata

Metadata on the Project.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_title** | **str** | The job title of the Project. | [optional] 
**job_posting_id** | **str** | The job posting ID of the Project. | [optional] 
**locations** | [**List[GetRecruiterHiringProjectList200ResponseDataInnerMetadataLocationsInner]**](GetRecruiterHiringProjectList200ResponseDataInnerMetadataLocationsInner.md) | A list of locations associated with the Project. | 
**seniority_level** | **str** | The seniority level of the Project. | [optional] 
**employment_type** | **str** | The employment type of the Project. | [optional] 
**industries** | **List[Optional[str]]** | A list of industries associated with the the Project. | 
**company** | [**GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany**](GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany.md) |  | [optional] 

## Example

```python
from unipile.models.get_recruiter_hiring_project_list200_response_data_inner_metadata import GetRecruiterHiringProjectList200ResponseDataInnerMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerMetadata from a JSON string
get_recruiter_hiring_project_list200_response_data_inner_metadata_instance = GetRecruiterHiringProjectList200ResponseDataInnerMetadata.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterHiringProjectList200ResponseDataInnerMetadata.to_json())

# convert the object into a dict
get_recruiter_hiring_project_list200_response_data_inner_metadata_dict = get_recruiter_hiring_project_list200_response_data_inner_metadata_instance.to_dict()
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerMetadata from a dict
get_recruiter_hiring_project_list200_response_data_inner_metadata_from_dict = GetRecruiterHiringProjectList200ResponseDataInnerMetadata.from_dict(get_recruiter_hiring_project_list200_response_data_inner_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


