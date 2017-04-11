# FileFolderExtensions.UploadFile Method  
 Uploads a file to the specified folder.   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static File UploadFile(Folder folder, String fileName, Stream stream, Boolean overwriteIfExists)
```
### Parameters
#### folder  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Folder  
&emsp;&emsp;Folder to upload file to.  

  

#### fileName  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Location of the file to be uploaded.  

  

#### stream  
&emsp;&emsp;Type: System.IO.Stream  
&emsp;&emsp; Uploads a file to the specified folder.   

  

#### overwriteIfExists  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;true (default) to overwite existing files  

  

### Return Value
Type: File  
The uploaded File, so that additional operations (such as setting properties) can be done.  


## See also
- [FileFolderExtensions](Microsoft.SharePoint.Client.FileFolderExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
