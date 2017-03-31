# AuthenticationManager.GetWebLoginClientContext Method  
Returns a SharePoint on-premises / SharePoint Online ClientContext object. Requires claims based authentication with FedAuth cookie.  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetWebLoginClientContext(String siteUrl,Icon icon)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) icon*  
&emsp;&emsp;Type: [System.Drawing.Icon](System.Drawing.Icon.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)  
ClientContext to be used by CSOM code

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
