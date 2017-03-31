# FileFolderExtensions.FolderExists Method  
Checks if the subfolder exists.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean FolderExists(Folder parentFolder,String folderName)
```
### Parameters
*parentFolder*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md) 
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
