# ContactCardPhonesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**number** | **str** | The phone number of the shared contact. | 
**type** | **str** | The label of the phone number, as set by the contact owner (CELL, WORK, ...). | [optional] 

## Example

```python
from unipile.models.contact_card_phones_inner import ContactCardPhonesInner

# TODO update the JSON string below
json = "{}"
# create an instance of ContactCardPhonesInner from a JSON string
contact_card_phones_inner_instance = ContactCardPhonesInner.from_json(json)
# print the JSON string representation of the object
print(ContactCardPhonesInner.to_json())

# convert the object into a dict
contact_card_phones_inner_dict = contact_card_phones_inner_instance.to_dict()
# create an instance of ContactCardPhonesInner from a dict
contact_card_phones_inner_from_dict = ContactCardPhonesInner.from_dict(contact_card_phones_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


