# TenantExtensions.GetSiteCollections Method  
Returns all site collections in the current Tenant based on a startIndex. IncludeDetail adds additional properties to the SPSite object.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.ilist`1<officedevpnp.core.entities.siteentity> GetSiteCollections(Tenant tenant,Int32 startIndex,Int32 endIndex,Boolean includeDetail,Boolean includeOD4BSites)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
&emsp;&emsp;  
  
*(optional) startIndex*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) endIndex*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) includeDetail*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) includeOD4BSites*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.IList`1<OfficeDevPnP.Core.Entities.SiteEntity>](System.Collections.Generic.IList`1<OfficeDevPnP.Core.Entities.SiteEntity>.md)  
An IList of SiteEntity objects

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
