# FullProfileCertificationsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | Name of the certification. | 
**organization** | [**GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization**](GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization.md) |  | 
**issued_on** | **str** | Date the certification was issued in MM/DD/YYYY format. | [optional] 
**expires_on** | **str** | Expiration date of the certification in MM/DD/YYYY format. | [optional] 
**license** | **str** | License identifier. | [optional] 
**skills** | **List[str]** | Skills acquired through certification. | [optional] 
**skills_preview** | **str** | Insight of the skills acquired through certification. | [optional] 
**url** | **str** | Public URL to the certification. | [optional] 

## Example

```python
from unipile.models.full_profile_certifications_inner import FullProfileCertificationsInner

# TODO update the JSON string below
json = "{}"
# create an instance of FullProfileCertificationsInner from a JSON string
full_profile_certifications_inner_instance = FullProfileCertificationsInner.from_json(json)
# print the JSON string representation of the object
print(FullProfileCertificationsInner.to_json())

# convert the object into a dict
full_profile_certifications_inner_dict = full_profile_certifications_inner_instance.to_dict()
# create an instance of FullProfileCertificationsInner from a dict
full_profile_certifications_inner_from_dict = FullProfileCertificationsInner.from_dict(full_profile_certifications_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


