# UnifiedGroupsUtility
  

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class UnifiedGroupsUtility
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [CreateGraphClient(String, Int32, Int32)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.CreateGraphClientStringInt32Int32.md) | 
| [GetUnifiedGroupSiteUrl(String, String, Int32, Int32)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.GetUnifiedGroupSiteUrlStringStringInt32Int32.md) | Returns the URL of the Modern SharePoint Site backing an Office 365 Group (i.e. Unified Group)
| [CreateUnifiedGroup(String, String, String, String, String[], String[], IO.Stream, Boolean, Int32, Int32)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.CreateUnifiedGroupStringStringStringStringString[]String[]IO.StreamBooleanInt32Int32.md) | Creates a new Office 365 Group (i.e. Unified Group) with its backing Modern SharePoint Site
| [AddMembers(String[], Microsoft.Graph.GraphServiceClient, Microsoft.Graph.Group)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.AddMembersString[]Microsoft.Graph.GraphServiceClientMicrosoft.Graph.Group.md) | 
| [AddOwners(String[], Microsoft.Graph.GraphServiceClient, Microsoft.Graph.Group)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.AddOwnersString[]Microsoft.Graph.GraphServiceClientMicrosoft.Graph.Group.md) | 
| [UpdateUnifiedGroup(String, String, Int32, Int32, String, String, String[], String[], IO.Stream, Boolean)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.UpdateUnifiedGroupStringStringInt32Int32StringStringString[]String[]IO.StreamBoolean.md) | Updates the logo, members or visibility state of an Office 365 Group
| [CreateUnifiedGroup(String, String, String, String, String[], String[], String, Boolean, Int32, Int32)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.CreateUnifiedGroupStringStringStringStringString[]String[]StringBooleanInt32Int32.md) | Creates a new Office 365 Group (i.e. Unified Group) with its backing Modern SharePoint Site
| [CreateUnifiedGroup(String, String, String, String, String[], String[], Boolean, Int32, Int32)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.CreateUnifiedGroupStringStringStringStringString[]String[]BooleanInt32Int32.md) | Creates a new Office 365 Group (i.e. Unified Group) with its backing Modern SharePoint Site
| [DeleteUnifiedGroup(String, String, Int32, Int32)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.DeleteUnifiedGroupStringStringInt32Int32.md) | Deletes an Office 365 Group (i.e. Unified Group)
| [GetUnifiedGroup(String, String, Int32, Int32, Boolean)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.GetUnifiedGroupStringStringInt32Int32Boolean.md) | Get an Office 365 Group (i.e. Unified Group) by Id
| [ListUnifiedGroups(String, String, String, Int32, Int32, Boolean, Int32, Int32)](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.ListUnifiedGroupsStringStringStringInt32Int32BooleanInt32Int32.md) | Returns all the Office 365 Groups in the current Tenant based on a startIndex. IncludeSite adds additional properties about the Modern SharePoint Site backing the group
## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
