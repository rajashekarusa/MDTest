Folder, String, String, Boolean# FileFolderExtensions.UploadFileWebDav members
Uploads a file to the specified folder by saving the binary directly (via webdav).  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  UploadFileWebDav(Folder, String, String, Boolean)
```
### Parameters
#### folder
Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md) 
#### 
#### fileName
Type: [System.String](System.String.md) 
#### 
#### localFilePath
Type: [System.String](System.String.md) 
#### 
#### overwriteIfExists
Type: [System.Boolean](System.Boolean.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.File](Microsoft.SharePoint.Client.File.md)The uploaded File, so that additional operations (such as setting properties) can be done.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
