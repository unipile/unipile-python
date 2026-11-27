# AcceptCommunityJoinRequest200Response

The request was accepted: the user is a member.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;CommunityJoinRequestAccepted&#x60;. | 

## Example

```python
from unipile.models.accept_community_join_request200_response import AcceptCommunityJoinRequest200Response

# TODO update the JSON string below
json = "{}"
# create an instance of AcceptCommunityJoinRequest200Response from a JSON string
accept_community_join_request200_response_instance = AcceptCommunityJoinRequest200Response.from_json(json)
# print the JSON string representation of the object
print(AcceptCommunityJoinRequest200Response.to_json())

# convert the object into a dict
accept_community_join_request200_response_dict = accept_community_join_request200_response_instance.to_dict()
# create an instance of AcceptCommunityJoinRequest200Response from a dict
accept_community_join_request200_response_from_dict = AcceptCommunityJoinRequest200Response.from_dict(accept_community_join_request200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


