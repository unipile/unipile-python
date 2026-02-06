# GetChat200ResponseMutedUntil

The date until the chat is muted. Use ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). Is `true` if muted indefinitely.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.get_chat200_response_muted_until import GetChat200ResponseMutedUntil

# TODO update the JSON string below
json = "{}"
# create an instance of GetChat200ResponseMutedUntil from a JSON string
get_chat200_response_muted_until_instance = GetChat200ResponseMutedUntil.from_json(json)
# print the JSON string representation of the object
print(GetChat200ResponseMutedUntil.to_json())

# convert the object into a dict
get_chat200_response_muted_until_dict = get_chat200_response_muted_until_instance.to_dict()
# create an instance of GetChat200ResponseMutedUntil from a dict
get_chat200_response_muted_until_from_dict = GetChat200ResponseMutedUntil.from_dict(get_chat200_response_muted_until_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


