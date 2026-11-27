# Instagram1

Instagram specific dataset for user profiles.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**messaging_identifier** | **str** | The text content of the message, when available. | 
**account_type** | **str** | Type of the account.       - &#x60;personal&#x60; is a regular personal account.       - &#x60;business&#x60; is a professional account for a business or brand.       - &#x60;creator&#x60; is a professional account for a creator or public figure. | [optional] 
**category** | **str** | Category displayed on the profile of a professional account. Absent when the profile has none. | [optional] 

## Example

```python
from unipile.models.instagram1 import Instagram1

# TODO update the JSON string below
json = "{}"
# create an instance of Instagram1 from a JSON string
instagram1_instance = Instagram1.from_json(json)
# print the JSON string representation of the object
print(Instagram1.to_json())

# convert the object into a dict
instagram1_dict = instagram1_instance.to_dict()
# create an instance of Instagram1 from a dict
instagram1_from_dict = Instagram1.from_dict(instagram1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


