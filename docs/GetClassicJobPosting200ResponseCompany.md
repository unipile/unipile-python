# GetClassicJobPosting200ResponseCompany

The company that published the Job posting.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**name** | **str** | The name of the Company. | 
**public_picture_url** | **str** | The public picture URL of the Company. | [optional] 
**profile_url** | **str** | The profile URL of the Company. | [optional] 
**public_identifier** | **str** | The public identifier of the Company. | [optional] 

## Example

```python
from unipile.models.get_classic_job_posting200_response_company import GetClassicJobPosting200ResponseCompany

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicJobPosting200ResponseCompany from a JSON string
get_classic_job_posting200_response_company_instance = GetClassicJobPosting200ResponseCompany.from_json(json)
# print the JSON string representation of the object
print(GetClassicJobPosting200ResponseCompany.to_json())

# convert the object into a dict
get_classic_job_posting200_response_company_dict = get_classic_job_posting200_response_company_instance.to_dict()
# create an instance of GetClassicJobPosting200ResponseCompany from a dict
get_classic_job_posting200_response_company_from_dict = GetClassicJobPosting200ResponseCompany.from_dict(get_classic_job_posting200_response_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


