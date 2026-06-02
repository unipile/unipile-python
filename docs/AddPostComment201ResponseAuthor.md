# AddPostComment201ResponseAuthor

The author of the comment.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the user for the provider. Usually an internal identifier used by the API only. | 
**object** | **str** |  | 
**type** | **str** | Type of the user       - &#x60;individual&#x60; is an individual user.       - &#x60;organization&#x60; is an organization / business entity.       - &#x60;other&#x60; is an other type of entity. | 
**public_identifier** | **str** | Public identifier of the user for the provider. Usually a shareable tag visible in urls and profiles.  | [optional] 
**display_name** | **str** | Display name of the user. | 
**profile_url** | **str** | Public url to the profile of the user. | [optional] 
**public_picture_url** | **str** | Public url to the profile picture of the user. | [optional] 
**private_picture_download_url** | **str** | Private url to download the profile picture of the user. This url require authentication. | [optional] 
**description** | **str** | Description of the user. | [optional] 
**specifics** | **object** |  | [optional] 

## Example

```python
from unipile.models.add_post_comment201_response_author import AddPostComment201ResponseAuthor

# TODO update the JSON string below
json = "{}"
# create an instance of AddPostComment201ResponseAuthor from a JSON string
add_post_comment201_response_author_instance = AddPostComment201ResponseAuthor.from_json(json)
# print the JSON string representation of the object
print(AddPostComment201ResponseAuthor.to_json())

# convert the object into a dict
add_post_comment201_response_author_dict = add_post_comment201_response_author_instance.to_dict()
# create an instance of AddPostComment201ResponseAuthor from a dict
add_post_comment201_response_author_from_dict = AddPostComment201ResponseAuthor.from_dict(add_post_comment201_response_author_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


