# UnblockUserRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**specifics** | [**UnblockUserRequestSpecifics**](UnblockUserRequestSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.unblock_user_request import UnblockUserRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UnblockUserRequest from a JSON string
unblock_user_request_instance = UnblockUserRequest.from_json(json)
# print the JSON string representation of the object
print(UnblockUserRequest.to_json())

# convert the object into a dict
unblock_user_request_dict = unblock_user_request_instance.to_dict()
# create an instance of UnblockUserRequest from a dict
unblock_user_request_from_dict = UnblockUserRequest.from_dict(unblock_user_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


