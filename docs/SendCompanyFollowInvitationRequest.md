# SendCompanyFollowInvitationRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member_ids** | **List[Optional[str]]** | A list of member profile IDs (ACo...) identifying the members to invite to follow the company page. | 

## Example

```python
from unipile.models.send_company_follow_invitation_request import SendCompanyFollowInvitationRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SendCompanyFollowInvitationRequest from a JSON string
send_company_follow_invitation_request_instance = SendCompanyFollowInvitationRequest.from_json(json)
# print the JSON string representation of the object
print(SendCompanyFollowInvitationRequest.to_json())

# convert the object into a dict
send_company_follow_invitation_request_dict = send_company_follow_invitation_request_instance.to_dict()
# create an instance of SendCompanyFollowInvitationRequest from a dict
send_company_follow_invitation_request_from_dict = SendCompanyFollowInvitationRequest.from_dict(send_company_follow_invitation_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


