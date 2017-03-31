# TenantExtensions.GetOneDriveSiteCollections Method  
Get OneDrive site collections by iterating through all user profiles.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.ilist`1<officedevpnp.core.entities.siteentity> GetOneDriveSiteCollections(Tenant tenant)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.IList`1<OfficeDevPnP.Core.Entities.SiteEntity>](System.Collections.Generic.IList`1<OfficeDevPnP.Core.Entities.SiteEntity>.md)  
List of  objects containing site collection info.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
