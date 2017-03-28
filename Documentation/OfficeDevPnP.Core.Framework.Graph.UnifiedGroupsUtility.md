# UnifiedGroupsUtility

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class UnifiedGroupsUtility
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [CreateGraphClient(String, Int32, Int32)](UnifiedGroupsUtilityCreateGraphClientStringInt32Int32.md) | 
| [GetUnifiedGroupSiteUrl(String, String, Int32, Int32)](UnifiedGroupsUtilityGetUnifiedGroupSiteUrlStringStringInt32Int32.md) | Returns the URL of the Modern SharePoint Site backing an Office 365 Group (i.e. Unified Group)
| [CreateUnifiedGroup(String, String, String, String, String[], String[], IO.Stream, Boolean, Int32, Int32)](UnifiedGroupsUtilityCreateUnifiedGroupStringStringStringStringString[]String[]IO.StreamBooleanInt32Int32.md) | Creates a new Office 365 Group (i.e. Unified Group) with its backing Modern SharePoint Site
| [AddMembers(String[], Microsoft.Graph.GraphServiceClient, Microsoft.Graph.Group)](UnifiedGroupsUtilityAddMembersString[]Microsoft.Graph.GraphServiceClientMicrosoft.Graph.Group.md) | 
| [AddOwners(String[], Microsoft.Graph.GraphServiceClient, Microsoft.Graph.Group)](UnifiedGroupsUtilityAddOwnersString[]Microsoft.Graph.GraphServiceClientMicrosoft.Graph.Group.md) | 
| [UpdateUnifiedGroup(String, String, Int32, Int32, String, String, String[], String[], IO.Stream, Boolean)](UnifiedGroupsUtilityUpdateUnifiedGroupStringStringInt32Int32StringStringString[]String[]IO.StreamBoolean.md) | Updates the logo, members or visibility state of an Office 365 Group
| [CreateUnifiedGroup(String, String, String, String, String[], String[], String, Boolean, Int32, Int32)](UnifiedGroupsUtilityCreateUnifiedGroupStringStringStringStringString[]String[]StringBooleanInt32Int32.md) | Creates a new Office 365 Group (i.e. Unified Group) with its backing Modern SharePoint Site
| [CreateUnifiedGroup(String, String, String, String, String[], String[], Boolean, Int32, Int32)](UnifiedGroupsUtilityCreateUnifiedGroupStringStringStringStringString[]String[]BooleanInt32Int32.md) | Creates a new Office 365 Group (i.e. Unified Group) with its backing Modern SharePoint Site
| [DeleteUnifiedGroup(String, String, Int32, Int32)](UnifiedGroupsUtilityDeleteUnifiedGroupStringStringInt32Int32.md) | Deletes an Office 365 Group (i.e. Unified Group)
| [GetUnifiedGroup(String, String, Int32, Int32, Boolean)](UnifiedGroupsUtilityGetUnifiedGroupStringStringInt32Int32Boolean.md) | Get an Office 365 Group (i.e. Unified Group) by Id
| [ListUnifiedGroups(String, String, String, Int32, Int32, Boolean, Int32, Int32)](UnifiedGroupsUtilityListUnifiedGroupsStringStringStringInt32Int32BooleanInt32Int32.md) | Returns all the Office 365 Groups in the current Tenant based on a startIndex. IncludeSite adds additional properties about the Modern SharePoint Site backing the group
## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
