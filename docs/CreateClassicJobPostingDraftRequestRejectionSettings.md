# CreateClassicJobPostingDraftRequestRejectionSettings

The settings for automated rejection system.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reject_unqualified_applicants** | **bool** | Whether to filter out and send rejections to applicants who don’t meet any must-have qualifications. | [optional] [default to True]
**rejection_template** | **str** | The textual content that will be sent to rejected applicants. | [optional] 

## Example

```python
from unipile.models.create_classic_job_posting_draft_request_rejection_settings import CreateClassicJobPostingDraftRequestRejectionSettings

# TODO update the JSON string below
json = "{}"
# create an instance of CreateClassicJobPostingDraftRequestRejectionSettings from a JSON string
create_classic_job_posting_draft_request_rejection_settings_instance = CreateClassicJobPostingDraftRequestRejectionSettings.from_json(json)
# print the JSON string representation of the object
print(CreateClassicJobPostingDraftRequestRejectionSettings.to_json())

# convert the object into a dict
create_classic_job_posting_draft_request_rejection_settings_dict = create_classic_job_posting_draft_request_rejection_settings_instance.to_dict()
# create an instance of CreateClassicJobPostingDraftRequestRejectionSettings from a dict
create_classic_job_posting_draft_request_rejection_settings_from_dict = CreateClassicJobPostingDraftRequestRejectionSettings.from_dict(create_classic_job_posting_draft_request_rejection_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


