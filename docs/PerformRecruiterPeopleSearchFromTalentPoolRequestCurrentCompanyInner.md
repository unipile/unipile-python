# PerformRecruiterPeopleSearchFromTalentPoolRequestCurrentCompanyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values. | 
**priority** | **str** | Whether the user can, must or shouldn&#39;t have the value.    Native filter : Priority    | [optional] [default to 'CAN_HAVE']

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_current_company_inner import PerformRecruiterPeopleSearchFromTalentPoolRequestCurrentCompanyInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestCurrentCompanyInner from a JSON string
perform_recruiter_people_search_from_talent_pool_request_current_company_inner_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestCurrentCompanyInner.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestCurrentCompanyInner.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_current_company_inner_dict = perform_recruiter_people_search_from_talent_pool_request_current_company_inner_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestCurrentCompanyInner from a dict
perform_recruiter_people_search_from_talent_pool_request_current_company_inner_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestCurrentCompanyInner.from_dict(perform_recruiter_people_search_from_talent_pool_request_current_company_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


