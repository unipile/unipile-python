# ConsentScreenProductsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the product. | 
**display_name** | **str** | The display name of the product. | 

## Example

```python
from unipile.models.consent_screen_products_inner import ConsentScreenProductsInner

# TODO update the JSON string below
json = "{}"
# create an instance of ConsentScreenProductsInner from a JSON string
consent_screen_products_inner_instance = ConsentScreenProductsInner.from_json(json)
# print the JSON string representation of the object
print(ConsentScreenProductsInner.to_json())

# convert the object into a dict
consent_screen_products_inner_dict = consent_screen_products_inner_instance.to_dict()
# create an instance of ConsentScreenProductsInner from a dict
consent_screen_products_inner_from_dict = ConsentScreenProductsInner.from_dict(consent_screen_products_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


