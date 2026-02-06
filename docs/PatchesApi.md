# unipile.PatchesApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**update_post**](PatchesApi.md#update_post) | **PATCH** /v2/{account_id}/posts/{post_id} | Update a Post
[**update_post_comment**](PatchesApi.md#update_post_comment) | **PATCH** /v2/{account_id}/posts/{post_id}/comments/{comment_id} | Update a Comment


# **update_post**
> GetPost200Response update_post(post_id, account_id, update_post_request=update_post_request)

Update a Post

Updates an existing post.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_post200_response import GetPost200Response
from unipile.models.update_post_request import UpdatePostRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.PatchesApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to update.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_post_request = unipile.UpdatePostRequest() # UpdatePostRequest |  (optional)

    try:
        # Update a Post
        api_response = api_instance.update_post(post_id, account_id, update_post_request=update_post_request)
        print("The response of PatchesApi->update_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PatchesApi->update_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to update. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_post_request** | [**UpdatePostRequest**](UpdatePostRequest.md)|  | [optional] 

### Return type

[**GetPost200Response**](GetPost200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_post_comment**
> GetPostCommentsList200ResponseDataInner update_post_comment(post_id, comment_id, account_id, update_post_comment_request)

Update a Comment

Updates an existing comment.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_post_comments_list200_response_data_inner import GetPostCommentsList200ResponseDataInner
from unipile.models.update_post_comment_request import UpdatePostCommentRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.PatchesApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post where the comment is.
    comment_id = 'comment_id_example' # str | The ID of the Comment to update.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_post_comment_request = unipile.UpdatePostCommentRequest() # UpdatePostCommentRequest | 

    try:
        # Update a Comment
        api_response = api_instance.update_post_comment(post_id, comment_id, account_id, update_post_comment_request)
        print("The response of PatchesApi->update_post_comment:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PatchesApi->update_post_comment: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post where the comment is. | 
 **comment_id** | **str**| The ID of the Comment to update. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_post_comment_request** | [**UpdatePostCommentRequest**](UpdatePostCommentRequest.md)|  | 

### Return type

[**GetPostCommentsList200ResponseDataInner**](GetPostCommentsList200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

