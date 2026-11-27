# unipile.SocialEventsApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_event_attendee**](SocialEventsApi.md#add_event_attendee) | **POST** /v2/{account_id}/events/{event_id}/attendees | Invite a User to an Event
[**create_event**](SocialEventsApi.md#create_event) | **POST** /v2/{account_id}/events | Create an Event
[**delete_event**](SocialEventsApi.md#delete_event) | **DELETE** /v2/{account_id}/events/{event_id} | Delete an Event
[**get_event**](SocialEventsApi.md#get_event) | **GET** /v2/{account_id}/events/{event_id} | Get an Event
[**get_event_attendees_list**](SocialEventsApi.md#get_event_attendees_list) | **GET** /v2/{account_id}/events/{event_id}/attendees | List all Event&#39;s Attendees
[**get_group_events_list**](SocialEventsApi.md#get_group_events_list) | **GET** /v2/{account_id}/groups/{group_id}/events | List all Group&#39;s Events
[**perform_events_search**](SocialEventsApi.md#perform_events_search) | **POST** /v2/{account_id}/search/events | Perform Events Search
[**set_event_rsvp**](SocialEventsApi.md#set_event_rsvp) | **POST** /v2/{account_id}/events/{event_id}/rsvp | Respond to an Event


# **add_event_attendee**
> AddEventAttendee200Response add_event_attendee(event_id, account_id, add_event_attendee_request)

Invite a User to an Event

Sends a user an invitation to a social event that they can accept or ignore. Inviting someone already invited succeeds without sending a new invitation.
      LIMITATIONS: The user must be a relation of the account owner (a friend on Facebook). On LinkedIn, only the organizers can invite, within a limit LinkedIn sets; a refused invitation gets a 403 when the account cannot invite to the event, a 400 otherwise. An unknown event gets a 404.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_event_attendee200_response import AddEventAttendee200Response
from unipile.models.add_event_attendee_request import AddEventAttendeeRequest
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
    api_instance = unipile.SocialEventsApi(api_client)
    event_id = 'event_id_example' # str | The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group's Events*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_event_attendee_request = unipile.AddEventAttendeeRequest() # AddEventAttendeeRequest | The user to invite.

    try:
        # Invite a User to an Event
        api_response = api_instance.add_event_attendee(event_id, account_id, add_event_attendee_request)
        print("The response of SocialEventsApi->add_event_attendee:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SocialEventsApi->add_event_attendee: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **event_id** | **str**| The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group&#39;s Events*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_event_attendee_request** | [**AddEventAttendeeRequest**](AddEventAttendeeRequest.md)| The user to invite. | 

### Return type

[**AddEventAttendee200Response**](AddEventAttendee200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The user was invited to the event. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_event**
> PerformEventsSearch200ResponseDataInner create_event(account_id, create_event_request)

Create an Event

Creates and returns an event on the account's social network with the account owner as organizer. If the full event is temporarily unavailable after creation, the response includes its ID, name and URL. An online event takes a link to join it (`online_url`). An in-person event takes a `location`. Set `start_at` in the future and `end_at` after it. The event is displayed in the specified IANA `timezone` (UTC by default).
      LIMITATIONS: On Facebook, an event is `private` by default; `group_id` creates it in a group (visibility `group`). `invite_group_members` without `group_id`, and `can_attendees_invite` for an event that is not `private`, get a 400. An `online_url` Facebook blocks is refused, and the event may still be created without it. On LinkedIn, events are public: an online event requires an http or https `online_url`, an in-person one a `location`; without `end_at`, the event lasts one hour; details LinkedIn refuses get a 400 with its reason. LinkedIn removes events that no post announces, so a post announcing the event is also published on the account's feed. `group_id`, `invite_group_members`, `co_host_ids`, `can_attendees_invite`, `is_attendees_list_hidden` and a visibility other than `public` get a 400 on LinkedIn.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_event_request import CreateEventRequest
from unipile.models.perform_events_search200_response_data_inner import PerformEventsSearch200ResponseDataInner
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
    api_instance = unipile.SocialEventsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_event_request = unipile.CreateEventRequest() # CreateEventRequest | The event to create.

    try:
        # Create an Event
        api_response = api_instance.create_event(account_id, create_event_request)
        print("The response of SocialEventsApi->create_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SocialEventsApi->create_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_event_request** | [**CreateEventRequest**](CreateEventRequest.md)| The event to create. | 

### Return type

[**PerformEventsSearch200ResponseDataInner**](PerformEventsSearch200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | An event of a social network. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_event**
> delete_event(event_id, account_id)

Delete an Event

Deletes a social event organized by the account owner. An event the account does not organize gets a 403.
      LIMITATIONS: On LinkedIn, the post announcing the event is deleted with it (an event without one gets a 422), and *Get an Event* may still return the event for a few seconds.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
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
    api_instance = unipile.SocialEventsApi(api_client)
    event_id = 'event_id_example' # str | The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group's Events*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete an Event
        api_instance.delete_event(event_id, account_id)
    except Exception as e:
        print("Exception when calling SocialEventsApi->delete_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **event_id** | **str**| The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group&#39;s Events*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | No content: the event was deleted. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_event**
> PerformEventsSearch200ResponseDataInner get_event(event_id, account_id)

Get an Event

Returns the details of a social event and the account owner's response to it.
      LIMITATIONS: LinkedIn may omit `timezone`. It returns the exact timestamps in `start.date_time` and `end.date_time` when available.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_events_search200_response_data_inner import PerformEventsSearch200ResponseDataInner
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
    api_instance = unipile.SocialEventsApi(api_client)
    event_id = 'event_id_example' # str | The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group's Events*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get an Event
        api_response = api_instance.get_event(event_id, account_id)
        print("The response of SocialEventsApi->get_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SocialEventsApi->get_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **event_id** | **str**| The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group&#39;s Events*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**PerformEventsSearch200ResponseDataInner**](PerformEventsSearch200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | An event of a social network. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_event_attendees_list**
> GetEventAttendeesList200Response get_event_attendees_list(event_id, account_id, cursor=cursor, limit=limit, status=status)

List all Event's Attendees

Lists guests of a social event by response. Use `yes` for going (the default), `maybe` for interested, `noreply` for invited, or `no` for declined.
      LIMITATIONS: On Facebook, only the first page is returned, up to `limit` (a `cursor` gets a 400). On LinkedIn, only the people attending are listed (a `status` other than `yes` gets a 400), LinkedIn sets the page size (follow `next_cursor`), and an unknown event gets a 404.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_event_attendees_list200_response import GetEventAttendeesList200Response
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
    api_instance = unipile.SocialEventsApi(api_client)
    event_id = 'event_id_example' # str | The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group's Events*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)
    status = 'status_example' # str | The response to the event.   - `yes` going.   - `maybe` interested.   - `no` not going.   - `noreply` invited, without a response yet. (optional)

    try:
        # List all Event's Attendees
        api_response = api_instance.get_event_attendees_list(event_id, account_id, cursor=cursor, limit=limit, status=status)
        print("The response of SocialEventsApi->get_event_attendees_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SocialEventsApi->get_event_attendees_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **event_id** | **str**| The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group&#39;s Events*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]
 **status** | **str**| The response to the event.   - &#x60;yes&#x60; going.   - &#x60;maybe&#x60; interested.   - &#x60;no&#x60; not going.   - &#x60;noreply&#x60; invited, without a response yet. | [optional] 

### Return type

[**GetEventAttendeesList200Response**](GetEventAttendeesList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_group_events_list**
> PerformEventsSearch200Response get_group_events_list(group_id, account_id, cursor=cursor, limit=limit, period=period)

List all Group's Events

Returns the upcoming social events of a group. Use `period` to list past events. Set `period` on the first request only. For later pages, pass `next_cursor` as `cursor`. The cursor carries the selected period.
      LIMITATIONS: On Facebook, the list has no dates and places (use *Get an Event*). Not supported on LinkedIn, whose groups have no events.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_events_search200_response import PerformEventsSearch200Response
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
    api_instance = unipile.SocialEventsApi(api_client)
    group_id = 'group_id_example' # str | The ID of the social group. Use an ID returned by *Perform Groups Search*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)
    period = 'period_example' # str | Whether to list upcoming events (the default) or past events. Omit this field when sending a cursor. (optional)

    try:
        # List all Group's Events
        api_response = api_instance.get_group_events_list(group_id, account_id, cursor=cursor, limit=limit, period=period)
        print("The response of SocialEventsApi->get_group_events_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SocialEventsApi->get_group_events_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **str**| The ID of the social group. Use an ID returned by *Perform Groups Search*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]
 **period** | **str**| Whether to list upcoming events (the default) or past events. Omit this field when sending a cursor. | [optional] 

### Return type

[**PerformEventsSearch200Response**](PerformEventsSearch200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_events_search**
> PerformEventsSearch200Response perform_events_search(account_id, perform_events_search_request, cursor=cursor, limit=limit)

Perform Events Search

Searches for social events that the account owner can see and that match the given keywords. When the provider supports date filters, `start_date` and `end_date` limit the search period (from today by default). Send the same body with `cursor` to get the next pages.
      LIMITATIONS: On Facebook, without dates the search covers the next 12 months, and with `end_date` alone it starts today (a past `end_date` gets a 400); the same day as `start_date` and `end_date` searches that day. `location` takes one city ID and `category` one or more category IDs; an ID Facebook does not know is ignored. Facebook sets the page size whatever the `limit`. On LinkedIn, events are searched by keywords only (the filters get a 400) and sorted by relevance, at most 10 per page (`limit` up to 10), up to 1000 results; a page may hold fewer events, or none: follow `next_cursor`. LinkedIn results have no dates: use *Get an Event*.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_events_search200_response import PerformEventsSearch200Response
from unipile.models.perform_events_search_request import PerformEventsSearchRequest
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
    api_instance = unipile.SocialEventsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_events_search_request = unipile.PerformEventsSearchRequest() # PerformEventsSearchRequest | The criteria of the search.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # Perform Events Search
        api_response = api_instance.perform_events_search(account_id, perform_events_search_request, cursor=cursor, limit=limit)
        print("The response of SocialEventsApi->perform_events_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SocialEventsApi->perform_events_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_events_search_request** | [**PerformEventsSearchRequest**](PerformEventsSearchRequest.md)| The criteria of the search. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**PerformEventsSearch200Response**](PerformEventsSearch200Response.md)

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

# **set_event_rsvp**
> set_event_rsvp(event_id, account_id, set_event_rsvp_request)

Respond to an Event

Sets the account owner's response to a social event. Use `yes` for going, `maybe` for interested, or `no` for not going.
      LIMITATIONS: On Facebook, a public event is followed: `maybe` marks it as interested and `no` stops following it. The organizer of an event always attends it: its response gets a 400. Not supported on LinkedIn.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.set_event_rsvp_request import SetEventRsvpRequest
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
    api_instance = unipile.SocialEventsApi(api_client)
    event_id = 'event_id_example' # str | The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group's Events*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    set_event_rsvp_request = unipile.SetEventRsvpRequest() # SetEventRsvpRequest | The response of the account owner to the event.

    try:
        # Respond to an Event
        api_instance.set_event_rsvp(event_id, account_id, set_event_rsvp_request)
    except Exception as e:
        print("Exception when calling SocialEventsApi->set_event_rsvp: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **event_id** | **str**| The ID of the event. Use an ID returned by *Perform Events Search*, *Create an Event* or *List all Group&#39;s Events*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **set_event_rsvp_request** | [**SetEventRsvpRequest**](SetEventRsvpRequest.md)| The response of the account owner to the event. | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | No content: the response was recorded. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

