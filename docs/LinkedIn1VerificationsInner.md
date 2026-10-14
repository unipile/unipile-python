# LinkedIn1VerificationsInner

A verification associated with a LinkedIn user profile.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The verification category displayed by LinkedIn, such as Identity or Workplace, in the account locale. | 
**description** | **str** | The verification details displayed by LinkedIn, including the verification method if available. | [optional] 
**verified_since** | **str** | The relative time since verification displayed by LinkedIn, such as \&quot;Over 1 year ago\&quot;, in the account locale. | [optional] 

## Example

```python
from unipile.models.linked_in1_verifications_inner import LinkedIn1VerificationsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1VerificationsInner from a JSON string
linked_in1_verifications_inner_instance = LinkedIn1VerificationsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1VerificationsInner.to_json())

# convert the object into a dict
linked_in1_verifications_inner_dict = linked_in1_verifications_inner_instance.to_dict()
# create an instance of LinkedIn1VerificationsInner from a dict
linked_in1_verifications_inner_from_dict = LinkedIn1VerificationsInner.from_dict(linked_in1_verifications_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


