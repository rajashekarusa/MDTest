# TenantExtensions.SetSiteLockState Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static System.Void SetSiteLockState(Tenant tenant, String siteFullUrl, SiteLockState lockState, Boolean wait, Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  
&emsp;&emsp;  
  
*siteFullUrl*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*lockState*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.SiteLockState](OfficeDevPnP.Core.SiteLockState.md)  
&emsp;&emsp;  
  
*(optional) wait*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*(optional) timeoutFunction*  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>  
&emsp;&emsp;  
  
### Return Value
Type: System.Void  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
