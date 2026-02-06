# InAppValidation

A notification was sent to the user's phone. The user needs to validate the notification by clicking on the link in the notification.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 

## Example

```python
from unipile.models.in_app_validation import InAppValidation

# TODO update the JSON string below
json = "{}"
# create an instance of InAppValidation from a JSON string
in_app_validation_instance = InAppValidation.from_json(json)
# print the JSON string representation of the object
print(InAppValidation.to_json())

# convert the object into a dict
in_app_validation_dict = in_app_validation_instance.to_dict()
# create an instance of InAppValidation from a dict
in_app_validation_from_dict = InAppValidation.from_dict(in_app_validation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


