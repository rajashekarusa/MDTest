# NavigationExtensions
This class holds deprecated navigation related methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class NavigationExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetNavigationSettings(Web)](Microsoft.SharePoint.Client.NavigationExtensions.GetNavigationSettingsWeb.md) | Returns the navigation settings for the selected web
| [UpdateNavigationSettings(Web, OfficeDevPnP.Core.Entities.AreaNavigationEntity)](Microsoft.SharePoint.Client.NavigationExtensions.UpdateNavigationSettingsWebOfficeDevPnP.Core.Entities.AreaNavigationEntity.md) | Updates navigation settings for the current web
| [MapToNavigationIncludeTypes(OfficeDevPnP.Core.Entities.StructuralNavigationEntity)](Microsoft.SharePoint.Client.NavigationExtensions.MapToNavigationIncludeTypesOfficeDevPnP.Core.Entities.StructuralNavigationEntity.md) | 
| [MapFromNavigationIncludeTypes(OfficeDevPnP.Core.Entities.StructuralNavigationEntity, Int32)](Microsoft.SharePoint.Client.NavigationExtensions.MapFromNavigationIncludeTypesOfficeDevPnP.Core.Entities.StructuralNavigationEntityInt32.md) | 
| [ArePublishingFeaturesActivated(PropertyValues)](Microsoft.SharePoint.Client.NavigationExtensions.ArePublishingFeaturesActivatedPropertyValues.md) | 
| [GetPropertyAsString(PropertyValues, String)](Microsoft.SharePoint.Client.NavigationExtensions.GetPropertyAsStringPropertyValuesString.md) | 
| [GetPropertyAsInt(PropertyValues, String)](Microsoft.SharePoint.Client.NavigationExtensions.GetPropertyAsIntPropertyValuesString.md) | 
| [GetEditableNavigationTermSet(Web, ManagedNavigationKind)](Microsoft.SharePoint.Client.NavigationExtensions.GetEditableNavigationTermSetWebManagedNavigationKind.md) | Returns an editable version of the Global Navigation TermSet for a web site
| [IsManagedNavigationEnabled(Web, ManagedNavigationKind)](Microsoft.SharePoint.Client.NavigationExtensions.IsManagedNavigationEnabledWebManagedNavigationKind.md) | Determines whether the current Web has the managed navigation enabled
| [GetEditableNavigationTermSetByProviderName(Web, ClientRuntimeContext, String)](Microsoft.SharePoint.Client.NavigationExtensions.GetEditableNavigationTermSetByProviderNameWebClientRuntimeContextString.md) | 
| [AddNavigationNode(Web, String, Uri, String, OfficeDevPnP.Core.Enums.NavigationType, Boolean, Boolean)](Microsoft.SharePoint.Client.NavigationExtensions.AddNavigationNodeWebStringUriStringOfficeDevPnP.Core.Enums.NavigationTypeBooleanBoolean.md) | Add a node to quick launch, top navigation bar or search navigation. The node will be added as the last node in the collection.
| [DeleteNavigationNode(Web, String, String, OfficeDevPnP.Core.Enums.NavigationType)](Microsoft.SharePoint.Client.NavigationExtensions.DeleteNavigationNodeWebStringStringOfficeDevPnP.Core.Enums.NavigationType.md) | Deletes a navigation node from the quickLaunch or top navigation bar
| [DeleteAllNavigationNodes(Web, OfficeDevPnP.Core.Enums.NavigationType)](Microsoft.SharePoint.Client.NavigationExtensions.DeleteAllNavigationNodesWebOfficeDevPnP.Core.Enums.NavigationType.md) | Deletes all Navigation Nodes from a given navigation
| [UpdateNavigationInheritance(Web, Boolean)](Microsoft.SharePoint.Client.NavigationExtensions.UpdateNavigationInheritanceWebBoolean.md) | Updates the navigation inheritance setting
| [LoadSearchNavigation(Web)](Microsoft.SharePoint.Client.NavigationExtensions.LoadSearchNavigationWeb.md) | Loads the search navigation nodes
| [AddCustomAction(Web, OfficeDevPnP.Core.Entities.CustomActionEntity)](Microsoft.SharePoint.Client.NavigationExtensions.AddCustomActionWebOfficeDevPnP.Core.Entities.CustomActionEntity.md) | Adds custom action to a web. If the CustomAction exists the item will be updated. Setting CustomActionEntity.Remove == true will delete the CustomAction.
| [AddCustomAction(Site, OfficeDevPnP.Core.Entities.CustomActionEntity)](Microsoft.SharePoint.Client.NavigationExtensions.AddCustomActionSiteOfficeDevPnP.Core.Entities.CustomActionEntity.md) | Adds custom action to a site collection. If the CustomAction exists the item will be updated. Setting CustomActionEntity.Remove == true will delete the CustomAction.
| [AddCustomActionImplementation(ClientObject, OfficeDevPnP.Core.Entities.CustomActionEntity)](Microsoft.SharePoint.Client.NavigationExtensions.AddCustomActionImplementationClientObjectOfficeDevPnP.Core.Entities.CustomActionEntity.md) | 
| [GetCustomActions(Web, Linq.Expressions.Expression<Func<UserCustomAction,Object>>[])](Microsoft.SharePoint.Client.NavigationExtensions.GetCustomActionsWebLinq.Expressions.Expression<Func<UserCustomAction,Object>>[].md) | 
| [GetCustomActions(Site, Linq.Expressions.Expression<Func<UserCustomAction,Object>>[])](Microsoft.SharePoint.Client.NavigationExtensions.GetCustomActionsSiteLinq.Expressions.Expression<Func<UserCustomAction,Object>>[].md) | 
| [DeleteCustomAction(Web, Guid)](Microsoft.SharePoint.Client.NavigationExtensions.DeleteCustomActionWebGuid.md) | Removes a custom action
| [DeleteCustomAction(Site, Guid)](Microsoft.SharePoint.Client.NavigationExtensions.DeleteCustomActionSiteGuid.md) | Removes a custom action
| [CustomActionExists(Web, String)](Microsoft.SharePoint.Client.NavigationExtensions.CustomActionExistsWebString.md) | Utility method to check particular custom action already exists on the web
| [CustomActionExists(Site, String)](Microsoft.SharePoint.Client.NavigationExtensions.CustomActionExistsSiteString.md) | Utility method to check particular custom action already exists on the web
## Examples
```C#
 var editAction = new CustomActionEntity() { Title = "Edit Site Classification", Description = "Manage business impact information for site collection or sub sites.", Sequence = 1000, Group = "SiteActions", Location = "Microsoft.SharePoint.StandardMenu", Url = EditFormUrl, ImageUrl = EditFormImageUrl, Rights = new BasePermissions(), }; editAction.Rights.Set(PermissionKind.ManageWeb); web.AddCustomAction(editAction); 
```
## See also
- [GetCustomActions](GetCustomActions.md)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
