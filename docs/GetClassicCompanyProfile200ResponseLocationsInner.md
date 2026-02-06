# GetClassicCompanyProfile200ResponseLocationsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_headquarter** | **bool** | Whether the location is the headquarters of the Company. | 
**country_code** | **str** | The country code of the location. | 
**city** | **str** | The city of the location. | 
**area** | **str** | The area of the location. | [optional] 
**postal_code** | **str** | The postal code of the location. | [optional] 
**street** | **str** | The street of the location. | [optional] 
**description** | **str** | The description of the location. | [optional] 

## Example

```python
from unipile.models.get_classic_company_profile200_response_locations_inner import GetClassicCompanyProfile200ResponseLocationsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicCompanyProfile200ResponseLocationsInner from a JSON string
get_classic_company_profile200_response_locations_inner_instance = GetClassicCompanyProfile200ResponseLocationsInner.from_json(json)
# print the JSON string representation of the object
print(GetClassicCompanyProfile200ResponseLocationsInner.to_json())

# convert the object into a dict
get_classic_company_profile200_response_locations_inner_dict = get_classic_company_profile200_response_locations_inner_instance.to_dict()
# create an instance of GetClassicCompanyProfile200ResponseLocationsInner from a dict
get_classic_company_profile200_response_locations_inner_from_dict = GetClassicCompanyProfile200ResponseLocationsInner.from_dict(get_classic_company_profile200_response_locations_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


