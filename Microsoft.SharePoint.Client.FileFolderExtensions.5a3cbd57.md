# FileFolderExtensions.CreateFolder Method  
Creates a folder with the given name as a child of the Web. 
            Note it is more common to create folders within an existing Folder, such as the RootFolder of a List.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateFolder(Web web,String folderName)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*folderName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md 
)The newly created Folder, so that additional operations (such as setting properties) can be done.

## Remarks 

            Note that this only checks one level of folder (the Folders collection) and cannot accept a name with path characters.
            
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
