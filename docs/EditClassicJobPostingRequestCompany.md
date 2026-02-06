# EditClassicJobPostingRequestCompany

The company on whose behalf the job is created.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from unipile.models.edit_classic_job_posting_request_company import EditClassicJobPostingRequestCompany

# TODO update the JSON string below
json = "{}"
# create an instance of EditClassicJobPostingRequestCompany from a JSON string
edit_classic_job_posting_request_company_instance = EditClassicJobPostingRequestCompany.from_json(json)
# print the JSON string representation of the object
print(EditClassicJobPostingRequestCompany.to_json())

# convert the object into a dict
edit_classic_job_posting_request_company_dict = edit_classic_job_posting_request_company_instance.to_dict()
# create an instance of EditClassicJobPostingRequestCompany from a dict
edit_classic_job_posting_request_company_from_dict = EditClassicJobPostingRequestCompany.from_dict(edit_classic_job_posting_request_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


