# GetCompanyFollowInvitationCredits200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**remaining_credit** | **float** | The remaining credit for inviting members to follow the company page. | 
**credit_grant** | **float** | The credit that is granted to you on each reset. | 
**resets_on** | **str** | The next reset date of the credits. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 

## Example

```python
from unipile.models.get_company_follow_invitation_credits200_response import GetCompanyFollowInvitationCredits200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetCompanyFollowInvitationCredits200Response from a JSON string
get_company_follow_invitation_credits200_response_instance = GetCompanyFollowInvitationCredits200Response.from_json(json)
# print the JSON string representation of the object
print(GetCompanyFollowInvitationCredits200Response.to_json())

# convert the object into a dict
get_company_follow_invitation_credits200_response_dict = get_company_follow_invitation_credits200_response_instance.to_dict()
# create an instance of GetCompanyFollowInvitationCredits200Response from a dict
get_company_follow_invitation_credits200_response_from_dict = GetCompanyFollowInvitationCredits200Response.from_dict(get_company_follow_invitation_credits200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


