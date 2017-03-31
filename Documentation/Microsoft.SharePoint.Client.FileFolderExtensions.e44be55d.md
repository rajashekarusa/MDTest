# FileFolderExtensions.FolderExists Method  
Checks if the folder exists at the top level of the web site.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean FolderExists(Web web,String folderName)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*folderName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md)  
true if the folder exists; false otherwise

## Remarks 

            Note that this only checks one level of folder (the Folders collection) and cannot accept a name with path characters.
            
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
