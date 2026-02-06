# PerformSalesPeopleSearchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**current_company** | [**PerformSalesPeopleSearchRequestCurrentCompany**](PerformSalesPeopleSearchRequestCurrentCompany.md) |  | [optional] 
**past_company** | [**PerformSalesPeopleSearchRequestPastCompany**](PerformSalesPeopleSearchRequestPastCompany.md) |  | [optional] 
**company_headcount** | [**List[PerformSalesPeopleSearchRequestCompanyHeadcountInner]**](PerformSalesPeopleSearchRequestCompanyHeadcountInner.md) | A list of headcount ranges. | [optional] 
**company_type** | **List[str]** | A list of company types. | [optional] 
**company_location** | [**PerformSalesPeopleSearchRequestCompanyLocation**](PerformSalesPeopleSearchRequestCompanyLocation.md) |  | [optional] 
**function** | [**PerformSalesPeopleSearchRequestFunction**](PerformSalesPeopleSearchRequestFunction.md) |  | [optional] 
**current_job_title** | [**PerformSalesPeopleSearchRequestCurrentJobTitle**](PerformSalesPeopleSearchRequestCurrentJobTitle.md) |  | [optional] 
**past_job_title** | [**PerformSalesPeopleSearchRequestPastJobTitle**](PerformSalesPeopleSearchRequestPastJobTitle.md) |  | [optional] 
**seniority** | [**PerformSalesPeopleSearchRequestSeniority**](PerformSalesPeopleSearchRequestSeniority.md) |  | [optional] 
**years_in_company** | [**List[PerformSalesPeopleSearchRequestYearsInCompanyInner]**](PerformSalesPeopleSearchRequestYearsInCompanyInner.md) | A list of years ranges. | [optional] 
**years_in_position** | [**List[PerformSalesPeopleSearchRequestYearsInPositionInner]**](PerformSalesPeopleSearchRequestYearsInPositionInner.md) | A list of years ranges. | [optional] 
**location** | [**PerformSalesPeopleSearchRequestLocation**](PerformSalesPeopleSearchRequestLocation.md) |  | [optional] 
**postal_code** | [**PerformSalesPeopleSearchRequestPostalCode**](PerformSalesPeopleSearchRequestPostalCode.md) |  | [optional] 
**industry** | [**PerformSalesPeopleSearchRequestIndustry**](PerformSalesPeopleSearchRequestIndustry.md) |  | [optional] 
**first_name** | **List[str]** | A list of names. | [optional] 
**last_name** | **List[str]** | A list of names. | [optional] 
**profile_language** | **List[str]** | A list of languages. | [optional] 
**years_of_experience** | [**List[PerformSalesPeopleSearchRequestYearsOfExperienceInner]**](PerformSalesPeopleSearchRequestYearsOfExperienceInner.md) | A list of years ranges. | [optional] 
**group** | [**PerformSalesPeopleSearchRequestGroup**](PerformSalesPeopleSearchRequestGroup.md) |  | [optional] 
**school** | [**PerformSalesPeopleSearchRequestSchool**](PerformSalesPeopleSearchRequestSchool.md) |  | [optional] 
**following_your_company** | **bool** | Whether the users are following your company.    Native filter : Buyer intent / Following your company    | [optional] 
**viewed_your_profile_recently** | **bool** | Whether the users visited your profile recently.    Native filter : Buyer intent / Viewed your profile recently    | [optional] 
**network_distance** | [**List[GetRecruiterTalentPoolApplicantsRequestNetworkDistanceInner]**](GetRecruiterTalentPoolApplicantsRequestNetworkDistanceInner.md) | A list of connection degrees (1 for First, 2 for Second, 3 for Third+ and GROUP for Common group members).    Native filter : Best path in / Connection    | [optional] 
**connections_of** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;RELATION&#x60; type to find out the possible values.    Native filter : Best path in / Connections of    | [optional] 
**past_colleague** | **bool** | Whether the users are past colleagues of yours.    Native filter : Best path in / Past colleague    | [optional] 
**shared_experiences** | **bool** | Whether the users share professionnal experiences with you.    Native filter : Buyer intent / Shared experiences    | [optional] 
**changed_jobs** | **bool** | Whether the users recently changed jobs.    Native filter : Recent updates / Changed jobs    | [optional] 
**posted_on_linkedin** | **bool** | Whether the users recently published posts on LinkedIn.    Native filter : Recent updates / Posted on Linkedin    | [optional] 
**persona** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;PERSONA&#x60; type to find out the possible values.    Native filter : Workflow / Persona    | [optional] 
**account_list** | [**PerformSalesPeopleSearchRequestAccountList**](PerformSalesPeopleSearchRequestAccountList.md) |  | [optional] 
**lead_list** | [**PerformSalesPeopleSearchRequestLeadList**](PerformSalesPeopleSearchRequestLeadList.md) |  | [optional] 
**recent_interaction** | [**PerformSalesPeopleSearchRequestRecentInteraction**](PerformSalesPeopleSearchRequestRecentInteraction.md) |  | [optional] 
**saved_resources** | [**PerformSalesPeopleSearchRequestSavedResources**](PerformSalesPeopleSearchRequestSavedResources.md) |  | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request import PerformSalesPeopleSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequest from a JSON string
perform_sales_people_search_request_instance = PerformSalesPeopleSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequest.to_json())

# convert the object into a dict
perform_sales_people_search_request_dict = perform_sales_people_search_request_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequest from a dict
perform_sales_people_search_request_from_dict = PerformSalesPeopleSearchRequest.from_dict(perform_sales_people_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


