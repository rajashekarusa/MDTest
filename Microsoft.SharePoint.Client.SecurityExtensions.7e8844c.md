# SecurityExtensions.AddPermissionLevelToGroup Method  
Add a permission level (e.g.Contribute, Reader,...) to a group  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void AddPermissionLevelToGroup(SecurableObject securableObject,String groupName,RoleType permissionLevel,Boolean removeExistingPermissionLevels)
```
### Parameters
*securableObject*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.SecurableObject](Microsoft.SharePoint.Client.SecurableObject.md) 
&emsp;&emsp;  
  
*groupName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*permissionLevel*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.RoleType](Microsoft.SharePoint.Client.RoleType.md) 
&emsp;&emsp;  
  
*(optional) removeExistingPermissionLevels*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md 
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)