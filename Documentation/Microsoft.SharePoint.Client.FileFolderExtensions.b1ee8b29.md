# FileFolderExtensions.ConvertFolderToDocumentSet Method  
Converts a folder with the given name as a child of the List RootFolder.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  ConvertFolderToDocumentSet(List list,String folderName)
```
### Parameters
*list*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md) 
&emsp;&emsp;  
  
*folderName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md)  
The newly converted Document Set, so that additional operations (such as setting properties) can be done.

## Remarks 

            Note that this only checks one level of folder (the Folders collection) and cannot accept a name with path characters.
            
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
