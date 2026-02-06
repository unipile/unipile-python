# GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the Stage. | 
**type** | **str** | The type of the Stage. | 
**name** | **str** | The name of the Stage. | 
**candidates_count** | **float** | The number of candidates ranked at this Stage. | 
**accepts_candidates** | **bool** | Whether candidates can be ranked at this Stage. | 

## Example

```python
from unipile.models.get_recruiter_hiring_project_list200_response_data_inner_pipeline_stages_inner import GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner from a JSON string
get_recruiter_hiring_project_list200_response_data_inner_pipeline_stages_inner_instance = GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner.to_json())

# convert the object into a dict
get_recruiter_hiring_project_list200_response_data_inner_pipeline_stages_inner_dict = get_recruiter_hiring_project_list200_response_data_inner_pipeline_stages_inner_instance.to_dict()
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner from a dict
get_recruiter_hiring_project_list200_response_data_inner_pipeline_stages_inner_from_dict = GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner.from_dict(get_recruiter_hiring_project_list200_response_data_inner_pipeline_stages_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


