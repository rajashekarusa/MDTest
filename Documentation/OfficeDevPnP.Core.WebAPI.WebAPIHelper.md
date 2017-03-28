# WebAPIHelper
This class provides helper methods that can be used to protect WebAPI services and to provide a 
            way to reinstantiate a contextobject in the service call.
**Namespace:** [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class WebAPIHelper
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [HasCacheEntry(Web.Http.Controllers.HttpControllerContext)](WebAPIHelperHasCacheEntryWeb.Http.Controllers.HttpControllerContext.md) | Checks if this request has a servicesToken cookie. To be used from inside the WebAPI.
| [GetCacheKeyValue(Web.Http.Controllers.HttpControllerContext)](WebAPIHelperGetCacheKeyValueWeb.Http.Controllers.HttpControllerContext.md) | 
| [GetClientContext(Web.Http.Controllers.HttpControllerContext)](WebAPIHelperGetClientContextWeb.Http.Controllers.HttpControllerContext.md) | Creates a ClientContext token for the incoming WebAPI request. This is done by - looking up the servicesToken - extracting the cacheKey - get the AccessToken from cache. If the AccessToken is expired a new one is requested using the refresh token - creation of a ClientContext object based on the AccessToken
| [AddToCache(WebAPIContext)](WebAPIHelperAddToCacheWebAPIContext.md) | Uses the information regarding the requesting app to obtain an access token and caches that using the cachekey. This method is called from the Register WebAPI service api.
| [RegisterWebAPIService(Web.UI.Page, String, Uri)](WebAPIHelperRegisterWebAPIServiceWeb.UI.PageStringUri.md) | This method needs to be called from a code behind of the SharePoint app startup page (default.aspx). It registers the calling SharePoint app by calling a specific "Register" api in your WebAPI service. Note: Given that method is async you'll need to add the Async="true" page directive to the page that uses this method.
| [GetQueryString(Collections.Specialized.NameValueCollection, String, Func2<String,T>, T)](WebAPIHelperGetQueryStringCollections.Specialized.NameValueCollectionStringFunc2<String,T>T.md) | 
| [AsString(Collections.Specialized.NameValueCollection, String, String)](WebAPIHelperAsStringCollections.Specialized.NameValueCollectionStringString.md) | 
| [GetClaimValue(SharePointPnP.IdentityModel.Extensions.S2S.Tokens.JsonWebSecurityToken, String)](WebAPIHelperGetClaimValueSharePointPnP.IdentityModel.Extensions.S2S.Tokens.JsonWebSecurityTokenString.md) | 
| [RemoveSpecialCharacters(String)](WebAPIHelperRemoveSpecialCharactersString.md) | 
## See also
- [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)
