# LinkedIn3

LinkedIn-specific options for sending a relation request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_email** | **str** | The recipient&#39;s email address, required when LinkedIn requests it for a Sales Navigator invitation. Only supported for Sales Navigator user IDs (ACw...). | [optional] 

## Example

```python
from unipile.models.linked_in3 import LinkedIn3

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn3 from a JSON string
linked_in3_instance = LinkedIn3.from_json(json)
# print the JSON string representation of the object
print(LinkedIn3.to_json())

# convert the object into a dict
linked_in3_dict = linked_in3_instance.to_dict()
# create an instance of LinkedIn3 from a dict
linked_in3_from_dict = LinkedIn3.from_dict(linked_in3_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


