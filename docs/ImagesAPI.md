# \ImagesAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CompleteImageUpload**](ImagesAPI.md#CompleteImageUpload) | **Post** /images/{imageId}/complete | 
[**GetImage**](ImagesAPI.md#GetImage) | **Get** /images/{imageId} | 
[**GetImages**](ImagesAPI.md#GetImages) | **Get** /images | 
[**InitiateImageUpload**](ImagesAPI.md#InitiateImageUpload) | **Post** /images | 
[**PreSignImageUpload**](ImagesAPI.md#PreSignImageUpload) | **Post** /images/{imageId}/pre-sign | 



## CompleteImageUpload

> GetImages200ResponseDataInner CompleteImageUpload(ctx, imageId).Accept(accept).CompleteImageUploadRequest(completeImageUploadRequest).Execute()





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
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the image.
	completeImageUploadRequest := *openapiclient.NewCompleteImageUploadRequest("images%2F123e4567-e89b-12d3-a456-426614174000%2Fwallpaper.jpg", "OGRhZDQ5NTMtOTQxYS00ZDI3LWE0MzUtOGUyNzEzZWZiYTlmLmY1YmE5NTkyLWIzZDMtNDE1ZS1iOWIxLWM1YWJjYjAxMmY5OQ", []openapiclient.CompleteImageUploadRequestPartsInner{*openapiclient.NewCompleteImageUploadRequestPartsInner(int32(123), "ETag_example")}) // CompleteImageUploadRequest | Complete a multipart upload for an image. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.CompleteImageUpload(context.Background(), imageId).Accept(accept).CompleteImageUploadRequest(completeImageUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.CompleteImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompleteImageUpload`: GetImages200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.CompleteImageUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** | The ID of the image. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCompleteImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **completeImageUploadRequest** | [**CompleteImageUploadRequest**](CompleteImageUploadRequest.md) | Complete a multipart upload for an image. | 

### Return type

[**GetImages200ResponseDataInner**](GetImages200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetImage

> GetImages200ResponseDataInner GetImage(ctx, imageId).Accept(accept).Execute()





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
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the image.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.GetImage(context.Background(), imageId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.GetImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetImage`: GetImages200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.GetImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** | The ID of the image. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetImages200ResponseDataInner**](GetImages200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetImages

> GetImages200Response GetImages(ctx).Accept(accept).Type_(type_).PerPage(perPage).Page(page).Execute()





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
	type_ := "type__example" // string | The type of images to retrieve.
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.GetImages(context.Background()).Accept(accept).Type_(type_).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.GetImages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetImages`: GetImages200Response
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.GetImages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetImagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **type_** | **string** | The type of images to retrieve. | 
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetImages200Response**](GetImages200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InitiateImageUpload

> InitiateImageUpload200Response InitiateImageUpload(ctx).Accept(accept).InitiateImageUploadRequest(initiateImageUploadRequest).Execute()





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
	initiateImageUploadRequest := *openapiclient.NewInitiateImageUploadRequest("wallpaper.jpg") // InitiateImageUploadRequest | Initiate a new image upload. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.InitiateImageUpload(context.Background()).Accept(accept).InitiateImageUploadRequest(initiateImageUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.InitiateImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InitiateImageUpload`: InitiateImageUpload200Response
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.InitiateImageUpload`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInitiateImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **initiateImageUploadRequest** | [**InitiateImageUploadRequest**](InitiateImageUploadRequest.md) | Initiate a new image upload. | 

### Return type

[**InitiateImageUpload200Response**](InitiateImageUpload200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PreSignImageUpload

> []PreSignImageUpload200ResponseInner PreSignImageUpload(ctx, imageId).Accept(accept).PreSignImageUploadRequest(preSignImageUploadRequest).Execute()





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
	imageId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the image.
	preSignImageUploadRequest := *openapiclient.NewPreSignImageUploadRequest("images%2F123e4567-e89b-12d3-a456-426614174000%2Fwallpaper.jpg", "OGRhZDQ5NTMtOTQxYS00ZDI3LWE0MzUtOGUyNzEzZWZiYTlmLmY1YmE5NTkyLWIzZDMtNDE1ZS1iOWIxLWM1YWJjYjAxMmY5OQ", []int32{int32(123)}) // PreSignImageUploadRequest | Pre-sign URLs for multipart upload parts. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.PreSignImageUpload(context.Background(), imageId).Accept(accept).PreSignImageUploadRequest(preSignImageUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.PreSignImageUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PreSignImageUpload`: []PreSignImageUpload200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.PreSignImageUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** | The ID of the image. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPreSignImageUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **preSignImageUploadRequest** | [**PreSignImageUploadRequest**](PreSignImageUploadRequest.md) | Pre-sign URLs for multipart upload parts. | 

### Return type

[**[]PreSignImageUpload200ResponseInner**](PreSignImageUpload200ResponseInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

