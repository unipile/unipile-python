# SendCompanyFollowInvitation200ResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitations_ids** | **List[Optional[str]]** | The IDs of the successfully sent invitations. | 
**invitations_count** | [**SendCompanyFollowInvitation200ResponseResultInvitationsCount**](SendCompanyFollowInvitation200ResponseResultInvitationsCount.md) |  | 

## Example

```python
from unipile.models.send_company_follow_invitation200_response_result import SendCompanyFollowInvitation200ResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendCompanyFollowInvitation200ResponseResult from a JSON string
send_company_follow_invitation200_response_result_instance = SendCompanyFollowInvitation200ResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendCompanyFollowInvitation200ResponseResult.to_json())

# convert the object into a dict
send_company_follow_invitation200_response_result_dict = send_company_follow_invitation200_response_result_instance.to_dict()
# create an instance of SendCompanyFollowInvitation200ResponseResult from a dict
send_company_follow_invitation200_response_result_from_dict = SendCompanyFollowInvitation200ResponseResult.from_dict(send_company_follow_invitation200_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


