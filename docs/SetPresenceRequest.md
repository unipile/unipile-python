# SetPresenceRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**presence** | **str** | The presence of the user.     - &#x60;online&#x60; if the user is online / available.     _ &#x60;restricted_online&#x60; if the user is online to a restricted set of contacts.     - &#x60;offline&#x60; if the user is offline / unavailable.     - &#x60;away&#x60; if the user is away / busy. | 

## Example

```python
from unipile.models.set_presence_request import SetPresenceRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SetPresenceRequest from a JSON string
set_presence_request_instance = SetPresenceRequest.from_json(json)
# print the JSON string representation of the object
print(SetPresenceRequest.to_json())

# convert the object into a dict
set_presence_request_dict = set_presence_request_instance.to_dict()
# create an instance of SetPresenceRequest from a dict
set_presence_request_from_dict = SetPresenceRequest.from_dict(set_presence_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


