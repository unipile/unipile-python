# MessageLastUpdatedBy


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
**specifics** | [**MessageLastUpdatedBySpecifics**](MessageLastUpdatedBySpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.message_last_updated_by import MessageLastUpdatedBy

# TODO update the JSON string below
json = "{}"
# create an instance of MessageLastUpdatedBy from a JSON string
message_last_updated_by_instance = MessageLastUpdatedBy.from_json(json)
# print the JSON string representation of the object
print(MessageLastUpdatedBy.to_json())

# convert the object into a dict
message_last_updated_by_dict = message_last_updated_by_instance.to_dict()
# create an instance of MessageLastUpdatedBy from a dict
message_last_updated_by_from_dict = MessageLastUpdatedBy.from_dict(message_last_updated_by_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


