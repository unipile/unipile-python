# PublishClassicJobPostingRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**set_hiring_frame** | **bool** | Whether to add the hiring frame to you public profile picture. | [optional] [default to True]
**bypass_email_verification** | **bool** | Whether not to verify if you&#39;re allowed to post a job on behalf on the current company. | [optional] [default to False]
**mode** | **str** |  | 
**budget** | [**PublishInPromotedModeBudget**](PublishInPromotedModeBudget.md) |  | 

## Example

```python
from unipile.models.publish_classic_job_posting_request import PublishClassicJobPostingRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PublishClassicJobPostingRequest from a JSON string
publish_classic_job_posting_request_instance = PublishClassicJobPostingRequest.from_json(json)
# print the JSON string representation of the object
print(PublishClassicJobPostingRequest.to_json())

# convert the object into a dict
publish_classic_job_posting_request_dict = publish_classic_job_posting_request_instance.to_dict()
# create an instance of PublishClassicJobPostingRequest from a dict
publish_classic_job_posting_request_from_dict = PublishClassicJobPostingRequest.from_dict(publish_classic_job_posting_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


