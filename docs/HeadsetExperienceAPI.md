# \HeadsetExperienceAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ConfigureDeviceArborXrHomeHeadsetExperience**](HeadsetExperienceAPI.md#ConfigureDeviceArborXrHomeHeadsetExperience) | **Post** /devices/{deviceId}/headset-experience/arborxr-home | 
[**ConfigureDeviceArborXrKioskHeadsetExperience**](HeadsetExperienceAPI.md#ConfigureDeviceArborXrKioskHeadsetExperience) | **Post** /devices/{deviceId}/headset-experience/arborxr-kiosk | 
[**ConfigureDeviceDefaultHomeHeadsetExperience**](HeadsetExperienceAPI.md#ConfigureDeviceDefaultHomeHeadsetExperience) | **Post** /devices/{deviceId}/headset-experience/default-home | 
[**ConfigureDeviceInHouseLauncherHeadsetExperience**](HeadsetExperienceAPI.md#ConfigureDeviceInHouseLauncherHeadsetExperience) | **Post** /devices/{deviceId}/headset-experience/in-house-launcher | 
[**ConfigureGroupArborXrHomeHeadsetExperience**](HeadsetExperienceAPI.md#ConfigureGroupArborXrHomeHeadsetExperience) | **Post** /groups/{groupId}/headset-experience/arborxr-home | 
[**ConfigureGroupArborXrKioskHeadsetExperience**](HeadsetExperienceAPI.md#ConfigureGroupArborXrKioskHeadsetExperience) | **Post** /groups/{groupId}/headset-experience/arborxr-kiosk | 
[**ConfigureGroupDefaultHomeHeadsetExperience**](HeadsetExperienceAPI.md#ConfigureGroupDefaultHomeHeadsetExperience) | **Post** /groups/{groupId}/headset-experience/default-home | 
[**ConfigureGroupInHouseLauncherHeadsetExperience**](HeadsetExperienceAPI.md#ConfigureGroupInHouseLauncherHeadsetExperience) | **Post** /groups/{groupId}/headset-experience/in-house-launcher | 
[**GetDeviceHeadsetExperience**](HeadsetExperienceAPI.md#GetDeviceHeadsetExperience) | **Get** /devices/{deviceId}/headset-experience | 
[**GetGroupHeadsetExperience**](HeadsetExperienceAPI.md#GetGroupHeadsetExperience) | **Get** /groups/{groupId}/headset-experience | 



## ConfigureDeviceArborXrHomeHeadsetExperience

> ConfigureDeviceArborXrHomeHeadsetExperience(ctx, deviceId).Accept(accept).ConfigureGroupArborXrHomeHeadsetExperienceRequest(configureGroupArborXrHomeHeadsetExperienceRequest).Execute()





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
	configureGroupArborXrHomeHeadsetExperienceRequest := *openapiclient.NewConfigureGroupArborXrHomeHeadsetExperienceRequest([]openapiclient.ConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner{*openapiclient.NewConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner("Id_example", "Type_example")}, "en", "My Stuff", "123e4567-e89b-12d3-a456-426614174000", false, []string{"Shortcuts_example"}, "1234", []string{"CategorizationTags_example"}, *openapiclient.NewConfigureGroupArborXrHomeHeadsetExperienceRequestBackground("Type_example"), "123e4567-e89b-12d3-a456-426614174000") // ConfigureGroupArborXrHomeHeadsetExperienceRequest | Request body for configuring the ArborXR Home headset experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HeadsetExperienceAPI.ConfigureDeviceArborXrHomeHeadsetExperience(context.Background(), deviceId).Accept(accept).ConfigureGroupArborXrHomeHeadsetExperienceRequest(configureGroupArborXrHomeHeadsetExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.ConfigureDeviceArborXrHomeHeadsetExperience``: %v\n", err)
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

Other parameters are passed through a pointer to a apiConfigureDeviceArborXrHomeHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupArborXrHomeHeadsetExperienceRequest** | [**ConfigureGroupArborXrHomeHeadsetExperienceRequest**](ConfigureGroupArborXrHomeHeadsetExperienceRequest.md) | Request body for configuring the ArborXR Home headset experience. | 

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


## ConfigureDeviceArborXrKioskHeadsetExperience

> ConfigureDeviceArborXrKioskHeadsetExperience(ctx, deviceId).Accept(accept).ConfigureGroupArborXrKioskHeadsetExperienceRequest(configureGroupArborXrKioskHeadsetExperienceRequest).Execute()





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
	configureGroupArborXrKioskHeadsetExperienceRequest := *openapiclient.NewConfigureGroupArborXrKioskHeadsetExperienceRequest(*openapiclient.NewConfigureGroupArborXrKioskHeadsetExperienceRequestKioskContent("Type_example", "Id_example"), true) // ConfigureGroupArborXrKioskHeadsetExperienceRequest | Request body for configuring the ArborXR Kiosk headset experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HeadsetExperienceAPI.ConfigureDeviceArborXrKioskHeadsetExperience(context.Background(), deviceId).Accept(accept).ConfigureGroupArborXrKioskHeadsetExperienceRequest(configureGroupArborXrKioskHeadsetExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.ConfigureDeviceArborXrKioskHeadsetExperience``: %v\n", err)
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

Other parameters are passed through a pointer to a apiConfigureDeviceArborXrKioskHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupArborXrKioskHeadsetExperienceRequest** | [**ConfigureGroupArborXrKioskHeadsetExperienceRequest**](ConfigureGroupArborXrKioskHeadsetExperienceRequest.md) | Request body for configuring the ArborXR Kiosk headset experience. | 

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


## ConfigureDeviceDefaultHomeHeadsetExperience

> ConfigureDeviceDefaultHomeHeadsetExperience(ctx, deviceId).Accept(accept).ConfigureGroupDefaultHomeHeadsetExperienceRequest(configureGroupDefaultHomeHeadsetExperienceRequest).Execute()





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
	configureGroupDefaultHomeHeadsetExperienceRequest := *openapiclient.NewConfigureGroupDefaultHomeHeadsetExperienceRequest() // ConfigureGroupDefaultHomeHeadsetExperienceRequest | Request body for configuring the Default Home headset experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HeadsetExperienceAPI.ConfigureDeviceDefaultHomeHeadsetExperience(context.Background(), deviceId).Accept(accept).ConfigureGroupDefaultHomeHeadsetExperienceRequest(configureGroupDefaultHomeHeadsetExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.ConfigureDeviceDefaultHomeHeadsetExperience``: %v\n", err)
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

Other parameters are passed through a pointer to a apiConfigureDeviceDefaultHomeHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupDefaultHomeHeadsetExperienceRequest** | [**ConfigureGroupDefaultHomeHeadsetExperienceRequest**](ConfigureGroupDefaultHomeHeadsetExperienceRequest.md) | Request body for configuring the Default Home headset experience. | 

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


## ConfigureDeviceInHouseLauncherHeadsetExperience

> ConfigureDeviceInHouseLauncherHeadsetExperience(ctx, deviceId).Accept(accept).ConfigureGroupInHouseLauncherHeadsetExperienceRequest(configureGroupInHouseLauncherHeadsetExperienceRequest).Execute()





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
	configureGroupInHouseLauncherHeadsetExperienceRequest := *openapiclient.NewConfigureGroupInHouseLauncherHeadsetExperienceRequest(*openapiclient.NewConfigureGroupInHouseLauncherHeadsetExperienceRequestLauncherContent("Type_example", "Id_example"), []openapiclient.ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner{*openapiclient.NewConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner("Id_example", "Type_example")}, true) // ConfigureGroupInHouseLauncherHeadsetExperienceRequest | Request body for configuring the In-House Launcher headset experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HeadsetExperienceAPI.ConfigureDeviceInHouseLauncherHeadsetExperience(context.Background(), deviceId).Accept(accept).ConfigureGroupInHouseLauncherHeadsetExperienceRequest(configureGroupInHouseLauncherHeadsetExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.ConfigureDeviceInHouseLauncherHeadsetExperience``: %v\n", err)
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

Other parameters are passed through a pointer to a apiConfigureDeviceInHouseLauncherHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupInHouseLauncherHeadsetExperienceRequest** | [**ConfigureGroupInHouseLauncherHeadsetExperienceRequest**](ConfigureGroupInHouseLauncherHeadsetExperienceRequest.md) | Request body for configuring the In-House Launcher headset experience. | 

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


## ConfigureGroupArborXrHomeHeadsetExperience

> ConfigureGroupArborXrHomeHeadsetExperience(ctx, groupId).Accept(accept).ConfigureGroupArborXrHomeHeadsetExperienceRequest(configureGroupArborXrHomeHeadsetExperienceRequest).Execute()





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
	configureGroupArborXrHomeHeadsetExperienceRequest := *openapiclient.NewConfigureGroupArborXrHomeHeadsetExperienceRequest([]openapiclient.ConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner{*openapiclient.NewConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner("Id_example", "Type_example")}, "en", "My Stuff", "123e4567-e89b-12d3-a456-426614174000", false, []string{"Shortcuts_example"}, "1234", []string{"CategorizationTags_example"}, *openapiclient.NewConfigureGroupArborXrHomeHeadsetExperienceRequestBackground("Type_example"), "123e4567-e89b-12d3-a456-426614174000") // ConfigureGroupArborXrHomeHeadsetExperienceRequest | Request body for configuring the ArborXR Home headset experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HeadsetExperienceAPI.ConfigureGroupArborXrHomeHeadsetExperience(context.Background(), groupId).Accept(accept).ConfigureGroupArborXrHomeHeadsetExperienceRequest(configureGroupArborXrHomeHeadsetExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.ConfigureGroupArborXrHomeHeadsetExperience``: %v\n", err)
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

Other parameters are passed through a pointer to a apiConfigureGroupArborXrHomeHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupArborXrHomeHeadsetExperienceRequest** | [**ConfigureGroupArborXrHomeHeadsetExperienceRequest**](ConfigureGroupArborXrHomeHeadsetExperienceRequest.md) | Request body for configuring the ArborXR Home headset experience. | 

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


## ConfigureGroupArborXrKioskHeadsetExperience

> ConfigureGroupArborXrKioskHeadsetExperience(ctx, groupId).Accept(accept).ConfigureGroupArborXrKioskHeadsetExperienceRequest(configureGroupArborXrKioskHeadsetExperienceRequest).Execute()





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
	configureGroupArborXrKioskHeadsetExperienceRequest := *openapiclient.NewConfigureGroupArborXrKioskHeadsetExperienceRequest(*openapiclient.NewConfigureGroupArborXrKioskHeadsetExperienceRequestKioskContent("Type_example", "Id_example"), true) // ConfigureGroupArborXrKioskHeadsetExperienceRequest | Request body for configuring the ArborXR Kiosk headset experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HeadsetExperienceAPI.ConfigureGroupArborXrKioskHeadsetExperience(context.Background(), groupId).Accept(accept).ConfigureGroupArborXrKioskHeadsetExperienceRequest(configureGroupArborXrKioskHeadsetExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.ConfigureGroupArborXrKioskHeadsetExperience``: %v\n", err)
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

Other parameters are passed through a pointer to a apiConfigureGroupArborXrKioskHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupArborXrKioskHeadsetExperienceRequest** | [**ConfigureGroupArborXrKioskHeadsetExperienceRequest**](ConfigureGroupArborXrKioskHeadsetExperienceRequest.md) | Request body for configuring the ArborXR Kiosk headset experience. | 

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


## ConfigureGroupDefaultHomeHeadsetExperience

> ConfigureGroupDefaultHomeHeadsetExperience(ctx, groupId).Accept(accept).ConfigureGroupDefaultHomeHeadsetExperienceRequest(configureGroupDefaultHomeHeadsetExperienceRequest).Execute()





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
	configureGroupDefaultHomeHeadsetExperienceRequest := *openapiclient.NewConfigureGroupDefaultHomeHeadsetExperienceRequest() // ConfigureGroupDefaultHomeHeadsetExperienceRequest | Request body for configuring the Default Home headset experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HeadsetExperienceAPI.ConfigureGroupDefaultHomeHeadsetExperience(context.Background(), groupId).Accept(accept).ConfigureGroupDefaultHomeHeadsetExperienceRequest(configureGroupDefaultHomeHeadsetExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.ConfigureGroupDefaultHomeHeadsetExperience``: %v\n", err)
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

Other parameters are passed through a pointer to a apiConfigureGroupDefaultHomeHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupDefaultHomeHeadsetExperienceRequest** | [**ConfigureGroupDefaultHomeHeadsetExperienceRequest**](ConfigureGroupDefaultHomeHeadsetExperienceRequest.md) | Request body for configuring the Default Home headset experience. | 

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


## ConfigureGroupInHouseLauncherHeadsetExperience

> ConfigureGroupInHouseLauncherHeadsetExperience(ctx, groupId).Accept(accept).ConfigureGroupInHouseLauncherHeadsetExperienceRequest(configureGroupInHouseLauncherHeadsetExperienceRequest).Execute()





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
	configureGroupInHouseLauncherHeadsetExperienceRequest := *openapiclient.NewConfigureGroupInHouseLauncherHeadsetExperienceRequest(*openapiclient.NewConfigureGroupInHouseLauncherHeadsetExperienceRequestLauncherContent("Type_example", "Id_example"), []openapiclient.ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner{*openapiclient.NewConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner("Id_example", "Type_example")}, true) // ConfigureGroupInHouseLauncherHeadsetExperienceRequest | Request body for configuring the In-House Launcher headset experience. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HeadsetExperienceAPI.ConfigureGroupInHouseLauncherHeadsetExperience(context.Background(), groupId).Accept(accept).ConfigureGroupInHouseLauncherHeadsetExperienceRequest(configureGroupInHouseLauncherHeadsetExperienceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.ConfigureGroupInHouseLauncherHeadsetExperience``: %v\n", err)
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

Other parameters are passed through a pointer to a apiConfigureGroupInHouseLauncherHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]

 **configureGroupInHouseLauncherHeadsetExperienceRequest** | [**ConfigureGroupInHouseLauncherHeadsetExperienceRequest**](ConfigureGroupInHouseLauncherHeadsetExperienceRequest.md) | Request body for configuring the In-House Launcher headset experience. | 

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


## GetDeviceHeadsetExperience

> GetGroupHeadsetExperience200Response GetDeviceHeadsetExperience(ctx, deviceId).Accept(accept).Execute()





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
	resp, r, err := apiClient.HeadsetExperienceAPI.GetDeviceHeadsetExperience(context.Background(), deviceId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.GetDeviceHeadsetExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceHeadsetExperience`: GetGroupHeadsetExperience200Response
	fmt.Fprintf(os.Stdout, "Response from `HeadsetExperienceAPI.GetDeviceHeadsetExperience`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceId** | **string** | The ID of a device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetGroupHeadsetExperience200Response**](GetGroupHeadsetExperience200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGroupHeadsetExperience

> GetGroupHeadsetExperience200Response GetGroupHeadsetExperience(ctx, groupId).Accept(accept).Execute()





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
	resp, r, err := apiClient.HeadsetExperienceAPI.GetGroupHeadsetExperience(context.Background(), groupId).Accept(accept).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HeadsetExperienceAPI.GetGroupHeadsetExperience``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGroupHeadsetExperience`: GetGroupHeadsetExperience200Response
	fmt.Fprintf(os.Stdout, "Response from `HeadsetExperienceAPI.GetGroupHeadsetExperience`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**groupId** | **string** | The ID of a group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGroupHeadsetExperienceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]


### Return type

[**GetGroupHeadsetExperience200Response**](GetGroupHeadsetExperience200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

