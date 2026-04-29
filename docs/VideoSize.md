# VideoSize

The size of the video in pixels.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**height** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**width** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 

## Example

```python
from unipile.models.video_size import VideoSize

# TODO update the JSON string below
json = "{}"
# create an instance of VideoSize from a JSON string
video_size_instance = VideoSize.from_json(json)
# print the JSON string representation of the object
print(VideoSize.to_json())

# convert the object into a dict
video_size_dict = video_size_instance.to_dict()
# create an instance of VideoSize from a dict
video_size_from_dict = VideoSize.from_dict(video_size_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


