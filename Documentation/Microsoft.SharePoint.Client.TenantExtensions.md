# TenantExtensions
Class for deprecated tenant extension methods
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class TenantExtensions```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [CreateSiteCollection(Microsoft.Online.SharePoint.TenantAdministration.Tenant, OfficeDevPnP.Core.Entities.SiteEntity, Boolean, Boolean, Func2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>)](TenantExtensionsCreateSiteCollectionMicrosoft.Online.SharePoint.TenantAdministration.TenantOfficeDevPnP.Core.Entities.SiteEntityBooleanBooleanFunc2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>.md) | 
| [CreateSiteCollection(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String, String, String, String, Int32, Int32, Int32, Int32, Int32, UInt32, Boolean, Boolean, Func2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>)](TenantExtensionsCreateSiteCollectionMicrosoft.Online.SharePoint.TenantAdministration.TenantStringStringStringStringInt32Int32Int32Int32Int32UInt32BooleanBooleanFunc2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>.md) | 
| [CheckIfSiteExists(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String, String)](TenantExtensionsCheckIfSiteExistsMicrosoft.Online.SharePoint.TenantAdministration.TenantStringString.md) | Returns if a site collection is in a particular status. If the url contains a sub site then returns true is the sub site exists, false if not. 
            Status is irrelevant for sub sites
| [IsSiteActive(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String)](TenantExtensionsIsSiteActiveMicrosoft.Online.SharePoint.TenantAdministration.TenantString.md) | Checks if a site collection is Active
| [SiteExists(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String)](TenantExtensionsSiteExistsMicrosoft.Online.SharePoint.TenantAdministration.TenantString.md) | Checks if a site collection exists, relies on tenant admin API. Sites that are recycled also return as existing sites
| [SubSiteExists(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String)](TenantExtensionsSubSiteExistsMicrosoft.Online.SharePoint.TenantAdministration.TenantString.md) | Checks if a sub site exists
| [DeleteSiteCollection(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String, Boolean, Func2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>)](TenantExtensionsDeleteSiteCollectionMicrosoft.Online.SharePoint.TenantAdministration.TenantStringBooleanFunc2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>.md) | 
| [DeleteSiteCollectionFromRecycleBin(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String, Boolean, Func2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>)](TenantExtensionsDeleteSiteCollectionFromRecycleBinMicrosoft.Online.SharePoint.TenantAdministration.TenantStringBooleanFunc2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>.md) | 
| [GetSiteGuidByUrl(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String)](TenantExtensionsGetSiteGuidByUrlMicrosoft.Online.SharePoint.TenantAdministration.TenantString.md) | Gets the ID of site collection with specified URL
| [GetSiteGuidByUrl(Microsoft.Online.SharePoint.TenantAdministration.Tenant, Uri)](TenantExtensionsGetSiteGuidByUrlMicrosoft.Online.SharePoint.TenantAdministration.TenantUri.md) | Gets the ID of site collection with specified URL
| [GetWebTemplates(Microsoft.Online.SharePoint.TenantAdministration.Tenant, UInt32, Int32)](TenantExtensionsGetWebTemplatesMicrosoft.Online.SharePoint.TenantAdministration.TenantUInt32Int32.md) | Returns available webtemplates/site definitions
| [SetSiteProperties(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String, String, Nullable1<Boolean>, Nullable1<Microsoft.Online.SharePoint.TenantManagement.SharingCapabilities>, Nullable1<Int64>, Nullable1<Int64>, Nullable1<Double>, Nullable1<Double>, Nullable1<Boolean>, Boolean, Func2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>)](TenantExtensionsSetSitePropertiesMicrosoft.Online.SharePoint.TenantAdministration.TenantStringStringNullable1<Boolean>Nullable1<Microsoft.Online.SharePoint.TenantManagement.SharingCapabilities>Nullable1<Int64>Nullable1<Int64>Nullable1<Double>Nullable1<Double>Nullable1<Boolean>BooleanFunc2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>.md) | 
| [SetSiteLockState(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String, OfficeDevPnP.Core.SiteLockState, Boolean, Func2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>)](TenantExtensionsSetSiteLockStateMicrosoft.Online.SharePoint.TenantAdministration.TenantStringOfficeDevPnP.Core.SiteLockStateBooleanFunc2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>.md) | 
| [AddAdministrators(Microsoft.Online.SharePoint.TenantAdministration.Tenant, Collections.Generic.IEnumerable1<OfficeDevPnP.Core.Entities.UserEntity>, Uri, Boolean)](TenantExtensionsAddAdministratorsMicrosoft.Online.SharePoint.TenantAdministration.TenantCollections.Generic.IEnumerable1<OfficeDevPnP.Core.Entities.UserEntity>UriBoolean.md) | 
| [GetSiteCollections(Microsoft.Online.SharePoint.TenantAdministration.Tenant, Int32, Int32, Boolean, Boolean)](TenantExtensionsGetSiteCollectionsMicrosoft.Online.SharePoint.TenantAdministration.TenantInt32Int32BooleanBoolean.md) | Returns all site collections in the current Tenant based on a startIndex. IncludeDetail adds additional properties to the SPSite object.
| [GetOneDriveSiteCollections(Microsoft.Online.SharePoint.TenantAdministration.Tenant)](TenantExtensionsGetOneDriveSiteCollectionsMicrosoft.Online.SharePoint.TenantAdministration.Tenant.md) | Get OneDrive site collections by iterating through all user profiles.
| [GetUserProfileServiceClient(Microsoft.Online.SharePoint.TenantAdministration.Tenant)](TenantExtensionsGetUserProfileServiceClientMicrosoft.Online.SharePoint.TenantAdministration.Tenant.md) | Gets the UserProfileService proxy to enable calls to the UPA web service.
| [DeployApplicationPackageToAppCatalog(Microsoft.Online.SharePoint.TenantAdministration.Tenant, String, String, String, Boolean, Boolean)](TenantExtensionsDeployApplicationPackageToAppCatalogMicrosoft.Online.SharePoint.TenantAdministration.TenantStringStringStringBooleanBoolean.md) | Adds a package to the tenants app catalog and by default deploys it if the package is a client side package (sppkg)
| [WaitForIsComplete(Microsoft.Online.SharePoint.TenantAdministration.Tenant, Microsoft.Online.SharePoint.TenantAdministration.SpoOperation, Func2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>, OfficeDevPnP.Core.TenantOperationMessage)](TenantExtensionsWaitForIsCompleteMicrosoft.Online.SharePoint.TenantAdministration.TenantMicrosoft.Online.SharePoint.TenantAdministration.SpoOperationFunc2<OfficeDevPnP.Core.TenantOperationMessage,Boolean>OfficeDevPnP.Core.TenantOperationMessage.md) | 
| [IsCannotGetSiteException(Exception)](TenantExtensionsIsCannotGetSiteExceptionException.md) | 
| [IsUnableToAccessSiteException(Exception)](TenantExtensionsIsUnableToAccessSiteExceptionException.md) | 
| [IsCannotRemoveSiteException(Exception)](TenantExtensionsIsCannotRemoveSiteExceptionException.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
