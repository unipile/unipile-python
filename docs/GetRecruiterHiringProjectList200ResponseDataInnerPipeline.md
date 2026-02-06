# GetRecruiterHiringProjectList200ResponseDataInnerPipeline

The pipeline of the Project.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** | Whether the pipeline is active. | 
**name** | **str** | The name of the Pipeline. | 
**description** | **str** | The description of the Pipeline. | 
**created_at** | **str** | The date on which the Pipeline was created. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_modified_at** | **str** | The date on which the Pipeline was last modified. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**stages** | [**List[GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner]**](GetRecruiterHiringProjectList200ResponseDataInnerPipelineStagesInner.md) | A list of stages that make up the Pipeline. | 

## Example

```python
from unipile.models.get_recruiter_hiring_project_list200_response_data_inner_pipeline import GetRecruiterHiringProjectList200ResponseDataInnerPipeline

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerPipeline from a JSON string
get_recruiter_hiring_project_list200_response_data_inner_pipeline_instance = GetRecruiterHiringProjectList200ResponseDataInnerPipeline.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterHiringProjectList200ResponseDataInnerPipeline.to_json())

# convert the object into a dict
get_recruiter_hiring_project_list200_response_data_inner_pipeline_dict = get_recruiter_hiring_project_list200_response_data_inner_pipeline_instance.to_dict()
# create an instance of GetRecruiterHiringProjectList200ResponseDataInnerPipeline from a dict
get_recruiter_hiring_project_list200_response_data_inner_pipeline_from_dict = GetRecruiterHiringProjectList200ResponseDataInnerPipeline.from_dict(get_recruiter_hiring_project_list200_response_data_inner_pipeline_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


