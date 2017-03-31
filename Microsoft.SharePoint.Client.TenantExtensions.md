# TenantExtensions
Class for deprecated tenant extension methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class TenantExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [CreateSiteCollection(Tenant, SiteEntity, Boolean, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.8f180b3b.md) | 
| [CreateSiteCollection(Tenant, String, String, String, String, Int32, Int32, Int32, Int32, Int32, UInt32, Boolean, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.5122ed46.md) | 
| [CheckIfSiteExists(Tenant, String, String)](Microsoft.SharePoint.Client.TenantExtensions.bd62d116.md) | Returns if a site collection is in a particular status. If the url contains a sub site then returns true is the sub site exists, false if not. Status is irrelevant for sub sites
| [IsSiteActive(Tenant, String)](Microsoft.SharePoint.Client.TenantExtensions.df897728.md) | Checks if a site collection is Active
| [SiteExists(Tenant, String)](Microsoft.SharePoint.Client.TenantExtensions.fa3c7d26.md) | Checks if a site collection exists, relies on tenant admin API. Sites that are recycled also return as existing sites
| [SubSiteExists(Tenant, String)](Microsoft.SharePoint.Client.TenantExtensions.488f63fb.md) | Checks if a sub site exists
| [DeleteSiteCollection(Tenant, String, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.32ab407c.md) | 
| [DeleteSiteCollectionFromRecycleBin(Tenant, String, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.802142c7.md) | 
| [GetSiteGuidByUrl(Tenant, String)](Microsoft.SharePoint.Client.TenantExtensions.6b408500.md) | Gets the ID of site collection with specified URL
| [GetSiteGuidByUrl(Tenant, Uri)](Microsoft.SharePoint.Client.TenantExtensions.64e4cb66.md) | Gets the ID of site collection with specified URL
| [GetWebTemplates(Tenant, UInt32, Int32)](Microsoft.SharePoint.Client.TenantExtensions.26f04e93.md) | Returns available webtemplates/site definitions
| [SetSiteProperties(Tenant, String, String, Nullable<Boolean>, Nullable<SharingCapabilities>, Nullable<Int64>, Nullable<Int64>, Nullable<Double>, Nullable<Double>, Nullable<Boolean>, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.41bc0a90.md) | 
| [SetSiteLockState(Tenant, String, SiteLockState, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.ef999b08.md) | 
| [AddAdministrators(Tenant, IEnumerable<UserEntity>, Uri, Boolean)](Microsoft.SharePoint.Client.TenantExtensions.23dcea4d.md) | 
| [GetSiteCollections(Tenant, Int32, Int32, Boolean, Boolean)](Microsoft.SharePoint.Client.TenantExtensions.9ce74f2.md) | Returns all site collections in the current Tenant based on a startIndex. IncludeDetail adds additional properties to the SPSite object.
| [GetOneDriveSiteCollections(Tenant)](Microsoft.SharePoint.Client.TenantExtensions.2c08e126.md) | Get OneDrive site collections by iterating through all user profiles.
| [GetUserProfileServiceClient(Tenant)](Microsoft.SharePoint.Client.TenantExtensions.4a97c99c.md) | Gets the UserProfileService proxy to enable calls to the UPA web service.
| [DeployApplicationPackageToAppCatalog(Tenant, String, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.TenantExtensions.8b800134.md) | Adds a package to the tenants app catalog and by default deploys it if the package is a client side package (sppkg)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
