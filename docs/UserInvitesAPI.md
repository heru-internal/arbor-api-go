# \UserInvitesAPI

All URIs are relative to *https://api.xrdm.app/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateUserInvite**](UserInvitesAPI.md#CreateUserInvite) | **Post** /user-invites | 



## CreateUserInvite

> CreateUserInvite(ctx).Accept(accept).CreateUserInviteRequest(createUserInviteRequest).Execute()





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
	createUserInviteRequest := *openapiclient.NewCreateUserInviteRequest("w.white@example.com", "123e4567-e89b-12d3-a456-426614174000") // CreateUserInviteRequest | The fields required to invite a user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UserInvitesAPI.CreateUserInvite(context.Background()).Accept(accept).CreateUserInviteRequest(createUserInviteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserInvitesAPI.CreateUserInvite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateUserInviteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accept** | **string** |  | [default to &quot;application/json&quot;]
 **createUserInviteRequest** | [**CreateUserInviteRequest**](CreateUserInviteRequest.md) | The fields required to invite a user. | 

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

