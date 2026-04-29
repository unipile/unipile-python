# OTPOrInAppValidation

The user can either enter a one-time password sent to their phone/email or validate a notification sent to their phone.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 

## Example

```python
from unipile.models.otpor_in_app_validation import OTPOrInAppValidation

# TODO update the JSON string below
json = "{}"
# create an instance of OTPOrInAppValidation from a JSON string
otpor_in_app_validation_instance = OTPOrInAppValidation.from_json(json)
# print the JSON string representation of the object
print(OTPOrInAppValidation.to_json())

# convert the object into a dict
otpor_in_app_validation_dict = otpor_in_app_validation_instance.to_dict()
# create an instance of OTPOrInAppValidation from a dict
otpor_in_app_validation_from_dict = OTPOrInAppValidation.from_dict(otpor_in_app_validation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


