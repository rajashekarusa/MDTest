# NavigationExtensions
This class holds deprecated navigation related methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class NavigationExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetNavigationSettings(Web)](NavigationExtensionsGetNavigationSettingsWeb.md) | Returns the navigation settings for the selected web
| [UpdateNavigationSettings(Web, OfficeDevPnP.Core.Entities.AreaNavigationEntity)](NavigationExtensionsUpdateNavigationSettingsWebOfficeDevPnP.Core.Entities.AreaNavigationEntity.md) | Updates navigation settings for the current web
| [MapToNavigationIncludeTypes(OfficeDevPnP.Core.Entities.StructuralNavigationEntity)](NavigationExtensionsMapToNavigationIncludeTypesOfficeDevPnP.Core.Entities.StructuralNavigationEntity.md) | 
| [MapFromNavigationIncludeTypes(OfficeDevPnP.Core.Entities.StructuralNavigationEntity, Int32)](NavigationExtensionsMapFromNavigationIncludeTypesOfficeDevPnP.Core.Entities.StructuralNavigationEntityInt32.md) | 
| [ArePublishingFeaturesActivated(PropertyValues)](NavigationExtensionsArePublishingFeaturesActivatedPropertyValues.md) | 
| [GetPropertyAsString(PropertyValues, String)](NavigationExtensionsGetPropertyAsStringPropertyValuesString.md) | 
| [GetPropertyAsInt(PropertyValues, String)](NavigationExtensionsGetPropertyAsIntPropertyValuesString.md) | 
| [GetEditableNavigationTermSet(Web, ManagedNavigationKind)](NavigationExtensionsGetEditableNavigationTermSetWebManagedNavigationKind.md) | Returns an editable version of the Global Navigation TermSet for a web site
| [IsManagedNavigationEnabled(Web, ManagedNavigationKind)](NavigationExtensionsIsManagedNavigationEnabledWebManagedNavigationKind.md) | Determines whether the current Web has the managed navigation enabled
| [GetEditableNavigationTermSetByProviderName(Web, ClientRuntimeContext, String)](NavigationExtensionsGetEditableNavigationTermSetByProviderNameWebClientRuntimeContextString.md) | 
| [AddNavigationNode(Web, String, Uri, String, OfficeDevPnP.Core.Enums.NavigationType, Boolean, Boolean)](NavigationExtensionsAddNavigationNodeWebStringUriStringOfficeDevPnP.Core.Enums.NavigationTypeBooleanBoolean.md) | Add a node to quick launch, top navigation bar or search navigation. The node will be added as the last node in the collection.
| [DeleteNavigationNode(Web, String, String, OfficeDevPnP.Core.Enums.NavigationType)](NavigationExtensionsDeleteNavigationNodeWebStringStringOfficeDevPnP.Core.Enums.NavigationType.md) | Deletes a navigation node from the quickLaunch or top navigation bar
| [DeleteAllNavigationNodes(Web, OfficeDevPnP.Core.Enums.NavigationType)](NavigationExtensionsDeleteAllNavigationNodesWebOfficeDevPnP.Core.Enums.NavigationType.md) | Deletes all Navigation Nodes from a given navigation
| [UpdateNavigationInheritance(Web, Boolean)](NavigationExtensionsUpdateNavigationInheritanceWebBoolean.md) | Updates the navigation inheritance setting
| [LoadSearchNavigation(Web)](NavigationExtensionsLoadSearchNavigationWeb.md) | Loads the search navigation nodes
| [AddCustomAction(Web, OfficeDevPnP.Core.Entities.CustomActionEntity)](NavigationExtensionsAddCustomActionWebOfficeDevPnP.Core.Entities.CustomActionEntity.md) | Adds custom action to a web. If the CustomAction exists the item will be updated. Setting CustomActionEntity.Remove == true will delete the CustomAction.
| [AddCustomAction(Site, OfficeDevPnP.Core.Entities.CustomActionEntity)](NavigationExtensionsAddCustomActionSiteOfficeDevPnP.Core.Entities.CustomActionEntity.md) | Adds custom action to a site collection. If the CustomAction exists the item will be updated. Setting CustomActionEntity.Remove == true will delete the CustomAction.
| [AddCustomActionImplementation(ClientObject, OfficeDevPnP.Core.Entities.CustomActionEntity)](NavigationExtensionsAddCustomActionImplementationClientObjectOfficeDevPnP.Core.Entities.CustomActionEntity.md) | 
| [GetCustomActions(Web, Linq.Expressions.Expression1<Func2<UserCustomAction,Object>>[])](NavigationExtensionsGetCustomActionsWebLinq.Expressions.Expression1<Func2<UserCustomAction,Object>>[].md) | 
| [GetCustomActions(Site, Linq.Expressions.Expression1<Func2<UserCustomAction,Object>>[])](NavigationExtensionsGetCustomActionsSiteLinq.Expressions.Expression1<Func2<UserCustomAction,Object>>[].md) | 
| [DeleteCustomAction(Web, Guid)](NavigationExtensionsDeleteCustomActionWebGuid.md) | Removes a custom action
| [DeleteCustomAction(Site, Guid)](NavigationExtensionsDeleteCustomActionSiteGuid.md) | Removes a custom action
| [CustomActionExists(Web, String)](NavigationExtensionsCustomActionExistsWebString.md) | Utility method to check particular custom action already exists on the web
| [CustomActionExists(Site, String)](NavigationExtensionsCustomActionExistsSiteString.md) | Utility method to check particular custom action already exists on the web
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
