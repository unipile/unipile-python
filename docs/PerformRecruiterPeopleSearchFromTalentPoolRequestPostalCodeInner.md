# PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The postal code location name. | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;ZIPCODE&#x60; type to find out the possible values.    Native filter : Postal code / Zip code    | 

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_postal_code_inner import PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner from a JSON string
perform_recruiter_people_search_from_talent_pool_request_postal_code_inner_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_postal_code_inner_dict = perform_recruiter_people_search_from_talent_pool_request_postal_code_inner_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner from a dict
perform_recruiter_people_search_from_talent_pool_request_postal_code_inner_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner.from_dict(perform_recruiter_people_search_from_talent_pool_request_postal_code_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


