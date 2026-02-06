# PublishInPromotedMode1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bypass_email_verification** | **bool** | Whether not to verify if you&#39;re allowed to post a job on behalf on the current company. | [optional] [default to False]
**mode** | **str** |  | 
**budget** | [**PublishInPromotedMode1Budget**](PublishInPromotedMode1Budget.md) |  | [optional] 

## Example

```python
from unipile.models.publish_in_promoted_mode1 import PublishInPromotedMode1

# TODO update the JSON string below
json = "{}"
# create an instance of PublishInPromotedMode1 from a JSON string
publish_in_promoted_mode1_instance = PublishInPromotedMode1.from_json(json)
# print the JSON string representation of the object
print(PublishInPromotedMode1.to_json())

# convert the object into a dict
publish_in_promoted_mode1_dict = publish_in_promoted_mode1_instance.to_dict()
# create an instance of PublishInPromotedMode1 from a dict
publish_in_promoted_mode1_from_dict = PublishInPromotedMode1.from_dict(publish_in_promoted_mode1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


