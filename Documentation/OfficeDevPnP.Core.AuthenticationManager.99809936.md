String, Icon# AuthenticationManager.GetWebLoginClientContext members
Returns a SharePoint on-premises / SharePoint Online ClientContext object. Requires claims based authentication with FedAuth cookie.  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetWebLoginClientContext(String, Icon)
```
### Parameters
#### siteUrl
Type: [System.String](System.String.md) 
#### 
#### (optional) icon
Type: [System.Drawing.Icon](System.Drawing.Icon.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)ClientContext to be used by CSOM code
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
