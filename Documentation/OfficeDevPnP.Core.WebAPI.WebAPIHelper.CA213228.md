Page, String, Uri# WebAPIHelper.RegisterWebAPIService members
This method needs to be called from a code behind of the SharePoint app startup page (default.aspx). It registers the calling
            SharePoint app by calling a specific "Register" api in your WebAPI service.
            
            Note:
            Given that method is async you'll need to add the  Async="true" page directive to the page that uses this method.  

**Namespace:** [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void RegisterWebAPIService(Page, String, Uri)
```
### Parameters
#### page
Type: [System.Web.UI.Page](System.Web.UI.Page.md) 
#### 
#### apiRequest
Type: [System.String](System.String.md) 
#### 
#### (optional) serviceEndPoint
Type: [System.Uri](System.Uri.md) 
#### 
### Return Value
Type: [System.Void](System.Void.md)## See also
- [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)
