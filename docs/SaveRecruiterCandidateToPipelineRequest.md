# SaveRecruiterCandidateToPipelineRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**stage_id** | **str** | The ID of the Pipeline stage. | 
**candidate_id** | **str** | The ID of the Candidate (or the User Profile ID) to be saved to the Pipeline. | 

## Example

```python
from unipile.models.save_recruiter_candidate_to_pipeline_request import SaveRecruiterCandidateToPipelineRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SaveRecruiterCandidateToPipelineRequest from a JSON string
save_recruiter_candidate_to_pipeline_request_instance = SaveRecruiterCandidateToPipelineRequest.from_json(json)
# print the JSON string representation of the object
print(SaveRecruiterCandidateToPipelineRequest.to_json())

# convert the object into a dict
save_recruiter_candidate_to_pipeline_request_dict = save_recruiter_candidate_to_pipeline_request_instance.to_dict()
# create an instance of SaveRecruiterCandidateToPipelineRequest from a dict
save_recruiter_candidate_to_pipeline_request_from_dict = SaveRecruiterCandidateToPipelineRequest.from_dict(save_recruiter_candidate_to_pipeline_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


