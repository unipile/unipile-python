# PipelineCandidatesSearchDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**profile** | [**ApplicantsSearchDataInnerProfile**](ApplicantsSearchDataInnerProfile.md) |  | 

## Example

```python
from unipile.models.pipeline_candidates_search_data_inner import PipelineCandidatesSearchDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PipelineCandidatesSearchDataInner from a JSON string
pipeline_candidates_search_data_inner_instance = PipelineCandidatesSearchDataInner.from_json(json)
# print the JSON string representation of the object
print(PipelineCandidatesSearchDataInner.to_json())

# convert the object into a dict
pipeline_candidates_search_data_inner_dict = pipeline_candidates_search_data_inner_instance.to_dict()
# create an instance of PipelineCandidatesSearchDataInner from a dict
pipeline_candidates_search_data_inner_from_dict = PipelineCandidatesSearchDataInner.from_dict(pipeline_candidates_search_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


