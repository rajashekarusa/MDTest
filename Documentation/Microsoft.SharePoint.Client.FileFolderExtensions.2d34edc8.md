# FileFolderExtensions.CreateFolder Method  
Creates a folder with the given name.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateFolder(Folder parentFolder,String folderName)
```
### Parameters
*parentFolder*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md) 
&emsp;&emsp;  
  
*folderName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md  
)The newly created folder

## Remarks 

            Note that this only checks one level of folder (the Folders collection) and cannot accept a name with path characters.
            
                var folder = list.RootFolder.CreateFolder("new-folder");
            
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
