# PublishInPromotedMode

Promoted Plus enables AI powered applicants filtering.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**set_hiring_frame** | **bool** | Whether to add the hiring frame to you public profile picture. | [optional] [default to True]
**bypass_email_verification** | **bool** | Whether not to verify if you&#39;re allowed to post a job on behalf on the current company. | [optional] [default to False]
**mode** | **str** | The publishing mode of the job posting. | 
**budget** | [**PublishInPromotedModeBudget**](PublishInPromotedModeBudget.md) |  | 

## Example

```python
from unipile.models.publish_in_promoted_mode import PublishInPromotedMode

# TODO update the JSON string below
json = "{}"
# create an instance of PublishInPromotedMode from a JSON string
publish_in_promoted_mode_instance = PublishInPromotedMode.from_json(json)
# print the JSON string representation of the object
print(PublishInPromotedMode.to_json())

# convert the object into a dict
publish_in_promoted_mode_dict = publish_in_promoted_mode_instance.to_dict()
# create an instance of PublishInPromotedMode from a dict
publish_in_promoted_mode_from_dict = PublishInPromotedMode.from_dict(publish_in_promoted_mode_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


