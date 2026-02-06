# GetRecruiterHiringProject200ResponseMetadata

Metadata on the Project.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_title** | **str** | The job title of the Project. | [optional] 
**job_posting_id** | **str** | The job posting ID of the Project. | [optional] 
**locations** | [**List[GetRecruiterHiringProjectList200ResponseDataInnerMetadataLocationsInner]**](GetRecruiterHiringProjectList200ResponseDataInnerMetadataLocationsInner.md) | A list of locations associated with the Project. | 
**seniority_level** | **str** | The seniority level of the Project. | [optional] 
**employment_type** | **str** | The employment type of the Project. | [optional] 
**industries** | **List[str]** | A list of industries associated with the the Project. | 
**company** | [**GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany**](GetRecruiterHiringProjectList200ResponseDataInnerMetadataCompany.md) |  | [optional] 

## Example

```python
from unipile.models.get_recruiter_hiring_project200_response_metadata import GetRecruiterHiringProject200ResponseMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterHiringProject200ResponseMetadata from a JSON string
get_recruiter_hiring_project200_response_metadata_instance = GetRecruiterHiringProject200ResponseMetadata.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterHiringProject200ResponseMetadata.to_json())

# convert the object into a dict
get_recruiter_hiring_project200_response_metadata_dict = get_recruiter_hiring_project200_response_metadata_instance.to_dict()
# create an instance of GetRecruiterHiringProject200ResponseMetadata from a dict
get_recruiter_hiring_project200_response_metadata_from_dict = GetRecruiterHiringProject200ResponseMetadata.from_dict(get_recruiter_hiring_project200_response_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


