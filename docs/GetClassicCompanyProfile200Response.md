# GetClassicCompanyProfile200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the Company for the provider. | 
**name** | **str** | The name of the Company. | 
**public_identifier** | **str** | The public identifier of the Company. | 
**profile_url** | **str** | The public profile URL of the Company. | 
**object** | **str** |  | 
**description** | **str** | The description of the Company. | [optional] 
**public_picture_url** | **str** | The public picture URL of the Company. | [optional] 
**tagline** | **str** | The tagline of the Company. | [optional] 
**followers_count** | **float** | The number of followers of the Company. | 
**is_school** | **bool** | Whether the Company is a school. | 
**is_active** | **bool** | Whether the Company is currently in activity. | 
**is_archived** | **bool** | Whether the Company has been archived. | 
**is_following** | **bool** | Whether the current user is following the Company. | 
**is_employee** | **bool** | Whether the current user is an employee of the Company. | 
**is_verified** | **bool** | Whether the Company has been verified. | 
**is_claimable** | **bool** | Whether the Company can be claimed. | 
**is_claimable_by_viewer** | **bool** | Whether the Company can be claimed by the current user. | 
**verified_at** | **str** | The date on which the Company was verified. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**mailbox** | [**GetClassicCompanyProfile200ResponseMailbox**](GetClassicCompanyProfile200ResponseMailbox.md) |  | 
**viewer_roles** | [**List[GetClassicCompanyProfile200ResponseViewerRolesInner]**](GetClassicCompanyProfile200ResponseViewerRolesInner.md) | The list of roles the current user may have in the Company. | 
**locations** | [**List[GetClassicCompanyProfile200ResponseLocationsInner]**](GetClassicCompanyProfile200ResponseLocationsInner.md) | The list of locations related to the Company. | 
**industry** | **List[Optional[str]]** | A list of industries associated with the the Company. | 
**activities** | **List[Optional[str]]** | The list of activities of the Company. | [optional] 
**website** | **str** | The website URL of the Company. | [optional] 
**establishment_year** | **float** | The year the Company was established. | [optional] 
**phone** | **str** | The phone number of the Company. | [optional] 
**fields_of_expertise** | **List[Optional[str]]** | The list of fields of expertise of the Company. | [optional] 
**acquired_by** | [**GetClassicCompanyProfile200ResponseAcquiredBy**](GetClassicCompanyProfile200ResponseAcquiredBy.md) |  | [optional] 
**insights** | [**GetClassicCompanyProfile200ResponseInsights**](GetClassicCompanyProfile200ResponseInsights.md) |  | 
**funding** | [**GetClassicCompanyProfile200ResponseFunding**](GetClassicCompanyProfile200ResponseFunding.md) |  | [optional] 
**hashtags** | **List[Optional[str]]** | The list of hashtags related to the Company. | 

## Example

```python
from unipile.models.get_classic_company_profile200_response import GetClassicCompanyProfile200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicCompanyProfile200Response from a JSON string
get_classic_company_profile200_response_instance = GetClassicCompanyProfile200Response.from_json(json)
# print the JSON string representation of the object
print(GetClassicCompanyProfile200Response.to_json())

# convert the object into a dict
get_classic_company_profile200_response_dict = get_classic_company_profile200_response_instance.to_dict()
# create an instance of GetClassicCompanyProfile200Response from a dict
get_classic_company_profile200_response_from_dict = GetClassicCompanyProfile200Response.from_dict(get_classic_company_profile200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


