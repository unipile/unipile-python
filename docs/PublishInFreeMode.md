# PublishInFreeMode

⚠️ Requires eligibility

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**set_hiring_frame** | **bool** | Whether to add the hiring frame to you public profile picture. | [optional] [default to True]
**bypass_email_verification** | **bool** | Whether not to verify if you&#39;re allowed to post a job on behalf on the current company. | [optional] [default to False]
**mode** | **str** |  | 

## Example

```python
from unipile.models.publish_in_free_mode import PublishInFreeMode

# TODO update the JSON string below
json = "{}"
# create an instance of PublishInFreeMode from a JSON string
publish_in_free_mode_instance = PublishInFreeMode.from_json(json)
# print the JSON string representation of the object
print(PublishInFreeMode.to_json())

# convert the object into a dict
publish_in_free_mode_dict = publish_in_free_mode_instance.to_dict()
# create an instance of PublishInFreeMode from a dict
publish_in_free_mode_from_dict = PublishInFreeMode.from_dict(publish_in_free_mode_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


