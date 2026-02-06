# GetRecruiterPipelineCandidatesRequestRecruitingActivity

The most recent actions taken by the team regarding the candidate.    Native filter : Recruiting activity   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**timespan** | **str** | The time period from which to filter results.    Native filter : Within date range    | [optional] [default to 'ANYTIME']
**include** | **List[str]** |  | 
**exclude** | **List[str]** |  | 

## Example

```python
from unipile.models.get_recruiter_pipeline_candidates_request_recruiting_activity import GetRecruiterPipelineCandidatesRequestRecruitingActivity

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterPipelineCandidatesRequestRecruitingActivity from a JSON string
get_recruiter_pipeline_candidates_request_recruiting_activity_instance = GetRecruiterPipelineCandidatesRequestRecruitingActivity.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterPipelineCandidatesRequestRecruitingActivity.to_json())

# convert the object into a dict
get_recruiter_pipeline_candidates_request_recruiting_activity_dict = get_recruiter_pipeline_candidates_request_recruiting_activity_instance.to_dict()
# create an instance of GetRecruiterPipelineCandidatesRequestRecruitingActivity from a dict
get_recruiter_pipeline_candidates_request_recruiting_activity_from_dict = GetRecruiterPipelineCandidatesRequestRecruitingActivity.from_dict(get_recruiter_pipeline_candidates_request_recruiting_activity_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


