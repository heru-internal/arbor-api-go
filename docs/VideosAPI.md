# \VideosAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AttachTagsToVideo**](VideosAPI.md#AttachTagsToVideo) | **Patch** /videos/{videoId}/tags/attach | 
[**CompleteVideoUpload**](VideosAPI.md#CompleteVideoUpload) | **Post** /videos/{videoId}/complete | 
[**DeleteVideo**](VideosAPI.md#DeleteVideo) | **Delete** /videos/{videoId} | 
[**DetachTagsFromVideo**](VideosAPI.md#DetachTagsFromVideo) | **Patch** /videos/{videoId}/tags/detach | 
[**GetVideo**](VideosAPI.md#GetVideo) | **Get** /videos/{videoId} | 
[**GetVideoDeviceStatuses**](VideosAPI.md#GetVideoDeviceStatuses) | **Get** /videos/{videoId}/device-statuses | 
[**GetVideos**](VideosAPI.md#GetVideos) | **Get** /videos | 
[**InitiateVideoUpload**](VideosAPI.md#InitiateVideoUpload) | **Post** /videos | 
[**PreSignVideoUpload**](VideosAPI.md#PreSignVideoUpload) | **Post** /videos/{videoId}/pre-sign | 
[**UpdateVideo**](VideosAPI.md#UpdateVideo) | **Put** /videos/{videoId} | 



## AttachTagsToVideo

> AttachTagsToVideo(ctx, videoId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()





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
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.
	attachTagsToAppRequest := *openapiclient.NewAttachTagsToAppRequest([]string{"Tags_example"}) // AttachTagsToAppRequest | The tags to attach or detach. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VideosAPI.AttachTagsToVideo(context.Background(), videoId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.AttachTagsToVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAttachTagsToVideoRequest struct via the builder pattern


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


## CompleteVideoUpload

> GetVideos200ResponseDataInner CompleteVideoUpload(ctx, videoId).Accept(accept).CompleteVideoUploadRequest(completeVideoUploadRequest).Execute()





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
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.
	completeVideoUploadRequest := *openapiclient.NewCompleteVideoUploadRequest("xrdm-016da47e-4c49-48ad-9c61-94904e06a226/videos/2f5d24ec-be98-49d3-ac42-cdecbeea40f0/f40d390d-94fc-47a9-952c-8b7321f3eefc/my-video.mp4", "OGRhZDQ5NTMtOTQxYS00ZDI3LWE0MzUtOGUyNzEzZWZiYTlmLmY1YmE5NTkyLWIzZDMtNDE1ZS1iOWIxLWM1YWJjYjAxMmY5OQ", []openapiclient.CompleteAppVersionUploadRequestPartsInner{*openapiclient.NewCompleteAppVersionUploadRequestPartsInner(int32(1), "d41d8cd98f00b204e9800998ecf8427e")}) // CompleteVideoUploadRequest | The fields to complete the video upload. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.CompleteVideoUpload(context.Background(), videoId).Accept(accept).CompleteVideoUploadRequest(completeVideoUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.CompleteVideoUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompleteVideoUpload`: GetVideos200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.CompleteVideoUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCompleteVideoUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **completeVideoUploadRequest** | [**CompleteVideoUploadRequest**](CompleteVideoUploadRequest.md) | The fields to complete the video upload. | 

### Return type

[**GetVideos200ResponseDataInner**](GetVideos200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteVideo

> DeleteVideo(ctx, videoId).Accept(accept).Execute()





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
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VideosAPI.DeleteVideo(context.Background(), videoId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.DeleteVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteVideoRequest struct via the builder pattern


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


## DetachTagsFromVideo

> DetachTagsFromVideo(ctx, videoId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()





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
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.
	attachTagsToAppRequest := *openapiclient.NewAttachTagsToAppRequest([]string{"Tags_example"}) // AttachTagsToAppRequest | The tags to attach or detach. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VideosAPI.DetachTagsFromVideo(context.Background(), videoId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.DetachTagsFromVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDetachTagsFromVideoRequest struct via the builder pattern


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


## GetVideo

> GetVideos200ResponseDataInner GetVideo(ctx, videoId).Accept(accept).Execute()





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
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.GetVideo(context.Background(), videoId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.GetVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVideo`: GetVideos200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.GetVideo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVideoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetVideos200ResponseDataInner**](GetVideos200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVideoDeviceStatuses

> GetVideoDeviceStatuses200Response GetVideoDeviceStatuses(ctx, videoId).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.GetVideoDeviceStatuses(context.Background(), videoId).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.GetVideoDeviceStatuses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVideoDeviceStatuses`: GetVideoDeviceStatuses200Response
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.GetVideoDeviceStatuses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVideoDeviceStatusesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetVideoDeviceStatuses200Response**](GetVideoDeviceStatuses200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVideos

> GetVideos200Response GetVideos(ctx).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	resp, r, err := apiClient.VideosAPI.GetVideos(context.Background()).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.GetVideos``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVideos`: GetVideos200Response
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.GetVideos`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVideosRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetVideos200Response**](GetVideos200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InitiateVideoUpload

> InitiateVideoUpload200Response InitiateVideoUpload(ctx).Accept(accept).InitiateVideoUploadRequest(initiateVideoUploadRequest).Execute()





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
	initiateVideoUploadRequest := *openapiclient.NewInitiateVideoUploadRequest("my-video.mp4", "ThreeSixty", "STEREO") // InitiateVideoUploadRequest | Initiate a new video upload. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.InitiateVideoUpload(context.Background()).Accept(accept).InitiateVideoUploadRequest(initiateVideoUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.InitiateVideoUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InitiateVideoUpload`: InitiateVideoUpload200Response
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.InitiateVideoUpload`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInitiateVideoUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **initiateVideoUploadRequest** | [**InitiateVideoUploadRequest**](InitiateVideoUploadRequest.md) | Initiate a new video upload. | 

### Return type

[**InitiateVideoUpload200Response**](InitiateVideoUpload200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PreSignVideoUpload

> []PreSignVideoUpload200ResponseInner PreSignVideoUpload(ctx, videoId).Accept(accept).PreSignVideoUploadRequest(preSignVideoUploadRequest).Execute()





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
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.
	preSignVideoUploadRequest := *openapiclient.NewPreSignVideoUploadRequest("xrdm-016da47e-4c49-48ad-9c61-94904e06a226/videos/2f5d24ec-be98-49d3-ac42-cdecbeea40f0/f40d390d-94fc-47a9-952c-8b7321f3eefc/my-video.mp4", "OGRhZDQ5NTMtOTQxYS00ZDI3LWE0MzUtOGUyNzEzZWZiYTlmLmY1YmE5NTkyLWIzZDMtNDE1ZS1iOWIxLWM1YWJjYjAxMmY5OQ", []int32{int32(1)}) // PreSignVideoUploadRequest | The fields to retrieve presigned URLs for video upload. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.PreSignVideoUpload(context.Background(), videoId).Accept(accept).PreSignVideoUploadRequest(preSignVideoUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.PreSignVideoUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PreSignVideoUpload`: []PreSignVideoUpload200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.PreSignVideoUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPreSignVideoUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **preSignVideoUploadRequest** | [**PreSignVideoUploadRequest**](PreSignVideoUploadRequest.md) | The fields to retrieve presigned URLs for video upload. | 

### Return type

[**[]PreSignVideoUpload200ResponseInner**](PreSignVideoUpload200ResponseInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateVideo

> GetVideos200ResponseDataInner UpdateVideo(ctx, videoId).Accept(accept).UpdateVideoRequest(updateVideoRequest).Execute()





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
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.
	updateVideoRequest := *openapiclient.NewUpdateVideoRequest("Updated Training Video", "Updated description for the training video", "ThreeSixty", "STEREO", []string{"Tags_example"}) // UpdateVideoRequest | Update a video

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.UpdateVideo(context.Background(), videoId).Accept(accept).UpdateVideoRequest(updateVideoRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.UpdateVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateVideo`: GetVideos200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.UpdateVideo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateVideoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **updateVideoRequest** | [**UpdateVideoRequest**](UpdateVideoRequest.md) | Update a video | 

### Return type

[**GetVideos200ResponseDataInner**](GetVideos200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

