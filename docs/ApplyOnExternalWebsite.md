# ApplyOnExternalWebsite


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**method** | **str** |  | 
**website_url** | **str** | The website on which applications should be made. | 

## Example

```python
from unipile.models.apply_on_external_website import ApplyOnExternalWebsite

# TODO update the JSON string below
json = "{}"
# create an instance of ApplyOnExternalWebsite from a JSON string
apply_on_external_website_instance = ApplyOnExternalWebsite.from_json(json)
# print the JSON string representation of the object
print(ApplyOnExternalWebsite.to_json())

# convert the object into a dict
apply_on_external_website_dict = apply_on_external_website_instance.to_dict()
# create an instance of ApplyOnExternalWebsite from a dict
apply_on_external_website_from_dict = ApplyOnExternalWebsite.from_dict(apply_on_external_website_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


