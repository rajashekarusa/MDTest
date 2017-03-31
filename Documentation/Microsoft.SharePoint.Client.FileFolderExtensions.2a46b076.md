# FileFolderExtensions.UploadFileWebDav Method  
Uploads a file to the specified folder by saving the binary directly (via webdav).
            Note: this method does not work using app only token.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  UploadFileWebDav(Folder folder,String fileName,Stream stream,Boolean overwriteIfExists)
```
### Parameters
*folder*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md) 
&emsp;&emsp;  
  
*fileName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*stream*  
&emsp;&emsp;Type: [System.IO.Stream](System.IO.Stream.md) 
&emsp;&emsp;  
  
*overwriteIfExists*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.File](Microsoft.SharePoint.Client.File.md)  
The uploaded File, so that additional operations (such as setting properties) can be done.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
