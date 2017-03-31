# SecurityExtensions.GetAllUniqueRoleAssignments Method  
Get all unique role assignments for a web object and all its descendents down to document or list item level.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.ienumerable`1<officedevpnp.core.entities.roleassignmententity> GetAllUniqueRoleAssignments(Web web,Int32 leafBreadthLimit)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*(optional) leafBreadthLimit*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.IEnumerable`1<OfficeDevPnP.Core.Entities.RoleAssignmentEntity>](System.Collections.Generic.IEnumerable`1<OfficeDevPnP.Core.Entities.RoleAssignmentEntity>.md  
)

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
