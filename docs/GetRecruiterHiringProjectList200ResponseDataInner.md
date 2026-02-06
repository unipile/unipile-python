# GetRecruiterHiringProjectList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the Project. | 
**name** | **str** | The name of the Project. | 
**readonly** | **bool** | Whether the Project is read only. | 
**created_at** | **str** | The date on which the Project was created. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_accessed_at** | **str** | The date on which the Project was last accessed. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**last_modified_at** | **str** | The date on which the Project was last modified. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**visibility** | **str** | The visibility level of the Project. | 
**owner** | [**GetRecruiterHiringProjectList200ResponseDataInnerOwner**](GetRecruiterHiringProjectList200ResponseDataInnerOwner.md) |  | 
**metadata** | [**GetRecruiterHiringProjectList200ResponseDataInnerMetadata**](GetRecruiterHiringProjectList200ResponseDataInnerMetadata.md) |  | 
**talent_pool** | [**GetRecruiterHiringProjectList200ResponseDataInnerTalentPool**](GetRecruiterHiringProjectList200ResponseDataInnerTalentPool.md) |  | 
**pipeline** | [**GetRecruiterHiringProjectList200ResponseDataInnerPipeline**](GetRecruiterHiringProjectList200ResponseDataInnerPipeline.md) |  | 

## Example

```python
from unipile.models.get_recruiter_hiring_project_list200_response_data_inner import GetRecruiterHiringProjectList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterHiringProjectList200ResponseDataInner from a JSON string
get_recruiter_hiring_project_list200_response_data_inner_instance = GetRecruiterHiringProjectList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterHiringProjectList200ResponseDataInner.to_json())

# convert the object into a dict
get_recruiter_hiring_project_list200_response_data_inner_dict = get_recruiter_hiring_project_list200_response_data_inner_instance.to_dict()
# create an instance of GetRecruiterHiringProjectList200ResponseDataInner from a dict
get_recruiter_hiring_project_list200_response_data_inner_from_dict = GetRecruiterHiringProjectList200ResponseDataInner.from_dict(get_recruiter_hiring_project_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


