# ContentRelation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | How this message relates to a piece of shared content: a normal reply to it, or a provider-generated notice that the current user was mentioned in it. | 
**attachment_id** | **str** | The id of this message&#39;s shared-content attachment describing the related content, when the provider still makes it available. Absent once the content is no longer retrievable (e.g. an expired story) but the relation is still known. | [optional] 

## Example

```python
from unipile.models.content_relation import ContentRelation

# TODO update the JSON string below
json = "{}"
# create an instance of ContentRelation from a JSON string
content_relation_instance = ContentRelation.from_json(json)
# print the JSON string representation of the object
print(ContentRelation.to_json())

# convert the object into a dict
content_relation_dict = content_relation_instance.to_dict()
# create an instance of ContentRelation from a dict
content_relation_from_dict = ContentRelation.from_dict(content_relation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


