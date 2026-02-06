# PerformRecruiterPeopleSearchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**network_distance** | [**List[GetRecruiterTalentPoolApplicantsRequestNetworkDistanceInner]**](GetRecruiterTalentPoolApplicantsRequestNetworkDistanceInner.md) | A list of connection degrees (1 for First, 2 for Second, 3 for Third+ and GROUP for Common group members).    Native filter : Connections    | [optional] 
**location** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner.md) | A list of locations. | [optional] 
**postal_code** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestPostalCodeInner.md) | A list of postal codes. | [optional] 
**postal_code_radius** | **float** | The distance radius around the postal code in miles.    Native filter : Within area    | [optional] 
**job_title** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner.md) | A list of job titles. | [optional] 
**occupation** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner.md) | A list of occupations. | [optional] 
**skills** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner.md) | A list of skills. | [optional] 
**company** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestCompanyInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestCompanyInner.md) | A list of companies. | [optional] 
**company_size** | [**List[GetRecruiterTalentPoolApplicantsRequestCompanySizeInner]**](GetRecruiterTalentPoolApplicantsRequestCompanySizeInner.md) | A list of company size ranges. | [optional] 
**years_of_experience** | [**GetRecruiterTalentPoolApplicantsRequestYearsOfExperience**](GetRecruiterTalentPoolApplicantsRequestYearsOfExperience.md) |  | [optional] 
**school** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestSchoolInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestSchoolInner.md) | A list of schools. | [optional] 
**graduation_year** | [**PerformRecruiterPeopleSearchFromTalentPoolRequestGraduationYear**](PerformRecruiterPeopleSearchFromTalentPoolRequestGraduationYear.md) |  | [optional] 
**industry** | [**PerformRecruiterPeopleSearchFromTalentPoolRequestIndustry**](PerformRecruiterPeopleSearchFromTalentPoolRequestIndustry.md) |  | [optional] 
**seniority** | **List[str]** | A list of senorities. | [optional] 
**profile_language** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;PROFILE_LANGUAGE&#x60; type to find out the possible values.    Native filter : Profile languages    | [optional] 
**project** | [**PerformRecruiterPeopleSearchFromTalentPoolRequestProject**](PerformRecruiterPeopleSearchFromTalentPoolRequestProject.md) |  | [optional] 
**function** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_FUNCTION&#x60; type to find out the possible values.    Native filter : Job functions    | [optional] 
**first_name** | **List[str]** | A list of names. | [optional] 
**last_name** | **List[str]** | A list of names. | [optional] 
**recently_joined** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestRecentlyJoinedInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestRecentlyJoinedInner.md) | A list of days ranges. | [optional] 
**is_military_veteran** | **bool** | Whether the users should have military background.    Native filter : Military veterans    | [optional] 
**recruiting_activity** | [**List[PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner]**](PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner.md) | A list of recruiting activities. | [optional] 
**hide_previously_viewed** | [**PerformRecruiterPeopleSearchFromTalentPoolRequestHidePreviouslyViewed**](PerformRecruiterPeopleSearchFromTalentPoolRequestHidePreviouslyViewed.md) |  | [optional] 
**group** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;GROUP&#x60; type to find out the possible values.    Native filter : All groups    | [optional] 
**is_past_applicant** | **bool** | Whether the users should have already applied to at least one of your job postings.    Native filter : Past applicants    | [optional] 
**notes** | **List[str]** | A list of notes. | [optional] 

## Example

```python
from unipile.models.perform_recruiter_people_search_request import PerformRecruiterPeopleSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchRequest from a JSON string
perform_recruiter_people_search_request_instance = PerformRecruiterPeopleSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchRequest.to_json())

# convert the object into a dict
perform_recruiter_people_search_request_dict = perform_recruiter_people_search_request_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchRequest from a dict
perform_recruiter_people_search_request_from_dict = PerformRecruiterPeopleSearchRequest.from_dict(perform_recruiter_people_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


