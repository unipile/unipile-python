# PublishInFreeMode1

⚠️ Requires eligibility

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bypass_email_verification** | **bool** | Whether not to verify if you&#39;re allowed to post a job on behalf on the current company. | [optional] [default to False]
**mode** | **str** |  | 

## Example

```python
from unipile.models.publish_in_free_mode1 import PublishInFreeMode1

# TODO update the JSON string below
json = "{}"
# create an instance of PublishInFreeMode1 from a JSON string
publish_in_free_mode1_instance = PublishInFreeMode1.from_json(json)
# print the JSON string representation of the object
print(PublishInFreeMode1.to_json())

# convert the object into a dict
publish_in_free_mode1_dict = publish_in_free_mode1_instance.to_dict()
# create an instance of PublishInFreeMode1 from a dict
publish_in_free_mode1_from_dict = PublishInFreeMode1.from_dict(publish_in_free_mode1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


