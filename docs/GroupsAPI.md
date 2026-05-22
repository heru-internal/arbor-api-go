# \GroupsAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddFileToGroup**](GroupsAPI.md#AddFileToGroup) | **Post** /groups/{groupId}/files | 
[**AddReleaseChannelToGroup**](GroupsAPI.md#AddReleaseChannelToGroup) | **Post** /groups/{groupId}/release-channels | 
[**AddVideoToGroup**](GroupsAPI.md#AddVideoToGroup) | **Post** /groups/{groupId}/videos | 
[**AttachTagsToGroup**](GroupsAPI.md#AttachTagsToGroup) | **Patch** /groups/{groupId}/tags/attach | 
[**ConfigureGroup**](GroupsAPI.md#ConfigureGroup) | **Patch** /groups/{groupId}/configure | 
[**CreateGroup**](GroupsAPI.md#CreateGroup) | **Post** /groups | 
[**DeleteGroup**](GroupsAPI.md#DeleteGroup) | **Delete** /groups/{groupId} | 
[**DetachTagsFromGroup**](GroupsAPI.md#DetachTagsFromGroup) | **Patch** /groups/{groupId}/tags/detach | 
[**DuplicateGroup**](GroupsAPI.md#DuplicateGroup) | **Post** /groups/{groupId}/duplicate | 
[**GetGroup**](GroupsAPI.md#GetGroup) | **Get** /groups/{groupId} | 
[**GetGroupHierarchy**](GroupsAPI.md#GetGroupHierarchy) | **Get** /group-hierarchy | 
[**GetGroupReleaseChannels**](GroupsAPI.md#GetGroupReleaseChannels) | **Get** /groups/{groupId}/release-channels | 
[**GetGroups**](GroupsAPI.md#GetGroups) | **Get** /groups | 
[**RemoveFileFromGroup**](GroupsAPI.md#RemoveFileFromGroup) | **Delete** /groups/{groupId}/files/{fileId} | 
[**RemoveReleaseChannelFromGroup**](GroupsAPI.md#RemoveReleaseChannelFromGroup) | **Delete** /groups/{groupId}/release-channels/{releaseChannelId} | 
[**RemoveVideoFromGroup**](GroupsAPI.md#RemoveVideoFromGroup) | **Delete** /groups/{groupId}/videos/{videoId} | 
[**UpdateGroup**](GroupsAPI.md#UpdateGroup) | **Put** /groups/{groupId} | 



## AddFileToGroup

> AddFileToGroup(ctx, groupId).Accept(accept).AddFileToGroupRequest(addFileToGroupRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	addFileToGroupRequest := *openapiclient.NewAddFileToGroupRequest("123e4567-e89b-12d3-a456-426614174000") // AddFileToGroupRequest | The file to add to the group. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.AddFileToGroup(context.Background(), groupId).Accept(accept).AddFileToGroupRequest(addFileToGroupRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.AddFileToGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddFileToGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **addFileToGroupRequest** | [**AddFileToGroupRequest**](AddFileToGroupRequest.md) | The file to add to the group. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AddReleaseChannelToGroup

> AddReleaseChannelToGroup(ctx, groupId).Accept(accept).AddReleaseChannelToGroupRequest(addReleaseChannelToGroupRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	addReleaseChannelToGroupRequest := *openapiclient.NewAddReleaseChannelToGroupRequest("123e4567-e89b-12d3-a456-426614174000") // AddReleaseChannelToGroupRequest | The release channel to add to the group. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.AddReleaseChannelToGroup(context.Background(), groupId).Accept(accept).AddReleaseChannelToGroupRequest(addReleaseChannelToGroupRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.AddReleaseChannelToGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddReleaseChannelToGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **addReleaseChannelToGroupRequest** | [**AddReleaseChannelToGroupRequest**](AddReleaseChannelToGroupRequest.md) | The release channel to add to the group. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AddVideoToGroup

> AddVideoToGroup(ctx, groupId).Accept(accept).AddVideoToGroupRequest(addVideoToGroupRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	addVideoToGroupRequest := *openapiclient.NewAddVideoToGroupRequest("123e4567-e89b-12d3-a456-426614174000") // AddVideoToGroupRequest | The video to add to the group. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.AddVideoToGroup(context.Background(), groupId).Accept(accept).AddVideoToGroupRequest(addVideoToGroupRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.AddVideoToGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddVideoToGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **addVideoToGroupRequest** | [**AddVideoToGroupRequest**](AddVideoToGroupRequest.md) | The video to add to the group. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AttachTagsToGroup

> AttachTagsToGroup(ctx, groupId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	attachTagsToAppRequest := *openapiclient.NewAttachTagsToAppRequest([]string{"Tags_example"}) // AttachTagsToAppRequest | The tags to attach or detach. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.AttachTagsToGroup(context.Background(), groupId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.AttachTagsToGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAttachTagsToGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **attachTagsToAppRequest** | [**AttachTagsToAppRequest**](AttachTagsToAppRequest.md) | The tags to attach or detach. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfigureGroup

> GetDevices200ResponseDataInnerGroup ConfigureGroup(ctx, groupId).Accept(accept).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupsAPI.ConfigureGroup(context.Background(), groupId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.ConfigureGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConfigureGroup`: GetDevices200ResponseDataInnerGroup
	fmt.Fprintf(os.Stdout, "Response from `GroupsAPI.ConfigureGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfigureGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetDevices200ResponseDataInnerGroup**](GetDevices200ResponseDataInnerGroup.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateGroup

> GetDevices200ResponseDataInnerGroup CreateGroup(ctx).Accept(accept).CreateGroupRequest(createGroupRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	createGroupRequest := *openapiclient.NewCreateGroupRequest("New Warehouse Group", "123e4567-e89b-12d3-a456-426614174001") // CreateGroupRequest | The group fields to create a new group. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupsAPI.CreateGroup(context.Background()).Accept(accept).CreateGroupRequest(createGroupRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.CreateGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateGroup`: GetDevices200ResponseDataInnerGroup
	fmt.Fprintf(os.Stdout, "Response from `GroupsAPI.CreateGroup`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **createGroupRequest** | [**CreateGroupRequest**](CreateGroupRequest.md) | The group fields to create a new group. | 

### Return type

[**GetDevices200ResponseDataInnerGroup**](GetDevices200ResponseDataInnerGroup.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteGroup

> DeleteGroup(ctx, groupId).Accept(accept).ReplacementGroupId(replacementGroupId).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	replacementGroupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of replacement group to move child groups to (only allowed for unconfigured groups) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.DeleteGroup(context.Background(), groupId).Accept(accept).ReplacementGroupId(replacementGroupId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.DeleteGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **replacementGroupId** | **string** | ID of replacement group to move child groups to (only allowed for unconfigured groups) | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DetachTagsFromGroup

> DetachTagsFromGroup(ctx, groupId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	attachTagsToAppRequest := *openapiclient.NewAttachTagsToAppRequest([]string{"Tags_example"}) // AttachTagsToAppRequest | The tags to attach or detach. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.DetachTagsFromGroup(context.Background(), groupId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.DetachTagsFromGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDetachTagsFromGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **attachTagsToAppRequest** | [**AttachTagsToAppRequest**](AttachTagsToAppRequest.md) | The tags to attach or detach. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DuplicateGroup

> GetDevices200ResponseDataInnerGroup DuplicateGroup(ctx, groupId).Accept(accept).DuplicateGroupRequest(duplicateGroupRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	duplicateGroupRequest := *openapiclient.NewDuplicateGroupRequest("Duplicated Warehouse Group") // DuplicateGroupRequest | The name for the duplicated group. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupsAPI.DuplicateGroup(context.Background(), groupId).Accept(accept).DuplicateGroupRequest(duplicateGroupRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.DuplicateGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DuplicateGroup`: GetDevices200ResponseDataInnerGroup
	fmt.Fprintf(os.Stdout, "Response from `GroupsAPI.DuplicateGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDuplicateGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **duplicateGroupRequest** | [**DuplicateGroupRequest**](DuplicateGroupRequest.md) | The name for the duplicated group. | 

### Return type

[**GetDevices200ResponseDataInnerGroup**](GetDevices200ResponseDataInnerGroup.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGroup

> GetDevices200ResponseDataInnerGroup GetGroup(ctx, groupId).Accept(accept).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupsAPI.GetGroup(context.Background(), groupId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.GetGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroup`: GetDevices200ResponseDataInnerGroup
	fmt.Fprintf(os.Stdout, "Response from `GroupsAPI.GetGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetDevices200ResponseDataInnerGroup**](GetDevices200ResponseDataInnerGroup.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGroupHierarchy

> GetGroupHierarchy200Response GetGroupHierarchy(ctx).Accept(accept).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupsAPI.GetGroupHierarchy(context.Background()).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.GetGroupHierarchy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroupHierarchy`: GetGroupHierarchy200Response
	fmt.Fprintf(os.Stdout, "Response from `GroupsAPI.GetGroupHierarchy`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupHierarchyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

### Return type

[**GetGroupHierarchy200Response**](GetGroupHierarchy200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGroupReleaseChannels

> GetGroupReleaseChannels200Response GetGroupReleaseChannels(ctx, groupId).Accept(accept).PerPage(perPage).Page(page).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupsAPI.GetGroupReleaseChannels(context.Background(), groupId).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.GetGroupReleaseChannels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroupReleaseChannels`: GetGroupReleaseChannels200Response
	fmt.Fprintf(os.Stdout, "Response from `GroupsAPI.GetGroupReleaseChannels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupReleaseChannelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetGroupReleaseChannels200Response**](GetGroupReleaseChannels200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGroups

> GetGroups200Response GetGroups(ctx).Accept(accept).PerPage(perPage).Page(page).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupsAPI.GetGroups(context.Background()).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.GetGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroups`: GetGroups200Response
	fmt.Fprintf(os.Stdout, "Response from `GroupsAPI.GetGroups`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetGroups200Response**](GetGroups200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveFileFromGroup

> RemoveFileFromGroup(ctx, groupId, fileId).Accept(accept).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.RemoveFileFromGroup(context.Background(), groupId, fileId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.RemoveFileFromGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveFileFromGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveReleaseChannelFromGroup

> RemoveReleaseChannelFromGroup(ctx, groupId, releaseChannelId).Accept(accept).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	releaseChannelId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a release channel.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.RemoveReleaseChannelFromGroup(context.Background(), groupId, releaseChannelId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.RemoveReleaseChannelFromGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 
**releaseChannelId** | **string** | The ID of a release channel. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveReleaseChannelFromGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveVideoFromGroup

> RemoveVideoFromGroup(ctx, groupId, videoId).Accept(accept).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GroupsAPI.RemoveVideoFromGroup(context.Background(), groupId, videoId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.RemoveVideoFromGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveVideoFromGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGroup

> GetDevices200ResponseDataInnerGroup UpdateGroup(ctx, groupId).Accept(accept).UpdateGroupRequest(updateGroupRequest).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	groupId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a group.
	updateGroupRequest := *openapiclient.NewUpdateGroupRequest("Updated Warehouse Group", "123e4567-e89b-12d3-a456-426614174001") // UpdateGroupRequest | The group fields to update an existing group. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GroupsAPI.UpdateGroup(context.Background(), groupId).Accept(accept).UpdateGroupRequest(updateGroupRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupsAPI.UpdateGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGroup`: GetDevices200ResponseDataInnerGroup
	fmt.Fprintf(os.Stdout, "Response from `GroupsAPI.UpdateGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **updateGroupRequest** | [**UpdateGroupRequest**](UpdateGroupRequest.md) | The group fields to update an existing group. | 

### Return type

[**GetDevices200ResponseDataInnerGroup**](GetDevices200ResponseDataInnerGroup.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

