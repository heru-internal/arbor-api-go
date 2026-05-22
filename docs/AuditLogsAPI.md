# \AuditLogsAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAuditLogs**](AuditLogsAPI.md#GetAuditLogs) | **Get** /audit-logs | 



## GetAuditLogs

> GetAuditLogs200Response GetAuditLogs(ctx).Accept(accept).PerPage(perPage).Page(page).Search(search).StartTime(startTime).EndTime(endTime).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/heru-inc/arbor-api-go"
)

func main() {
	accept := "accept_example" // string |  (default to "application/json")
	perPage := int32(56) // int32 | The number of items to return per page. (optional) (default to 10)
	page := int32(56) // int32 | The page number to return. (optional) (default to 1)
	search := "alpha" // string | Search term to filter results. (optional)
	startTime := time.Now() // Time | Filter to show only entries created at or after this timestamp (ISO 8601 Zulu format with millisecond precision). (optional)
	endTime := time.Now() // Time | Filter to show only entries created at or before this timestamp (ISO 8601 Zulu format with millisecond precision). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditLogsAPI.GetAuditLogs(context.Background()).Accept(accept).PerPage(perPage).Page(page).Search(search).StartTime(startTime).EndTime(endTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditLogsAPI.GetAuditLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAuditLogs`: GetAuditLogs200Response
	fmt.Fprintf(os.Stdout, "Response from `AuditLogsAPI.GetAuditLogs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAuditLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **perPage** | **int32** | The number of items to return per page. | [default to 10]
 **page** | **int32** | The page number to return. | [default to 1]
 **search** | **string** | Search term to filter results. | 
 **startTime** | **Time** | Filter to show only entries created at or after this timestamp (ISO 8601 Zulu format with millisecond precision). | 
 **endTime** | **Time** | Filter to show only entries created at or before this timestamp (ISO 8601 Zulu format with millisecond precision). | 

### Return type

[**GetAuditLogs200Response**](GetAuditLogs200Response.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

