# ApplyOnLinkedin


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**method** | **str** |  | 
**notification_email** | **str** | An email address to get updates about applicants. | 

## Example

```python
from unipile.models.apply_on_linkedin import ApplyOnLinkedin

# TODO update the JSON string below
json = "{}"
# create an instance of ApplyOnLinkedin from a JSON string
apply_on_linkedin_instance = ApplyOnLinkedin.from_json(json)
# print the JSON string representation of the object
print(ApplyOnLinkedin.to_json())

# convert the object into a dict
apply_on_linkedin_dict = apply_on_linkedin_instance.to_dict()
# create an instance of ApplyOnLinkedin from a dict
apply_on_linkedin_from_dict = ApplyOnLinkedin.from_dict(apply_on_linkedin_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


