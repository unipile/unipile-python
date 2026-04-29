# LinkedInLanguagesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**language** | **str** | Name of the language. | 
**proficiency** | **str** | Level of fluency in the language. | [optional] 

## Example

```python
from unipile.models.linked_in_languages_inner import LinkedInLanguagesInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInLanguagesInner from a JSON string
linked_in_languages_inner_instance = LinkedInLanguagesInner.from_json(json)
# print the JSON string representation of the object
print(LinkedInLanguagesInner.to_json())

# convert the object into a dict
linked_in_languages_inner_dict = linked_in_languages_inner_instance.to_dict()
# create an instance of LinkedInLanguagesInner from a dict
linked_in_languages_inner_from_dict = LinkedInLanguagesInner.from_dict(linked_in_languages_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


