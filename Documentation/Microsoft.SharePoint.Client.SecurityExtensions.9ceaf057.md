# SecurityExtensions.AssociateDefaultGroups Method  
Associate the provided groups as default owners, members or visitors groups. If a group is null then the 
            association is not done  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void AssociateDefaultGroups(Web web,Group owners,Group members,Group visitors)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*owners*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Group](Microsoft.SharePoint.Client.Group.md) 
&emsp;&emsp;  
  
*members*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Group](Microsoft.SharePoint.Client.Group.md) 
&emsp;&emsp;  
  
*visitors*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Group](Microsoft.SharePoint.Client.Group.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md)  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
