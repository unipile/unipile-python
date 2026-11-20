# GetRecruiterTalentPoolApplyStartersRequestCompany

    Native filter : Companies   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.get_recruiter_talent_pool_apply_starters_request_company import GetRecruiterTalentPoolApplyStartersRequestCompany

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterTalentPoolApplyStartersRequestCompany from a JSON string
get_recruiter_talent_pool_apply_starters_request_company_instance = GetRecruiterTalentPoolApplyStartersRequestCompany.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterTalentPoolApplyStartersRequestCompany.to_json())

# convert the object into a dict
get_recruiter_talent_pool_apply_starters_request_company_dict = get_recruiter_talent_pool_apply_starters_request_company_instance.to_dict()
# create an instance of GetRecruiterTalentPoolApplyStartersRequestCompany from a dict
get_recruiter_talent_pool_apply_starters_request_company_from_dict = GetRecruiterTalentPoolApplyStartersRequestCompany.from_dict(get_recruiter_talent_pool_apply_starters_request_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


