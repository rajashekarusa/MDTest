# TenantExtensions.SetSiteLockState Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetSiteLockState(Tenant tenant, String siteFullUrl, SiteLockState lockState, Boolean wait, Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
#### tenant  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  

#### siteFullUrl  
&emsp;&emsp;Type: System.String  

#### lockState  
&emsp;&emsp;Type: [OfficeDevPnP.Core.SiteLockState](OfficeDevPnP.Core.SiteLockState.md)  

#### (optional) wait  
&emsp;&emsp;Type: System.Boolean  

#### (optional) timeoutFunction  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage, System.Boolean>  

### Return Value
Type: void  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
