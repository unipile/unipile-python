# PipelineSourced


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **str** |  | 
**project_id** | **str** | The ID of the Project the Pipeline belongs to. | 
**stage_id** | **str** | In Pipeline context, the ID of the Stage to get parameters from. Leave undefined to get results from all stages. | [optional] 
**keywords** | **str** | A keyword or group of keywords to filter results. Applicable to SEAT only. | [optional] 
**type** | **str** | The type of search parameter. | 

## Example

```python
from unipile.models.pipeline_sourced import PipelineSourced

# TODO update the JSON string below
json = "{}"
# create an instance of PipelineSourced from a JSON string
pipeline_sourced_instance = PipelineSourced.from_json(json)
# print the JSON string representation of the object
print(PipelineSourced.to_json())

# convert the object into a dict
pipeline_sourced_dict = pipeline_sourced_instance.to_dict()
# create an instance of PipelineSourced from a dict
pipeline_sourced_from_dict = PipelineSourced.from_dict(pipeline_sourced_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


