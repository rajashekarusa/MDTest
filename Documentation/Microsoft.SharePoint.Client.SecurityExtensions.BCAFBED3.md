# SecurityExtensions.AddPermissionLevelToPrincipal Method  
Add a role definition (e.g.Contribute, Read, Approve) to a group  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void AddPermissionLevelToPrincipal(SecurableObject securableObject,Principal principal,String roleDefinitionName,Boolean removeExistingPermissionLevels)
```
### Parameters
*securableObject*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.SecurableObject](Microsoft.SharePoint.Client.SecurableObject.md) 
&emsp;&emsp;  
  
*principal*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Principal](Microsoft.SharePoint.Client.Principal.md) 
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
