# WebExtensions.RemoveAppInstanceByTitle Method  
Removes the app instance with the specified title.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean RemoveAppInstanceByTitle(Web web,String appTitle)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web to remove the app instance from  
  
*appTitle*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Title of the app instance to remove  
  
### Return Value
Type: [System.Boolean]  
true if the the app instance was removed; false if it does not exist

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)