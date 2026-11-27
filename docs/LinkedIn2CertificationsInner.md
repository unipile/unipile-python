# LinkedIn2CertificationsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | Name of the certification. | 
**organization** | [**LinkedIn2CertificationsInnerOrganization**](LinkedIn2CertificationsInnerOrganization.md) |  | 
**issued_on** | **str** | Date the certification was issued in MM/DD/YYYY format. | [optional] 
**expires_on** | **str** | Expiration date of the certification in MM/DD/YYYY format. | [optional] 
**license** | **str** | License identifier. | [optional] 
**skills** | **List[Optional[str]]** | Skills acquired through certification. | [optional] 
**skills_preview** | **str** | Insight of the skills acquired through certification. | [optional] 
**url** | **str** | Public URL to the certification. | [optional] 

## Example

```python
from unipile.models.linked_in2_certifications_inner import LinkedIn2CertificationsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2CertificationsInner from a JSON string
linked_in2_certifications_inner_instance = LinkedIn2CertificationsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2CertificationsInner.to_json())

# convert the object into a dict
linked_in2_certifications_inner_dict = linked_in2_certifications_inner_instance.to_dict()
# create an instance of LinkedIn2CertificationsInner from a dict
linked_in2_certifications_inner_from_dict = LinkedIn2CertificationsInner.from_dict(linked_in2_certifications_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


