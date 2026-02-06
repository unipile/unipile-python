# CreateClassicJobPostingDraftRequestApplyMethod

The apply method, either `linkedin` or `external`.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**method** | **str** |  | 
**notification_email** | **str** | An email address to get updates about applicants. | 
**website_url** | **str** | The website on which applications should be made. | 

## Example

```python
from unipile.models.create_classic_job_posting_draft_request_apply_method import CreateClassicJobPostingDraftRequestApplyMethod

# TODO update the JSON string below
json = "{}"
# create an instance of CreateClassicJobPostingDraftRequestApplyMethod from a JSON string
create_classic_job_posting_draft_request_apply_method_instance = CreateClassicJobPostingDraftRequestApplyMethod.from_json(json)
# print the JSON string representation of the object
print(CreateClassicJobPostingDraftRequestApplyMethod.to_json())

# convert the object into a dict
create_classic_job_posting_draft_request_apply_method_dict = create_classic_job_posting_draft_request_apply_method_instance.to_dict()
# create an instance of CreateClassicJobPostingDraftRequestApplyMethod from a dict
create_classic_job_posting_draft_request_apply_method_from_dict = CreateClassicJobPostingDraftRequestApplyMethod.from_dict(create_classic_job_posting_draft_request_apply_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


