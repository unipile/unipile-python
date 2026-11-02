# CreateEmailCategoryRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the category. A category name is unique within a mailbox, so it must not already be used by another category. | 
**color** | **str** | Color identifier to assign to the category. Outlook accepts &#x60;none&#x60; and &#x60;preset0&#x60; to &#x60;preset24&#x60;; any other value is rejected with an error listing the accepted values. Defaults to no color. See the &lt;a href&#x3D;\&quot;https://learn.microsoft.com/en-us/graph/api/resources/outlookcategory#properties\&quot;&gt;color mapped to each preset&lt;/a&gt;. | [optional] 

## Example

```python
from unipile.models.create_email_category_request import CreateEmailCategoryRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateEmailCategoryRequest from a JSON string
create_email_category_request_instance = CreateEmailCategoryRequest.from_json(json)
# print the JSON string representation of the object
print(CreateEmailCategoryRequest.to_json())

# convert the object into a dict
create_email_category_request_dict = create_email_category_request_instance.to_dict()
# create an instance of CreateEmailCategoryRequest from a dict
create_email_category_request_from_dict = CreateEmailCategoryRequest.from_dict(create_email_category_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


