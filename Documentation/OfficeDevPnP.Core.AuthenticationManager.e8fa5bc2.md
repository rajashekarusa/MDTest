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
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;Site for which the ClientContext object will be instantiated  
  
*tenantUser*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;User to be used to instantiate the ClientContext object  
  
*tenantUserPassword*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;Password of the user used to instantiate the ClientContext object  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext]  
ClientContext to be used by CSOM code

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
