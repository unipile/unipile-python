# CreateClassicJobPostingDraftRequestJobTitle

The title of the job.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values. | [optional] 
**name** | **str** | The name of the job. | [optional] 

## Example

```python
from unipile.models.create_classic_job_posting_draft_request_job_title import CreateClassicJobPostingDraftRequestJobTitle

# TODO update the JSON string below
json = "{}"
# create an instance of CreateClassicJobPostingDraftRequestJobTitle from a JSON string
create_classic_job_posting_draft_request_job_title_instance = CreateClassicJobPostingDraftRequestJobTitle.from_json(json)
# print the JSON string representation of the object
print(CreateClassicJobPostingDraftRequestJobTitle.to_json())

# convert the object into a dict
create_classic_job_posting_draft_request_job_title_dict = create_classic_job_posting_draft_request_job_title_instance.to_dict()
# create an instance of CreateClassicJobPostingDraftRequestJobTitle from a dict
create_classic_job_posting_draft_request_job_title_from_dict = CreateClassicJobPostingDraftRequestJobTitle.from_dict(create_classic_job_posting_draft_request_job_title_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


