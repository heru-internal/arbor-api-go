# \FilesAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AttachTagsToFile**](FilesAPI.md#AttachTagsToFile) | **Patch** /files/{fileId}/tags/attach | 
[**CompleteFileUpload**](FilesAPI.md#CompleteFileUpload) | **Post** /files/{fileId}/complete | 
[**DeleteFile**](FilesAPI.md#DeleteFile) | **Delete** /files/{fileId} | 
[**DetachTagsFromFile**](FilesAPI.md#DetachTagsFromFile) | **Patch** /files/{fileId}/tags/detach | 
[**GetFile**](FilesAPI.md#GetFile) | **Get** /files/{fileId} | 
[**GetFileDeviceStatuses**](FilesAPI.md#GetFileDeviceStatuses) | **Get** /files/{fileId}/device-statuses | 
[**GetFiles**](FilesAPI.md#GetFiles) | **Get** /files | 
[**InitiateFileUpload**](FilesAPI.md#InitiateFileUpload) | **Post** /files | 
[**PreSignFileUpload**](FilesAPI.md#PreSignFileUpload) | **Post** /files/{fileId}/pre-sign | 



## AttachTagsToFile

> AttachTagsToFile(ctx, fileId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()





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
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.
	attachTagsToAppRequest := *openapiclient.NewAttachTagsToAppRequest([]string{"Tags_example"}) // AttachTagsToAppRequest | The tags to attach or detach. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FilesAPI.AttachTagsToFile(context.Background(), fileId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.AttachTagsToFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAttachTagsToFileRequest struct via the builder pattern


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


## CompleteFileUpload

> GetAppFiles200ResponseDataInner CompleteFileUpload(ctx, fileId).Accept(accept).CompleteFileUploadRequest(completeFileUploadRequest).Execute()





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
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.
	completeFileUploadRequest := *openapiclient.NewCompleteFileUploadRequest("xrdm-016da47e-4c49-48ad-9c61-94904e06a226/files/2f5d24ec-be98-49d3-ac42-cdecbeea40f0/f40d390d-94fc-47a9-952c-8b7321f3eefc/my-file.txt", "OGRhZDQ5NTMtOTQxYS00ZDI3LWE0MzUtOGUyNzEzZWZiYTlmLmY1YmE5NTkyLWIzZDMtNDE1ZS1iOWIxLWM1YWJjYjAxMmY5OQ", []openapiclient.CompleteAppVersionUploadRequestPartsInner{*openapiclient.NewCompleteAppVersionUploadRequestPartsInner(int32(1), "d41d8cd98f00b204e9800998ecf8427e")}) // CompleteFileUploadRequest | The fields to complete the upload. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.CompleteFileUpload(context.Background(), fileId).Accept(accept).CompleteFileUploadRequest(completeFileUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.CompleteFileUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompleteFileUpload`: GetAppFiles200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.CompleteFileUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCompleteFileUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **completeFileUploadRequest** | [**CompleteFileUploadRequest**](CompleteFileUploadRequest.md) | The fields to complete the upload. | 

### Return type

[**GetAppFiles200ResponseDataInner**](GetAppFiles200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteFile

> DeleteFile(ctx, fileId).Accept(accept).Execute()





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
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FilesAPI.DeleteFile(context.Background(), fileId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.DeleteFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteFileRequest struct via the builder pattern


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


## DetachTagsFromFile

> DetachTagsFromFile(ctx, fileId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()





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
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.
	attachTagsToAppRequest := *openapiclient.NewAttachTagsToAppRequest([]string{"Tags_example"}) // AttachTagsToAppRequest | The tags to attach or detach. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FilesAPI.DetachTagsFromFile(context.Background(), fileId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.DetachTagsFromFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDetachTagsFromFileRequest struct via the builder pattern


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


## GetFile

> GetAppFiles200ResponseDataInner GetFile(ctx, fileId).Accept(accept).Execute()





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
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.GetFile(context.Background(), fileId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.GetFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFile`: GetAppFiles200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.GetFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetAppFiles200ResponseDataInner**](GetAppFiles200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFileDeviceStatuses

> GetFileDeviceStatuses200Response GetFileDeviceStatuses(ctx, fileId).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.GetFileDeviceStatuses(context.Background(), fileId).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.GetFileDeviceStatuses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFileDeviceStatuses`: GetFileDeviceStatuses200Response
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.GetFileDeviceStatuses`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFileDeviceStatusesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetFileDeviceStatuses200Response**](GetFileDeviceStatuses200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFiles

> GetFiles200Response GetFiles(ctx).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	resp, r, err := apiClient.FilesAPI.GetFiles(context.Background()).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.GetFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFiles`: GetFiles200Response
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.GetFiles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetFiles200Response**](GetFiles200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InitiateFileUpload

> InitiateFileUpload200Response InitiateFileUpload(ctx).Accept(accept).InitiateFileUploadRequest(initiateFileUploadRequest).Execute()





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
	initiateFileUploadRequest := *openapiclient.NewInitiateFileUploadRequest("my-file.txt", "/sdcard/my-files/some-sub-directory") // InitiateFileUploadRequest | Initiate a new file upload. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.InitiateFileUpload(context.Background()).Accept(accept).InitiateFileUploadRequest(initiateFileUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.InitiateFileUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InitiateFileUpload`: InitiateFileUpload200Response
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.InitiateFileUpload`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInitiateFileUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **initiateFileUploadRequest** | [**InitiateFileUploadRequest**](InitiateFileUploadRequest.md) | Initiate a new file upload. | 

### Return type

[**InitiateFileUpload200Response**](InitiateFileUpload200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PreSignFileUpload

> []PreSignFileUpload200ResponseInner PreSignFileUpload(ctx, fileId).Accept(accept).PreSignAppVersionUploadRequest(preSignAppVersionUploadRequest).Execute()





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
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.
	preSignAppVersionUploadRequest := *openapiclient.NewPreSignAppVersionUploadRequest("xrdm-016da47e-4c49-48ad-9c61-94904e06a226/apps/2f5d24ec-be98-49d3-ac42-cdecbeea40f0/f40d390d-94fc-47a9-952c-8b7321f3eefc/my-app.apk", "OGRhZDQ5NTMtOTQxYS00ZDI3LWE0MzUtOGUyNzEzZWZiYTlmLmY1YmE5NTkyLWIzZDMtNDE1ZS1iOWIxLWM1YWJjYjAxMmY5OQ", []int32{int32(1)}) // PreSignAppVersionUploadRequest | The fields to retrieve presigned URLs. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FilesAPI.PreSignFileUpload(context.Background(), fileId).Accept(accept).PreSignAppVersionUploadRequest(preSignAppVersionUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FilesAPI.PreSignFileUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PreSignFileUpload`: []PreSignFileUpload200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `FilesAPI.PreSignFileUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPreSignFileUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **preSignAppVersionUploadRequest** | [**PreSignAppVersionUploadRequest**](PreSignAppVersionUploadRequest.md) | The fields to retrieve presigned URLs. | 

### Return type

[**[]PreSignFileUpload200ResponseInner**](PreSignFileUpload200ResponseInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

