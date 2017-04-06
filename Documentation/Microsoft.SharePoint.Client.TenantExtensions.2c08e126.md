# TenantExtensions.GetOneDriveSiteCollections Method  
Get OneDrive site collections by iterating through all user profiles.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static IList<SiteEntity> GetOneDriveSiteCollections(Tenant tenant)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  
### Return Value
Type: IList<SiteEntity>  
List of  objects containing site collection info.

## See also
- [OfficeDevPnP.Core.Entities.SiteEntity](OfficeDevPnP.Core.Entities.SiteEntity.md)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
