# WebExtensions.DeleteWeb Method  
Deletes the child website with the specified leaf URL, from a parent Web, if it exists.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean DeleteWeb(Web parentWeb,String leafUrl)
```
### Parameters
*parentWeb*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*leafUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md  
)true if the web was deleted; otherwise false if nothing was done

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
