# GetEmailCategories200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | Object type identifier, always \&quot;EmailCategory\&quot;. | 
**id** | **str** | The ID of the category for the provider. | 
**name** | **str** | The name of the category. This is the value carried by the &#x60;categories&#x60; field of an email, and the value to pass when assigning categories to an email. | 
**color** | **str** | The color identifier the provider assigns to the category, when one is set. | [optional] 

## Example

```python
from unipile.models.get_email_categories200_response_data_inner import GetEmailCategories200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetEmailCategories200ResponseDataInner from a JSON string
get_email_categories200_response_data_inner_instance = GetEmailCategories200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetEmailCategories200ResponseDataInner.to_json())

# convert the object into a dict
get_email_categories200_response_data_inner_dict = get_email_categories200_response_data_inner_instance.to_dict()
# create an instance of GetEmailCategories200ResponseDataInner from a dict
get_email_categories200_response_data_inner_from_dict = GetEmailCategories200ResponseDataInner.from_dict(get_email_categories200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


