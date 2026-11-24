# GetRecruiterTalentPoolApplyStartersRequestCurrentCompany

    Native filter : Current companies   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;CURRENT_COMPANY&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;CURRENT_COMPANY&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.get_recruiter_talent_pool_apply_starters_request_current_company import GetRecruiterTalentPoolApplyStartersRequestCurrentCompany

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterTalentPoolApplyStartersRequestCurrentCompany from a JSON string
get_recruiter_talent_pool_apply_starters_request_current_company_instance = GetRecruiterTalentPoolApplyStartersRequestCurrentCompany.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterTalentPoolApplyStartersRequestCurrentCompany.to_json())

# convert the object into a dict
get_recruiter_talent_pool_apply_starters_request_current_company_dict = get_recruiter_talent_pool_apply_starters_request_current_company_instance.to_dict()
# create an instance of GetRecruiterTalentPoolApplyStartersRequestCurrentCompany from a dict
get_recruiter_talent_pool_apply_starters_request_current_company_from_dict = GetRecruiterTalentPoolApplyStartersRequestCurrentCompany.from_dict(get_recruiter_talent_pool_apply_starters_request_current_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


