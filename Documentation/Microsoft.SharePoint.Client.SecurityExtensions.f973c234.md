# SecurityExtensions.AddPermissionLevelToUser Method  
Add a role definition (e.g.Contribute, Read, Approve) to a user  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void AddPermissionLevelToUser(SecurableObject securableObject,String userLoginName,String roleDefinitionName,Boolean removeExistingPermissionLevels)
```
### Parameters
*securableObject*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.SecurableObject](Microsoft.SharePoint.Client.SecurableObject.md) 
&emsp;&emsp;  
  
*userLoginName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*roleDefinitionName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) removeExistingPermissionLevels*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md  
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
