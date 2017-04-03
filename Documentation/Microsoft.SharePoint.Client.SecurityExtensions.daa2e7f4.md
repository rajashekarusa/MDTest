# SecurityExtensions.GetAllUniqueRoleAssignments Method  
Get all unique role assignments for a web object and all its descendents down to document or list item level.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.ienumerable<officedevpnp.core.entities.roleassignmententity> GetAllUniqueRoleAssignments(Web web,Int32 leafBreadthLimit)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;The current web object to be processed.  
  
*(optional) leafBreadthLimit*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;Skip further visiting on this branch if the number of child items or documents with unique role assignments exceeded leafBreadthLimit. When setting to 0, the process will stop at list / document library level.  
  
### Return Value
Type: [System.Collections.Generic.IEnumerable<OfficeDevPnP.Core.Entities.RoleAssignmentEntity>]  


## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)