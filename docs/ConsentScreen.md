# ConsentScreen

The user must select the products that will be activated on the account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**products** | [**List[ConsentScreenProductsInner]**](ConsentScreenProductsInner.md) | A list of products to choose from. | 

## Example

```python
from unipile.models.consent_screen import ConsentScreen

# TODO update the JSON string below
json = "{}"
# create an instance of ConsentScreen from a JSON string
consent_screen_instance = ConsentScreen.from_json(json)
# print the JSON string representation of the object
print(ConsentScreen.to_json())

# convert the object into a dict
consent_screen_dict = consent_screen_instance.to_dict()
# create an instance of ConsentScreen from a dict
consent_screen_from_dict = ConsentScreen.from_dict(consent_screen_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


