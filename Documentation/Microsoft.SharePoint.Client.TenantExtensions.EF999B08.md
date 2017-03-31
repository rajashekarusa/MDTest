Tenant, String, SiteLockState, Boolean, Func<TenantOperationMessage, Boolean># TenantExtensions.SetSiteLockState members
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetSiteLockState(Tenant, String, SiteLockState, Boolean, Func<TenantOperationMessage, Boolean>)
```
### Parameters
#### tenant
Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
#### 
#### siteFullUrl
Type: [System.String](System.String.md) 
#### 
#### lockState
Type: [OfficeDevPnP.Core.SiteLockState](OfficeDevPnP.Core.SiteLockState.md) 
#### 
#### (optional) wait
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) timeoutFunction
Type: [System.Func`2<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>](System.Func`2<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>.md) 
#### 
### Return Value
Type: [System.Void](System.Void.md)## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
