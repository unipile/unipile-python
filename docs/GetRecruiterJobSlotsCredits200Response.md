# GetRecruiterJobSlotsCredits200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**total** | **float** | The total amount of Job slots for your Recruiter contract. | 
**used** | **float** | The amount of Job slots currently in use for your Recruiter contract. | 
**available** | **float** | The available amount of Job slots for your Recruiter contract. | 

## Example

```python
from unipile.models.get_recruiter_job_slots_credits200_response import GetRecruiterJobSlotsCredits200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterJobSlotsCredits200Response from a JSON string
get_recruiter_job_slots_credits200_response_instance = GetRecruiterJobSlotsCredits200Response.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterJobSlotsCredits200Response.to_json())

# convert the object into a dict
get_recruiter_job_slots_credits200_response_dict = get_recruiter_job_slots_credits200_response_instance.to_dict()
# create an instance of GetRecruiterJobSlotsCredits200Response from a dict
get_recruiter_job_slots_credits200_response_from_dict = GetRecruiterJobSlotsCredits200Response.from_dict(get_recruiter_job_slots_credits200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


