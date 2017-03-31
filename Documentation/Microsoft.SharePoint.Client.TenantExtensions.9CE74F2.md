Tenant, Int32, Int32, Boolean, Boolean# TenantExtensions.GetSiteCollections members
Returns all site collections in the current Tenant based on a startIndex. IncludeDetail adds additional properties to the SPSite object.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.ilist`1<officedevpnp.core.entities.siteentity> GetSiteCollections(Tenant, Int32, Int32, Boolean, Boolean)
```
### Parameters
#### tenant
Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
#### 
#### (optional) startIndex
Type: [System.Int32](System.Int32.md) 
#### 
#### (optional) endIndex
Type: [System.Int32](System.Int32.md) 
#### 
#### (optional) includeDetail
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) includeOD4BSites
Type: [System.Boolean](System.Boolean.md) 
#### 
### Return Value
Type: [System.Collections.Generic.IList`1<OfficeDevPnP.Core.Entities.SiteEntity>](System.Collections.Generic.IList`1<OfficeDevPnP.Core.Entities.SiteEntity>.md)An IList of SiteEntity objects
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
