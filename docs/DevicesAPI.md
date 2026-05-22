# \DevicesAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddFileToDevice**](DevicesAPI.md#AddFileToDevice) | **Post** /devices/{deviceId}/files | 
[**AddReleaseChannelToDevice**](DevicesAPI.md#AddReleaseChannelToDevice) | **Post** /devices/{deviceId}/release-channels | 
[**AddVideoToDevice**](DevicesAPI.md#AddVideoToDevice) | **Post** /devices/{deviceId}/videos | 
[**AttachTagsToDevice**](DevicesAPI.md#AttachTagsToDevice) | **Patch** /devices/{deviceId}/tags/attach | 
[**CheckFingerprint**](DevicesAPI.md#CheckFingerprint) | **Post** /devices/{deviceId}/fingerprint | 
[**ClearAppDataForApp**](DevicesAPI.md#ClearAppDataForApp) | **Post** /devices/{deviceId}/clear-data/apps/{appId} | 
[**ClearAppDataForPackage**](DevicesAPI.md#ClearAppDataForPackage) | **Post** /devices/{deviceId}/clear-data/packages/{packageName} | 
[**DetachTagsFromDevice**](DevicesAPI.md#DetachTagsFromDevice) | **Patch** /devices/{deviceId}/tags/detach | 
[**FactoryResetDevice**](DevicesAPI.md#FactoryResetDevice) | **Post** /devices/{deviceId}/factory-reset | 
[**GetDevice**](DevicesAPI.md#GetDevice) | **Get** /devices/{deviceId} | 
[**GetDeviceFiles**](DevicesAPI.md#GetDeviceFiles) | **Get** /devices/{deviceId}/files | 
[**GetDeviceReleaseChannels**](DevicesAPI.md#GetDeviceReleaseChannels) | **Get** /devices/{deviceId}/release-channels | 
[**GetDeviceVideos**](DevicesAPI.md#GetDeviceVideos) | **Get** /devices/{deviceId}/videos | 
[**GetDevices**](DevicesAPI.md#GetDevices) | **Get** /devices | 
[**LaunchApp**](DevicesAPI.md#LaunchApp) | **Post** /devices/{deviceId}/launch/apps/{appId} | 
[**LaunchPackage**](DevicesAPI.md#LaunchPackage) | **Post** /devices/{deviceId}/launch/packages/{packageName} | 
[**LaunchVideo**](DevicesAPI.md#LaunchVideo) | **Post** /devices/{deviceId}/launch/videos/{videoId} | 
[**MigrateDeviceToOrganization**](DevicesAPI.md#MigrateDeviceToOrganization) | **Post** /devices/{deviceId}/migrate/{organizationSlug} | 
[**RebootDevice**](DevicesAPI.md#RebootDevice) | **Post** /devices/{deviceId}/reboot | 
[**RemoveFileFromDevice**](DevicesAPI.md#RemoveFileFromDevice) | **Delete** /devices/{deviceId}/files/{fileId} | 
[**RemoveReleaseChannelFromDevice**](DevicesAPI.md#RemoveReleaseChannelFromDevice) | **Delete** /devices/{deviceId}/release-channels/{releaseChannelId} | 
[**RemoveVideoFromDevice**](DevicesAPI.md#RemoveVideoFromDevice) | **Delete** /devices/{deviceId}/videos/{videoId} | 
[**ShutDownDevice**](DevicesAPI.md#ShutDownDevice) | **Post** /devices/{deviceId}/shut-down | 
[**UpdateDevice**](DevicesAPI.md#UpdateDevice) | **Put** /devices/{deviceId} | 
[**UpdateDeviceCustomFields**](DevicesAPI.md#UpdateDeviceCustomFields) | **Patch** /devices/{deviceId}/custom-fields | 



## AddFileToDevice

> AddFileToDevice(ctx, deviceId).Accept(accept).AddFileToDeviceRequest(addFileToDeviceRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	addFileToDeviceRequest := *openapiclient.NewAddFileToDeviceRequest("123e4567-e89b-12d3-a456-426614174000") // AddFileToDeviceRequest | The file to add to the device. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.AddFileToDevice(context.Background(), deviceId).Accept(accept).AddFileToDeviceRequest(addFileToDeviceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.AddFileToDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddFileToDeviceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **addFileToDeviceRequest** | [**AddFileToDeviceRequest**](AddFileToDeviceRequest.md) | The file to add to the device. | 

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


## AddReleaseChannelToDevice

> AddReleaseChannelToDevice(ctx, deviceId).Accept(accept).AddReleaseChannelToDeviceRequest(addReleaseChannelToDeviceRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	addReleaseChannelToDeviceRequest := *openapiclient.NewAddReleaseChannelToDeviceRequest("123e4567-e89b-12d3-a456-426614174000") // AddReleaseChannelToDeviceRequest | The release channel to add to the device. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.AddReleaseChannelToDevice(context.Background(), deviceId).Accept(accept).AddReleaseChannelToDeviceRequest(addReleaseChannelToDeviceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.AddReleaseChannelToDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddReleaseChannelToDeviceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **addReleaseChannelToDeviceRequest** | [**AddReleaseChannelToDeviceRequest**](AddReleaseChannelToDeviceRequest.md) | The release channel to add to the device. | 

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


## AddVideoToDevice

> AddVideoToDevice(ctx, deviceId).Accept(accept).AddVideoToDeviceRequest(addVideoToDeviceRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	addVideoToDeviceRequest := *openapiclient.NewAddVideoToDeviceRequest("123e4567-e89b-12d3-a456-426614174000") // AddVideoToDeviceRequest | The video to add to the device. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.AddVideoToDevice(context.Background(), deviceId).Accept(accept).AddVideoToDeviceRequest(addVideoToDeviceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.AddVideoToDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddVideoToDeviceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **addVideoToDeviceRequest** | [**AddVideoToDeviceRequest**](AddVideoToDeviceRequest.md) | The video to add to the device. | 

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


## AttachTagsToDevice

> AttachTagsToDevice(ctx, deviceId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	attachTagsToAppRequest := *openapiclient.NewAttachTagsToAppRequest([]string{"Tags_example"}) // AttachTagsToAppRequest | The tags to attach or detach. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.AttachTagsToDevice(context.Background(), deviceId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.AttachTagsToDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAttachTagsToDeviceRequest struct via the builder pattern


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


## CheckFingerprint

> CheckFingerprint(ctx, deviceId).Accept(accept).CheckFingerprintRequest(checkFingerprintRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	checkFingerprintRequest := *openapiclient.NewCheckFingerprintRequest("d41d8cd98f00b204e9800998ecf8427e") // CheckFingerprintRequest | The fingerprint to check. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.CheckFingerprint(context.Background(), deviceId).Accept(accept).CheckFingerprintRequest(checkFingerprintRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.CheckFingerprint``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckFingerprintRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **checkFingerprintRequest** | [**CheckFingerprintRequest**](CheckFingerprintRequest.md) | The fingerprint to check. | 

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


## ClearAppDataForApp

> ClearAppDataForApp(ctx, deviceId, appId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.ClearAppDataForApp(context.Background(), deviceId, appId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.ClearAppDataForApp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**appId** | **string** | The ID of an app. | 

### Other Parameters

Other parameters are passed through a pointer to a apiClearAppDataForAppRequest struct via the builder pattern


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


## ClearAppDataForPackage

> ClearAppDataForPackage(ctx, deviceId, packageName).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	packageName := "packageName_example" // string | The package name of an app (e.g. com.example.app).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.ClearAppDataForPackage(context.Background(), deviceId, packageName).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.ClearAppDataForPackage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**packageName** | **string** | The package name of an app (e.g. com.example.app). | 

### Other Parameters

Other parameters are passed through a pointer to a apiClearAppDataForPackageRequest struct via the builder pattern


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


## DetachTagsFromDevice

> DetachTagsFromDevice(ctx, deviceId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	attachTagsToAppRequest := *openapiclient.NewAttachTagsToAppRequest([]string{"Tags_example"}) // AttachTagsToAppRequest | The tags to attach or detach. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.DetachTagsFromDevice(context.Background(), deviceId).Accept(accept).AttachTagsToAppRequest(attachTagsToAppRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.DetachTagsFromDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDetachTagsFromDeviceRequest struct via the builder pattern


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


## FactoryResetDevice

> FactoryResetDevice(ctx, deviceId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.FactoryResetDevice(context.Background(), deviceId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.FactoryResetDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiFactoryResetDeviceRequest struct via the builder pattern


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


## GetDevice

> GetDevices200ResponseDataInner GetDevice(ctx, deviceId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DevicesAPI.GetDevice(context.Background(), deviceId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.GetDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDevice`: GetDevices200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `DevicesAPI.GetDevice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetDevices200ResponseDataInner**](GetDevices200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceFiles

> GetDeviceFiles200Response GetDeviceFiles(ctx, deviceId).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DevicesAPI.GetDeviceFiles(context.Background(), deviceId).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.GetDeviceFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceFiles`: GetDeviceFiles200Response
	fmt.Fprintf(os.Stdout, "Response from `DevicesAPI.GetDeviceFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetDeviceFiles200Response**](GetDeviceFiles200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceReleaseChannels

> GetDeviceReleaseChannels200Response GetDeviceReleaseChannels(ctx, deviceId).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DevicesAPI.GetDeviceReleaseChannels(context.Background(), deviceId).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.GetDeviceReleaseChannels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceReleaseChannels`: GetDeviceReleaseChannels200Response
	fmt.Fprintf(os.Stdout, "Response from `DevicesAPI.GetDeviceReleaseChannels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceReleaseChannelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetDeviceReleaseChannels200Response**](GetDeviceReleaseChannels200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceVideos

> GetDeviceVideos200Response GetDeviceVideos(ctx, deviceId).Accept(accept).PerPage(perPage).Page(page).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DevicesAPI.GetDeviceVideos(context.Background(), deviceId).Accept(accept).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.GetDeviceVideos``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceVideos`: GetDeviceVideos200Response
	fmt.Fprintf(os.Stdout, "Response from `DevicesAPI.GetDeviceVideos`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceVideosRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]

### Return type

[**GetDeviceVideos200Response**](GetDeviceVideos200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDevices

> GetDevices200Response GetDevices(ctx).Accept(accept).PerPage(perPage).Page(page).State(state).TagsAll(tagsAll).TagsAny(tagsAny).CustomFieldsAll(customFieldsAll).CustomFieldsAny(customFieldsAny).AndroidVersions(androidVersions).OsVersions(osVersions).ClientAppVersions(clientAppVersions).HomeAppVersions(homeAppVersions).EnrollmentMethods(enrollmentMethods).GroupIds(groupIds).DeviceModelIds(deviceModelIds).DeviceSerialNumbers(deviceSerialNumbers).LastOnline(lastOnline).ComplianceStatus(complianceStatus).HmsModes(hmsModes).Execute()





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
	state := "state_example" // string | Filter devices by their state. Defaults to 'active' if not specified. (optional) (default to "active")
	tagsAll := []string{"Inner_example"} // []string | Filter devices by all of the specified tags. This parameter allows you to search for devices that have all of the provided tags. The tags should be provided as a query-parameter array. e.g. `?tags_all[]=tag1&tags_all[]=tag2`. Cannot be used with `tags_any` parameter. (optional)
	tagsAny := []string{"Inner_example"} // []string | Filter devices by any of the specified tags. This parameter allows you to search for devices that have at least one of the provided tags. The tags should be provided as a query-parameter array. e.g. `?tags_any[]=tag1&tags_any[]=tag2`. Cannot be used with `tags_all` parameter. (optional)
	customFieldsAll := []string{"Inner_example"} // []string | Filter devices by all of the specified custom fields. This parameter allows you to search for devices that have all of the provided custom field values. The custom fields should be provided as a query-parameter array. e.g. `?custom_fields_all[name1]=value1&custom_fields_all[name2]=value2`. Cannot be used with `custom_fields_any` parameter. (optional)
	customFieldsAny := []string{"Inner_example"} // []string | Filter devices by any of the specified custom fields. This parameter allows you to search for devices that have any of the provided custom field values. The custom fields should be provided as a query-parameter array. e.g. `?custom_fields_any[name1]=value1&custom_fields_any[name2]=value2`. Cannot be used with `custom_fields_all` parameter. (optional)
	androidVersions := []string{"Inner_example"} // []string | Filter devices by Android versions. This parameter allows you to search for devices that are running any of the provided Android versions. The Android versions should be provided as a query-parameter array. e.g. `?android_versions[]=value1&android_versions[]=value2`. Provide the full version string, e.g. `12`, `11`, or `unknown` to retrieve devices that haven't reported their version number. (optional)
	osVersions := []string{"Inner_example"} // []string | Filter devices by OS versions. This parameter allows you to search for devices that are running any of the provided OS versions. The OS versions should be provided as a query-parameter array. e.g. `?os_versions[]=value1&os_versions[]=value2`. Provide the full version string, e.g. `5.13.4`, `5.12.6`, or `unknown` to retrieve devices that haven't reported their version number. (optional)
	clientAppVersions := []string{"Inner_example"} // []string | Filter devices by ArborXR Client App versions. This parameter allows you to search for devices that are running any of the provided client app versions. The client app versions should be provided as a query-parameter array. e.g. `?client_app_versions[]=value1&client_app_versions[]=value2`. Provide the full version string, e.g. `2025.1.0`, `2024.4.2`, or `unknown` to retrieve devices that haven't reported their version number. (optional)
	homeAppVersions := []string{"Inner_example"} // []string | Filter devices by ArborXR Home App versions. This parameter allows you to search for devices that are running any of the provided home app versions. The home app versions should be provided as a query-parameter array. e.g. `?home_app_versions[]=value1&home_app_versions[]=value2`. Provide the full version string, e.g. `2025.1.0`, `2024.4.2`, or `unknown` to retrieve devices that haven't reported their version number. (optional)
	enrollmentMethods := []string{"EnrollmentMethods_example"} // []string | Filter devices by enrollment methods. This parameter allows you to search for devices that were enrolled using any of the provided methods. The enrollment methods should be provided as a query-parameter array. e.g. `?enrollment_methods[]=value1&enrollment_methods[]=value2`. (optional)
	groupIds := []*string{"Inner_example"} // []*string | Filter devices by group IDs (null for ungrouped devices). This parameter allows you to search for devices that belong to any of the provided groups, or sub-groups thereof. The group IDs should be provided as a query-parameter array. e.g. `?group_ids[]=value1&group_ids[]=value2`. Use an empty value to retrieve ungrouped devices. e.g. `?group_ids[]=&group_ids[]=value2`, e.g.2. `?group_ids[]=`. (optional)
	deviceModelIds := []string{"Inner_example"} // []string | Filter devices by device model IDs. This parameter allows you to search for devices of any of the provided device models. The device model IDs should be provided as a query-parameter array. e.g. `?device_model_ids[]=value1&device_model_ids[]=value2`. (optional)
	deviceSerialNumbers := []string{"Inner_example"} // []string | Filter devices by device serial numbers. This parameter allows you to search for devices of any of the provided device serial numbers. The device serial numbers should be provided as a query-parameter array. e.g. `?device_serial_numbers[]=value1&device_serial_numbers[]=value2`. (optional)
	lastOnline := "lastOnline_example" // string | Filter devices by when they were last online. This parameter allows you to search for devices based on their last online activity. (optional)
	complianceStatus := "complianceStatus_example" // string | Filter devices by their compliance status. This parameter allows you to search for devices based on their compliance status. (optional)
	hmsModes := []string{"HmsModes_example"} // []string | Filter devices by Meta Hms modes. This parameter allows you to search for devices that are in any of the provided Hms modes. The Hms modes should be provided as a query-parameter array. e.g. `?hms_modes[]=value1&hms_modes[]=value2`. Use `UNKNOWN` to find Meta Hms devices whose mode is not reported. Use `NON_APPLICABLE` to include non-Meta Hms devices. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DevicesAPI.GetDevices(context.Background()).Accept(accept).PerPage(perPage).Page(page).State(state).TagsAll(tagsAll).TagsAny(tagsAny).CustomFieldsAll(customFieldsAll).CustomFieldsAny(customFieldsAny).AndroidVersions(androidVersions).OsVersions(osVersions).ClientAppVersions(clientAppVersions).HomeAppVersions(homeAppVersions).EnrollmentMethods(enrollmentMethods).GroupIds(groupIds).DeviceModelIds(deviceModelIds).DeviceSerialNumbers(deviceSerialNumbers).LastOnline(lastOnline).ComplianceStatus(complianceStatus).HmsModes(hmsModes).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.GetDevices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDevices`: GetDevices200Response
	fmt.Fprintf(os.Stdout, "Response from `DevicesAPI.GetDevices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDevicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]
 **state** | **string** | Filter devices by their state. Defaults to &#39;active&#39; if not specified. | [default to &quot;active&quot;]
 **tagsAll** | **[]string** | Filter devices by all of the specified tags. This parameter allows you to search for devices that have all of the provided tags. The tags should be provided as a query-parameter array. e.g. &#x60;?tags_all[]&#x3D;tag1&amp;tags_all[]&#x3D;tag2&#x60;. Cannot be used with &#x60;tags_any&#x60; parameter. | 
 **tagsAny** | **[]string** | Filter devices by any of the specified tags. This parameter allows you to search for devices that have at least one of the provided tags. The tags should be provided as a query-parameter array. e.g. &#x60;?tags_any[]&#x3D;tag1&amp;tags_any[]&#x3D;tag2&#x60;. Cannot be used with &#x60;tags_all&#x60; parameter. | 
 **customFieldsAll** | **[]string** | Filter devices by all of the specified custom fields. This parameter allows you to search for devices that have all of the provided custom field values. The custom fields should be provided as a query-parameter array. e.g. &#x60;?custom_fields_all[name1]&#x3D;value1&amp;custom_fields_all[name2]&#x3D;value2&#x60;. Cannot be used with &#x60;custom_fields_any&#x60; parameter. | 
 **customFieldsAny** | **[]string** | Filter devices by any of the specified custom fields. This parameter allows you to search for devices that have any of the provided custom field values. The custom fields should be provided as a query-parameter array. e.g. &#x60;?custom_fields_any[name1]&#x3D;value1&amp;custom_fields_any[name2]&#x3D;value2&#x60;. Cannot be used with &#x60;custom_fields_all&#x60; parameter. | 
 **androidVersions** | **[]string** | Filter devices by Android versions. This parameter allows you to search for devices that are running any of the provided Android versions. The Android versions should be provided as a query-parameter array. e.g. &#x60;?android_versions[]&#x3D;value1&amp;android_versions[]&#x3D;value2&#x60;. Provide the full version string, e.g. &#x60;12&#x60;, &#x60;11&#x60;, or &#x60;unknown&#x60; to retrieve devices that haven&#39;t reported their version number. | 
 **osVersions** | **[]string** | Filter devices by OS versions. This parameter allows you to search for devices that are running any of the provided OS versions. The OS versions should be provided as a query-parameter array. e.g. &#x60;?os_versions[]&#x3D;value1&amp;os_versions[]&#x3D;value2&#x60;. Provide the full version string, e.g. &#x60;5.13.4&#x60;, &#x60;5.12.6&#x60;, or &#x60;unknown&#x60; to retrieve devices that haven&#39;t reported their version number. | 
 **clientAppVersions** | **[]string** | Filter devices by ArborXR Client App versions. This parameter allows you to search for devices that are running any of the provided client app versions. The client app versions should be provided as a query-parameter array. e.g. &#x60;?client_app_versions[]&#x3D;value1&amp;client_app_versions[]&#x3D;value2&#x60;. Provide the full version string, e.g. &#x60;2025.1.0&#x60;, &#x60;2024.4.2&#x60;, or &#x60;unknown&#x60; to retrieve devices that haven&#39;t reported their version number. | 
 **homeAppVersions** | **[]string** | Filter devices by ArborXR Home App versions. This parameter allows you to search for devices that are running any of the provided home app versions. The home app versions should be provided as a query-parameter array. e.g. &#x60;?home_app_versions[]&#x3D;value1&amp;home_app_versions[]&#x3D;value2&#x60;. Provide the full version string, e.g. &#x60;2025.1.0&#x60;, &#x60;2024.4.2&#x60;, or &#x60;unknown&#x60; to retrieve devices that haven&#39;t reported their version number. | 
 **enrollmentMethods** | **[]string** | Filter devices by enrollment methods. This parameter allows you to search for devices that were enrolled using any of the provided methods. The enrollment methods should be provided as a query-parameter array. e.g. &#x60;?enrollment_methods[]&#x3D;value1&amp;enrollment_methods[]&#x3D;value2&#x60;. | 
 **groupIds** | **[]string** | Filter devices by group IDs (null for ungrouped devices). This parameter allows you to search for devices that belong to any of the provided groups, or sub-groups thereof. The group IDs should be provided as a query-parameter array. e.g. &#x60;?group_ids[]&#x3D;value1&amp;group_ids[]&#x3D;value2&#x60;. Use an empty value to retrieve ungrouped devices. e.g. &#x60;?group_ids[]&#x3D;&amp;group_ids[]&#x3D;value2&#x60;, e.g.2. &#x60;?group_ids[]&#x3D;&#x60;. | 
 **deviceModelIds** | **[]string** | Filter devices by device model IDs. This parameter allows you to search for devices of any of the provided device models. The device model IDs should be provided as a query-parameter array. e.g. &#x60;?device_model_ids[]&#x3D;value1&amp;device_model_ids[]&#x3D;value2&#x60;. | 
 **deviceSerialNumbers** | **[]string** | Filter devices by device serial numbers. This parameter allows you to search for devices of any of the provided device serial numbers. The device serial numbers should be provided as a query-parameter array. e.g. &#x60;?device_serial_numbers[]&#x3D;value1&amp;device_serial_numbers[]&#x3D;value2&#x60;. | 
 **lastOnline** | **string** | Filter devices by when they were last online. This parameter allows you to search for devices based on their last online activity. | 
 **complianceStatus** | **string** | Filter devices by their compliance status. This parameter allows you to search for devices based on their compliance status. | 
 **hmsModes** | **[]string** | Filter devices by Meta Hms modes. This parameter allows you to search for devices that are in any of the provided Hms modes. The Hms modes should be provided as a query-parameter array. e.g. &#x60;?hms_modes[]&#x3D;value1&amp;hms_modes[]&#x3D;value2&#x60;. Use &#x60;UNKNOWN&#x60; to find Meta Hms devices whose mode is not reported. Use &#x60;NON_APPLICABLE&#x60; to include non-Meta Hms devices. | 

### Return type

[**GetDevices200Response**](GetDevices200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LaunchApp

> LaunchApp(ctx, deviceId, appId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of an app.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.LaunchApp(context.Background(), deviceId, appId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.LaunchApp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**appId** | **string** | The ID of an app. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLaunchAppRequest struct via the builder pattern


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


## LaunchPackage

> LaunchPackage(ctx, deviceId, packageName).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	packageName := "packageName_example" // string | The package name of an app (e.g. com.example.app).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.LaunchPackage(context.Background(), deviceId, packageName).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.LaunchPackage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**packageName** | **string** | The package name of an app (e.g. com.example.app). | 

### Other Parameters

Other parameters are passed through a pointer to a apiLaunchPackageRequest struct via the builder pattern


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


## LaunchVideo

> LaunchVideo(ctx, deviceId, videoId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.LaunchVideo(context.Background(), deviceId, videoId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.LaunchVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLaunchVideoRequest struct via the builder pattern


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


## MigrateDeviceToOrganization

> MigrateDeviceToOrganization(ctx, deviceId, organizationSlug).Accept(accept).MigrateDeviceToOrganizationRequest(migrateDeviceToOrganizationRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	organizationSlug := "organizationSlug_example" // string | The slug for the organization
	migrateDeviceToOrganizationRequest := *openapiclient.NewMigrateDeviceToOrganizationRequest() // MigrateDeviceToOrganizationRequest | Migrate device to organization request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.MigrateDeviceToOrganization(context.Background(), deviceId, organizationSlug).Accept(accept).MigrateDeviceToOrganizationRequest(migrateDeviceToOrganizationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.MigrateDeviceToOrganization``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**organizationSlug** | **string** | The slug for the organization | 

### Other Parameters

Other parameters are passed through a pointer to a apiMigrateDeviceToOrganizationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


 **migrateDeviceToOrganizationRequest** | [**MigrateDeviceToOrganizationRequest**](MigrateDeviceToOrganizationRequest.md) | Migrate device to organization request | 

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


## RebootDevice

> RebootDevice(ctx, deviceId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.RebootDevice(context.Background(), deviceId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.RebootDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRebootDeviceRequest struct via the builder pattern


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


## RemoveFileFromDevice

> RemoveFileFromDevice(ctx, deviceId, fileId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	fileId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a file.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.RemoveFileFromDevice(context.Background(), deviceId, fileId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.RemoveFileFromDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**fileId** | **string** | The ID of a file. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveFileFromDeviceRequest struct via the builder pattern


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


## RemoveReleaseChannelFromDevice

> RemoveReleaseChannelFromDevice(ctx, deviceId, releaseChannelId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	releaseChannelId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a release channel.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.RemoveReleaseChannelFromDevice(context.Background(), deviceId, releaseChannelId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.RemoveReleaseChannelFromDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**releaseChannelId** | **string** | The ID of a release channel. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveReleaseChannelFromDeviceRequest struct via the builder pattern


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


## RemoveVideoFromDevice

> RemoveVideoFromDevice(ctx, deviceId, videoId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	videoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a video.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.RemoveVideoFromDevice(context.Background(), deviceId, videoId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.RemoveVideoFromDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 
**videoId** | **string** | The ID of a video. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveVideoFromDeviceRequest struct via the builder pattern


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


## ShutDownDevice

> ShutDownDevice(ctx, deviceId).Accept(accept).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DevicesAPI.ShutDownDevice(context.Background(), deviceId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.ShutDownDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiShutDownDeviceRequest struct via the builder pattern


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


## UpdateDevice

> GetDevices200ResponseDataInner UpdateDevice(ctx, deviceId).Accept(accept).UpdateDeviceRequest(updateDeviceRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	updateDeviceRequest := *openapiclient.NewUpdateDeviceRequest() // UpdateDeviceRequest | The device fields to update. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DevicesAPI.UpdateDevice(context.Background(), deviceId).Accept(accept).UpdateDeviceRequest(updateDeviceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.UpdateDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDevice`: GetDevices200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `DevicesAPI.UpdateDevice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeviceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **updateDeviceRequest** | [**UpdateDeviceRequest**](UpdateDeviceRequest.md) | The device fields to update. | 

### Return type

[**GetDevices200ResponseDataInner**](GetDevices200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeviceCustomFields

> GetDevices200ResponseDataInner UpdateDeviceCustomFields(ctx, deviceId).Accept(accept).UpdateDeviceCustomFieldsRequest(updateDeviceCustomFieldsRequest).Execute()





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
	deviceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of a device.
	updateDeviceCustomFieldsRequest := *openapiclient.NewUpdateDeviceCustomFieldsRequest("Action_example", []openapiclient.UpdateDeviceCustomFieldsRequestCustomFieldsInner{*openapiclient.NewUpdateDeviceCustomFieldsRequestCustomFieldsInner("Name_example")}) // UpdateDeviceCustomFieldsRequest | Update custom fields on a device

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DevicesAPI.UpdateDeviceCustomFields(context.Background(), deviceId).Accept(accept).UpdateDeviceCustomFieldsRequest(updateDeviceCustomFieldsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DevicesAPI.UpdateDeviceCustomFields``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDeviceCustomFields`: GetDevices200ResponseDataInner
	fmt.Fprintf(os.Stdout, "Response from `DevicesAPI.UpdateDeviceCustomFields`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeviceCustomFieldsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **updateDeviceCustomFieldsRequest** | [**UpdateDeviceCustomFieldsRequest**](UpdateDeviceCustomFieldsRequest.md) | Update custom fields on a device | 

### Return type

[**GetDevices200ResponseDataInner**](GetDevices200ResponseDataInner.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

