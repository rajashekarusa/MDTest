# SecurityExtensions.AddPermissionLevelToGroup Method  
 Add a role definition (e.g.Contribute, Read, Approve) to a group   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void AddPermissionLevelToGroup(SecurableObject securableObject, String groupName, String roleDefinitionName, Boolean removeExistingPermissionLevels)
```
### Parameters
#### securableObject  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.SecurableObject  
&emsp;&emsp;Web/List/Item to operate against  

  

#### groupName  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Name of the group  

  

#### roleDefinitionName  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Name of the role definition to add, Full Control|Design|Contribute|Read|Approve|Manage Hierarchy|Restricted Read. Use the correct name of the language of the root site you are using  

  

#### (optional) removeExistingPermissionLevels  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Set to true to remove all other permission levels for that group  

  

### Return Value
Type: void  

## Remarks
  
## See also
- [SecurityExtensions](Microsoft.SharePoint.Client.SecurityExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
