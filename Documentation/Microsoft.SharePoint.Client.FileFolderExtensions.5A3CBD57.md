Web, String# FileFolderExtensions.CreateFolder members
Creates a folder with the given name as a child of the Web. 
            Note it is more common to create folders within an existing Folder, such as the RootFolder of a List.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateFolder(Web, String)
```
### Parameters
#### web
Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
#### 
#### folderName
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md)The newly created Folder, so that additional operations (such as setting properties) can be done.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
