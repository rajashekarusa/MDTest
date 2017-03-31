# WebAPIHelper.RegisterWebAPIService Method  
This method needs to be called from a code behind of the SharePoint app startup page (default.aspx). It registers the calling
            SharePoint app by calling a specific "Register" api in your WebAPI service.
            
            Note:
            Given that method is async you'll need to add the  Async="true" page directive to the page that uses this method.  

**Namespace:** [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void RegisterWebAPIService(Page page,String apiRequest,Uri serviceEndPoint)
```
### Parameters
*page*  
&emsp;&emsp;Type: [System.Web.UI.Page](System.Web.UI.Page.md) 
&emsp;&emsp;  
  
*apiRequest*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) serviceEndPoint*  
&emsp;&emsp;Type: [System.Uri](System.Uri.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md  
)
## See also
- [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)
