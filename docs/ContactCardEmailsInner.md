# ContactCardEmailsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | The email address of the shared contact. | 
**type** | **str** | The label of the email address, as set by the contact owner (HOME, WORK, ...). | [optional] 

## Example

```python
from unipile.models.contact_card_emails_inner import ContactCardEmailsInner

# TODO update the JSON string below
json = "{}"
# create an instance of ContactCardEmailsInner from a JSON string
contact_card_emails_inner_instance = ContactCardEmailsInner.from_json(json)
# print the JSON string representation of the object
print(ContactCardEmailsInner.to_json())

# convert the object into a dict
contact_card_emails_inner_dict = contact_card_emails_inner_instance.to_dict()
# create an instance of ContactCardEmailsInner from a dict
contact_card_emails_inner_from_dict = ContactCardEmailsInner.from_dict(contact_card_emails_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


