# \StatusesAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetStatuses**](StatusesAPI.md#GetStatuses) | **Get** /statuses | 



## GetStatuses

> GetStatuses200Response GetStatuses(ctx).Accept(accept).PerPage(perPage).Page(page).DeviceIds(deviceIds).GroupIds(groupIds).ContentIds(contentIds).ContentTypes(contentTypes).Statuses(statuses).Execute()





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
	deviceIds := []string{"Inner_example"} // []string | Filter results to one or more devices. Provide as a query-parameter array, e.g. `?deviceIds[]=value1&deviceIds[]=value2`. (optional)
	groupIds := []string{"Inner_example"} // []string | Filter results to devices in one or more groups. Provide as a query-parameter array, e.g. `?groupIds[]=value1&groupIds[]=value2`. (optional)
	contentIds := []string{"Inner_example"} // []string | Filter results to one or more pieces of content (app, file, video, etc.). Provide as a query-parameter array, e.g. `?contentIds[]=value1&contentIds[]=value2`. (optional)
	contentTypes := []string{"ContentTypes_example"} // []string | Filter results to one or more content types. Provide as a query-parameter array, e.g. `?contentTypes[]=app&contentTypes[]=file`. (optional)
	statuses := []string{"Statuses_example"} // []string | Filter results to one or more projected statuses. Provide as a query-parameter array, e.g. `?statuses[]=failed-install&statuses[]=failed-update`. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StatusesAPI.GetStatuses(context.Background()).Accept(accept).PerPage(perPage).Page(page).DeviceIds(deviceIds).GroupIds(groupIds).ContentIds(contentIds).ContentTypes(contentTypes).Statuses(statuses).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StatusesAPI.GetStatuses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStatuses`: GetStatuses200Response
	fmt.Fprintf(os.Stdout, "Response from `StatusesAPI.GetStatuses`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetStatusesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]
 **deviceIds** | **[]string** | Filter results to one or more devices. Provide as a query-parameter array, e.g. &#x60;?deviceIds[]&#x3D;value1&amp;deviceIds[]&#x3D;value2&#x60;. | 
 **groupIds** | **[]string** | Filter results to devices in one or more groups. Provide as a query-parameter array, e.g. &#x60;?groupIds[]&#x3D;value1&amp;groupIds[]&#x3D;value2&#x60;. | 
 **contentIds** | **[]string** | Filter results to one or more pieces of content (app, file, video, etc.). Provide as a query-parameter array, e.g. &#x60;?contentIds[]&#x3D;value1&amp;contentIds[]&#x3D;value2&#x60;. | 
 **contentTypes** | **[]string** | Filter results to one or more content types. Provide as a query-parameter array, e.g. &#x60;?contentTypes[]&#x3D;app&amp;contentTypes[]&#x3D;file&#x60;. | 
 **statuses** | **[]string** | Filter results to one or more projected statuses. Provide as a query-parameter array, e.g. &#x60;?statuses[]&#x3D;failed-install&amp;statuses[]&#x3D;failed-update&#x60;. | 

### Return type

[**GetStatuses200Response**](GetStatuses200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

