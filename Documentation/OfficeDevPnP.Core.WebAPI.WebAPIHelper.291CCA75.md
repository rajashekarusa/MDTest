HttpControllerContext# WebAPIHelper.GetClientContext members
Creates a ClientContext token for the incoming WebAPI request. This is done by 
            - looking up the servicesToken
            - extracting the cacheKey 
            - get the AccessToken from cache. If the AccessToken is expired a new one is requested using the refresh token
            - creation of a ClientContext object based on the AccessToken  

**Namespace:** [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  GetClientContext(HttpControllerContext)
```
### Parameters
#### httpControllerContext
Type: [System.Web.Http.Controllers.HttpControllerContext](System.Web.Http.Controllers.HttpControllerContext.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)A valid ClientContext object
## See also
- [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)
