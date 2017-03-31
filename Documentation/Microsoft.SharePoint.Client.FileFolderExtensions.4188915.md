# FileFolderExtensions.UploadFile Method  
Uploads a file to the specified folder.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  UploadFile(Folder folder,String fileName,String localFilePath,Boolean overwriteIfExists)
```
### Parameters
*folder*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md) 
&emsp;&emsp;  
  
*fileName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*localFilePath*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*overwriteIfExists*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.File](Microsoft.SharePoint.Client.File.md)  
The uploaded File, so that additional operations (such as setting properties) can be done.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
