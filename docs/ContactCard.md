# ContactCard


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the attachment for the provider. | 
**file_size** | **float** | The size of the attachment in bytes. | [optional] 
**is_inline** | **bool** | Is the attachment inline in the content. | 
**is_unavailable** | **bool** | The attachment is not available for download because it was removed from provider servers. | [optional] 
**mimetype** | **str** | The MIME type of the attachment. | 
**url** | **str** | The URL to download the attachment. | 
**url_expires_at** | **str** | The URL expiration timestamp. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**content** | **str** | Content of the attachement | [optional] 
**type** | **str** |  | 
**display_name** | **str** | The name of the shared contact. | [optional] 
**organization** | **str** | The organization of the shared contact. | [optional] 
**phones** | [**List[ContactCardPhonesInner]**](ContactCardPhonesInner.md) | The phone numbers of the shared contact. | 
**emails** | [**List[ContactCardEmailsInner]**](ContactCardEmailsInner.md) | The email addresses of the shared contact. | 

## Example

```python
from unipile.models.contact_card import ContactCard

# TODO update the JSON string below
json = "{}"
# create an instance of ContactCard from a JSON string
contact_card_instance = ContactCard.from_json(json)
# print the JSON string representation of the object
print(ContactCard.to_json())

# convert the object into a dict
contact_card_dict = contact_card_instance.to_dict()
# create an instance of ContactCard from a dict
contact_card_from_dict = ContactCard.from_dict(contact_card_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


