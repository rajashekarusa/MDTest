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
| [CreateSiteCollection(Tenant, SiteEntity, Boolean, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.8F180B3B.md) | 
| [CreateSiteCollection(Tenant, String, String, String, String, Int32, Int32, Int32, Int32, Int32, UInt32, Boolean, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.5122ED46.md) | 
| [CheckIfSiteExists(Tenant, String, String)](Microsoft.SharePoint.Client.TenantExtensions.BD62D116.md) | Returns if a site collection is in a particular status. If the url contains a sub site then returns true is the sub site exists, false if not. Status is irrelevant for sub sites
| [IsSiteActive(Tenant, String)](Microsoft.SharePoint.Client.TenantExtensions.DF897728.md) | Checks if a site collection is Active
| [SiteExists(Tenant, String)](Microsoft.SharePoint.Client.TenantExtensions.FA3C7D26.md) | Checks if a site collection exists, relies on tenant admin API. Sites that are recycled also return as existing sites
| [SubSiteExists(Tenant, String)](Microsoft.SharePoint.Client.TenantExtensions.488F63FB.md) | Checks if a sub site exists
| [DeleteSiteCollection(Tenant, String, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.32AB407C.md) | 
| [DeleteSiteCollectionFromRecycleBin(Tenant, String, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.802142C7.md) | 
| [GetSiteGuidByUrl(Tenant, String)](Microsoft.SharePoint.Client.TenantExtensions.6B408500.md) | Gets the ID of site collection with specified URL
| [GetSiteGuidByUrl(Tenant, Uri)](Microsoft.SharePoint.Client.TenantExtensions.64E4CB66.md) | Gets the ID of site collection with specified URL
| [GetWebTemplates(Tenant, UInt32, Int32)](Microsoft.SharePoint.Client.TenantExtensions.26F04E93.md) | Returns available webtemplates/site definitions
| [SetSiteProperties(Tenant, String, String, Nullable<Boolean>, Nullable<SharingCapabilities>, Nullable<Int64>, Nullable<Int64>, Nullable<Double>, Nullable<Double>, Nullable<Boolean>, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.41BC0A90.md) | 
| [SetSiteLockState(Tenant, String, SiteLockState, Boolean, Func<TenantOperationMessage, Boolean>)](Microsoft.SharePoint.Client.TenantExtensions.EF999B08.md) | 
| [AddAdministrators(Tenant, IEnumerable<UserEntity>, Uri, Boolean)](Microsoft.SharePoint.Client.TenantExtensions.23DCEA4D.md) | 
| [GetSiteCollections(Tenant, Int32, Int32, Boolean, Boolean)](Microsoft.SharePoint.Client.TenantExtensions.9CE74F2.md) | Returns all site collections in the current Tenant based on a startIndex. IncludeDetail adds additional properties to the SPSite object.
| [GetOneDriveSiteCollections(Tenant)](Microsoft.SharePoint.Client.TenantExtensions.2C08E126.md) | Get OneDrive site collections by iterating through all user profiles.
| [GetUserProfileServiceClient(Tenant)](Microsoft.SharePoint.Client.TenantExtensions.4A97C99C.md) | Gets the UserProfileService proxy to enable calls to the UPA web service.
| [DeployApplicationPackageToAppCatalog(Tenant, String, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.TenantExtensions.8B800134.md) | Adds a package to the tenants app catalog and by default deploys it if the package is a client side package (sppkg)
| [WaitForIsComplete(Tenant, SpoOperation, Func<TenantOperationMessage, Boolean>, TenantOperationMessage)](Microsoft.SharePoint.Client.TenantExtensions.95924360.md) | 
| [IsCannotGetSiteException(Exception)](Microsoft.SharePoint.Client.TenantExtensions.21D08CEE.md) | 
| [IsUnableToAccessSiteException(Exception)](Microsoft.SharePoint.Client.TenantExtensions.7504D4FC.md) | 
| [IsCannotRemoveSiteException(Exception)](Microsoft.SharePoint.Client.TenantExtensions.6EB11217.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
