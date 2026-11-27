# PinPostComment200Response

Result of pinning a comment on a post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | Confirms that the comment is now pinned on the post. | 

## Example

```python
from unipile.models.pin_post_comment200_response import PinPostComment200Response

# TODO update the JSON string below
json = "{}"
# create an instance of PinPostComment200Response from a JSON string
pin_post_comment200_response_instance = PinPostComment200Response.from_json(json)
# print the JSON string representation of the object
print(PinPostComment200Response.to_json())

# convert the object into a dict
pin_post_comment200_response_dict = pin_post_comment200_response_instance.to_dict()
# create an instance of PinPostComment200Response from a dict
pin_post_comment200_response_from_dict = PinPostComment200Response.from_dict(pin_post_comment200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


