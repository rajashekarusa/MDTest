# FileFolderExtensions.GetFile Method  
Gets a file in a document library.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  GetFile(Folder folder,String fileName)
```
### Parameters
*folder*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Folder  
&emsp;&emsp;Folder containing the target file.  
  
*fileName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;File name.  
  
### Return Value
Type: [Microsoft.SharePoint.Client.File]  
The target file if found, null if no file is found.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)