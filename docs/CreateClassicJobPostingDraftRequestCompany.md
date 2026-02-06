# CreateClassicJobPostingDraftRequestCompany

The company on whose behalf the job is created.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from unipile.models.create_classic_job_posting_draft_request_company import CreateClassicJobPostingDraftRequestCompany

# TODO update the JSON string below
json = "{}"
# create an instance of CreateClassicJobPostingDraftRequestCompany from a JSON string
create_classic_job_posting_draft_request_company_instance = CreateClassicJobPostingDraftRequestCompany.from_json(json)
# print the JSON string representation of the object
print(CreateClassicJobPostingDraftRequestCompany.to_json())

# convert the object into a dict
create_classic_job_posting_draft_request_company_dict = create_classic_job_posting_draft_request_company_instance.to_dict()
# create an instance of CreateClassicJobPostingDraftRequestCompany from a dict
create_classic_job_posting_draft_request_company_from_dict = CreateClassicJobPostingDraftRequestCompany.from_dict(create_classic_job_posting_draft_request_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


