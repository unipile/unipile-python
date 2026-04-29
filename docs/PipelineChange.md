# PipelineChange


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**last_updated_at** | **str** | The time at which the activity was updated. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_updated_by** | [**LinkedInProjectsInnerContributorsInner**](LinkedInProjectsInnerContributorsInner.md) |  | 
**event** | **str** | The type of event. | 
**project_id** | **str** | The ID of the project the user is related to. | 
**project_name** | **str** | The name of the project the user is related to. | 
**pipeline_stage** | **str** | The pipeline stage the user was added/moved to. | 

## Example

```python
from unipile.models.pipeline_change import PipelineChange

# TODO update the JSON string below
json = "{}"
# create an instance of PipelineChange from a JSON string
pipeline_change_instance = PipelineChange.from_json(json)
# print the JSON string representation of the object
print(PipelineChange.to_json())

# convert the object into a dict
pipeline_change_dict = pipeline_change_instance.to_dict()
# create an instance of PipelineChange from a dict
pipeline_change_from_dict = PipelineChange.from_dict(pipeline_change_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


