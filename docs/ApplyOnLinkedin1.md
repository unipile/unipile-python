# ApplyOnLinkedin1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**method** | **str** |  | 
**notification_email** | **str** | An email address to get updates about applicants. | 
**resume_required** | **bool** | Whether to require a resume from the applicants. | 

## Example

```python
from unipile.models.apply_on_linkedin1 import ApplyOnLinkedin1

# TODO update the JSON string below
json = "{}"
# create an instance of ApplyOnLinkedin1 from a JSON string
apply_on_linkedin1_instance = ApplyOnLinkedin1.from_json(json)
# print the JSON string representation of the object
print(ApplyOnLinkedin1.to_json())

# convert the object into a dict
apply_on_linkedin1_dict = apply_on_linkedin1_instance.to_dict()
# create an instance of ApplyOnLinkedin1 from a dict
apply_on_linkedin1_from_dict = ApplyOnLinkedin1.from_dict(apply_on_linkedin1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


