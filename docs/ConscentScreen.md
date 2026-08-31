# ConscentScreen

The user must select the products that will be activated on the account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**products** | [**List[ConscentScreenProductsInner]**](ConscentScreenProductsInner.md) | A list of products to choose from. | 

## Example

```python
from unipile.models.conscent_screen import ConscentScreen

# TODO update the JSON string below
json = "{}"
# create an instance of ConscentScreen from a JSON string
conscent_screen_instance = ConscentScreen.from_json(json)
# print the JSON string representation of the object
print(ConscentScreen.to_json())

# convert the object into a dict
conscent_screen_dict = conscent_screen_instance.to_dict()
# create an instance of ConscentScreen from a dict
conscent_screen_from_dict = ConscentScreen.from_dict(conscent_screen_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


