# GetRecruiterHiringProject200Response


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
**metadata** | [**GetRecruiterHiringProject200ResponseMetadata**](GetRecruiterHiringProject200ResponseMetadata.md) |  | 
**talent_pool** | [**GetRecruiterHiringProjectList200ResponseDataInnerTalentPool**](GetRecruiterHiringProjectList200ResponseDataInnerTalentPool.md) |  | 
**pipeline** | [**GetRecruiterHiringProjectList200ResponseDataInnerPipeline**](GetRecruiterHiringProjectList200ResponseDataInnerPipeline.md) |  | 

## Example

```python
from unipile.models.get_recruiter_hiring_project200_response import GetRecruiterHiringProject200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterHiringProject200Response from a JSON string
get_recruiter_hiring_project200_response_instance = GetRecruiterHiringProject200Response.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterHiringProject200Response.to_json())

# convert the object into a dict
get_recruiter_hiring_project200_response_dict = get_recruiter_hiring_project200_response_instance.to_dict()
# create an instance of GetRecruiterHiringProject200Response from a dict
get_recruiter_hiring_project200_response_from_dict = GetRecruiterHiringProject200Response.from_dict(get_recruiter_hiring_project200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


