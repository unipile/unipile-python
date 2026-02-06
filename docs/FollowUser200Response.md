# FollowUser200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**user** | [**GetRelationRequestsList200ResponseDataInnerUser**](GetRelationRequestsList200ResponseDataInnerUser.md) |  | [optional] 
**type** | **str** | Type of the relation / follow request.       - &#x60;sent&#x60; if the current user has asked another one to be in his relations.       - &#x60;received&#x60; if another user has asked the current one to be in his relations. | 
**id** | **str** | The unique identifier of the invitation for the provider. | 
**created_at** | **str** | Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**message** | **str** | Any message that comes with the invitation. | [optional] 

## Example

```python
from unipile.models.follow_user200_response import FollowUser200Response

# TODO update the JSON string below
json = "{}"
# create an instance of FollowUser200Response from a JSON string
follow_user200_response_instance = FollowUser200Response.from_json(json)
# print the JSON string representation of the object
print(FollowUser200Response.to_json())

# convert the object into a dict
follow_user200_response_dict = follow_user200_response_instance.to_dict()
# create an instance of FollowUser200Response from a dict
follow_user200_response_from_dict = FollowUser200Response.from_dict(follow_user200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


