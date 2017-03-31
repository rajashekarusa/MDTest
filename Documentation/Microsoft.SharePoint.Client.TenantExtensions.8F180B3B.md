Tenant, SiteEntity, Boolean, Boolean, Func<TenantOperationMessage, Boolean># TenantExtensions.CreateSiteCollection members
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static guid CreateSiteCollection(Tenant, SiteEntity, Boolean, Boolean, Func<TenantOperationMessage, Boolean>)
```
### Parameters
#### tenant
Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
#### 
#### properties
Type: [OfficeDevPnP.Core.Entities.SiteEntity](OfficeDevPnP.Core.Entities.SiteEntity.md) 
#### 
#### (optional) removeFromRecycleBin
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) wait
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) timeoutFunction
Type: [System.Func`2<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>](System.Func`2<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>.md) 
#### 
### Return Value
Type: [System.Guid](System.Guid.md)## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
