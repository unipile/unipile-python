# PublishRecruiterJobPostingRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bypass_email_verification** | **bool** | Whether not to verify if you&#39;re allowed to post a job on behalf on the current company. | [optional] [default to False]
**mode** | **str** |  | 
**budget** | [**PublishInPromotedMode1Budget**](PublishInPromotedMode1Budget.md) |  | [optional] 

## Example

```python
from unipile.models.publish_recruiter_job_posting_request import PublishRecruiterJobPostingRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PublishRecruiterJobPostingRequest from a JSON string
publish_recruiter_job_posting_request_instance = PublishRecruiterJobPostingRequest.from_json(json)
# print the JSON string representation of the object
print(PublishRecruiterJobPostingRequest.to_json())

# convert the object into a dict
publish_recruiter_job_posting_request_dict = publish_recruiter_job_posting_request_instance.to_dict()
# create an instance of PublishRecruiterJobPostingRequest from a dict
publish_recruiter_job_posting_request_from_dict = PublishRecruiterJobPostingRequest.from_dict(publish_recruiter_job_posting_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


