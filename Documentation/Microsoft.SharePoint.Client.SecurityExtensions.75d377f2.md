# SecurityExtensions.IsUserInGroup Method  
Checks if a user is member of a group  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean IsUserInGroup(Web web,String groupName,String userLoginName)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web to operate against  
  
*groupName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Name of the group  
  
*userLoginName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Loginname of the user  
  
### Return Value
Type: System.Boolean  
True if the user is in the group, false otherwise

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
