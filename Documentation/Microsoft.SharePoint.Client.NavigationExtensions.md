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
| [GetNavigationSettings(Web)](Microsoft.SharePoint.Client.NavigationExtensions.C72DBB5.md) | Returns the navigation settings for the selected web
| [UpdateNavigationSettings(Web, AreaNavigationEntity)](Microsoft.SharePoint.Client.NavigationExtensions.419CDF55.md) | Updates navigation settings for the current web
| [MapToNavigationIncludeTypes(StructuralNavigationEntity)](Microsoft.SharePoint.Client.NavigationExtensions.FFFF887F.md) | 
| [MapFromNavigationIncludeTypes(StructuralNavigationEntity, Int32)](Microsoft.SharePoint.Client.NavigationExtensions.8FF539C1.md) | 
| [ArePublishingFeaturesActivated(PropertyValues)](Microsoft.SharePoint.Client.NavigationExtensions.AC6CF603.md) | 
| [GetPropertyAsString(PropertyValues, String)](Microsoft.SharePoint.Client.NavigationExtensions.463582C4.md) | 
| [GetPropertyAsInt(PropertyValues, String)](Microsoft.SharePoint.Client.NavigationExtensions.33808160.md) | 
| [GetEditableNavigationTermSet(Web, ManagedNavigationKind)](Microsoft.SharePoint.Client.NavigationExtensions.12EFA587.md) | Returns an editable version of the Global Navigation TermSet for a web site
| [IsManagedNavigationEnabled(Web, ManagedNavigationKind)](Microsoft.SharePoint.Client.NavigationExtensions.60D1127.md) | Determines whether the current Web has the managed navigation enabled
| [GetEditableNavigationTermSetByProviderName(Web, ClientRuntimeContext, String)](Microsoft.SharePoint.Client.NavigationExtensions.DA9AAB13.md) | 
| [AddNavigationNode(Web, String, Uri, String, NavigationType, Boolean, Boolean)](Microsoft.SharePoint.Client.NavigationExtensions.379F276C.md) | Add a node to quick launch, top navigation bar or search navigation. The node will be added as the last node in the collection.
| [DeleteNavigationNode(Web, String, String, NavigationType)](Microsoft.SharePoint.Client.NavigationExtensions.54C91F2E.md) | Deletes a navigation node from the quickLaunch or top navigation bar
| [DeleteAllNavigationNodes(Web, NavigationType)](Microsoft.SharePoint.Client.NavigationExtensions.BFCB26CE.md) | Deletes all Navigation Nodes from a given navigation
| [UpdateNavigationInheritance(Web, Boolean)](Microsoft.SharePoint.Client.NavigationExtensions.C7232652.md) | Updates the navigation inheritance setting
| [LoadSearchNavigation(Web)](Microsoft.SharePoint.Client.NavigationExtensions.4BB1E553.md) | Loads the search navigation nodes
| [AddCustomAction(Web, CustomActionEntity)](Microsoft.SharePoint.Client.NavigationExtensions.C58AE7F0.md) | Adds custom action to a web. If the CustomAction exists the item will be updated. Setting CustomActionEntity.Remove == true will delete the CustomAction.
| [AddCustomAction(Site, CustomActionEntity)](Microsoft.SharePoint.Client.NavigationExtensions.C238735D.md) | Adds custom action to a site collection. If the CustomAction exists the item will be updated. Setting CustomActionEntity.Remove == true will delete the CustomAction.
| [AddCustomActionImplementation(ClientObject, CustomActionEntity)](Microsoft.SharePoint.Client.NavigationExtensions.823851D3.md) | 
| [GetCustomActions(Web, Expression<Func<UserCustomAction, Object>>[])](Microsoft.SharePoint.Client.NavigationExtensions.EAC0E89B.md) | 
| [GetCustomActions(Site, Expression<Func<UserCustomAction, Object>>[])](Microsoft.SharePoint.Client.NavigationExtensions.FC5B2546.md) | 
| [DeleteCustomAction(Web, Guid)](Microsoft.SharePoint.Client.NavigationExtensions.4BB46A7F.md) | Removes a custom action
| [DeleteCustomAction(Site, Guid)](Microsoft.SharePoint.Client.NavigationExtensions.F2016670.md) | Removes a custom action
| [CustomActionExists(Web, String)](Microsoft.SharePoint.Client.NavigationExtensions.45893840.md) | Utility method to check particular custom action already exists on the web
| [CustomActionExists(Site, String)](Microsoft.SharePoint.Client.NavigationExtensions.D520D62A.md) | Utility method to check particular custom action already exists on the web
## Examples
```C#
 var editAction = new CustomActionEntity() { Title = "Edit Site Classification", Description = "Manage business impact information for site collection or sub sites.", Sequence = 1000, Group = "SiteActions", Location = "Microsoft.SharePoint.StandardMenu", Url = EditFormUrl, ImageUrl = EditFormImageUrl, Rights = new BasePermissions(), }; editAction.Rights.Set(PermissionKind.ManageWeb); web.AddCustomAction(editAction); 
```
## See also
- [GetCustomActions](GetCustomActions.md)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
