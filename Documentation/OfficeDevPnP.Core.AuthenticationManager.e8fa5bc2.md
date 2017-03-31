# AuthenticationManager.GetSharePointOnlineAuthenticatedContextTenant Method  
Returns a SharePointOnline ClientContext object  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetSharePointOnlineAuthenticatedContextTenant(String siteUrl,String tenantUser,String tenantUserPassword)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*tenantUser*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*tenantUserPassword*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)  
ClientContext to be used by CSOM code

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
