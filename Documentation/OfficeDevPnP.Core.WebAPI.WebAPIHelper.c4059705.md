# WebAPIHelper.HasCacheEntry Method  
Checks if this request has a servicesToken cookie. To be used from inside the WebAPI.  

**Namespace:** [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean HasCacheEntry(HttpControllerContext httpControllerContext)
```
### Parameters
*httpControllerContext*  
&emsp;&emsp;Type: [System.Web.Http.Controllers.HttpControllerContext](System.Web.Http.Controllers.HttpControllerContext.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md)  
True if cookie is available and not empty, false otherwise

## See also
- [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)
