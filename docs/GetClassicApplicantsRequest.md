# GetClassicApplicantsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ratings** | **List[str]** | A list of ratings to filter applicants. | [optional] [default to ["UNRATED","MAYBE","GOOD_FIT"]]
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**sort_by** | **str** | The sort method. | [optional] [default to 'APPLIED_DATE']
**location** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values.    Native filter : Location    | [optional] 
**years_of_experience** | [**List[GetClassicApplicantsRequestYearsOfExperienceInner]**](GetClassicApplicantsRequestYearsOfExperienceInner.md) | A list of years ranges. | [optional] 
**skills** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SKILL&#x60; type to find out the possible values.    Native filter : Skilled in    | [optional] 

## Example

```python
from unipile.models.get_classic_applicants_request import GetClassicApplicantsRequest

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicApplicantsRequest from a JSON string
get_classic_applicants_request_instance = GetClassicApplicantsRequest.from_json(json)
# print the JSON string representation of the object
print(GetClassicApplicantsRequest.to_json())

# convert the object into a dict
get_classic_applicants_request_dict = get_classic_applicants_request_instance.to_dict()
# create an instance of GetClassicApplicantsRequest from a dict
get_classic_applicants_request_from_dict = GetClassicApplicantsRequest.from_dict(get_classic_applicants_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


