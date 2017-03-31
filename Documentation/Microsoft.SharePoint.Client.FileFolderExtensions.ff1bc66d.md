# FileFolderExtensions.EnsureFolder Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  EnsureFolder(Web web,Folder parentFolder,String folderPath,Expression<Func<Folder, Object>>[] expressions)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*parentFolder*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md) 
&emsp;&emsp;  
  
*folderPath*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*expressions*  
&emsp;&emsp;Type: [System.Linq.Expressions.Expression<System.Func<Microsoft.SharePoint.Client.Folder,System.Object>>[]](System.Linq.Expressions.Expression<System.Func<Microsoft.SharePoint.Client.Folder,System.Object>>[].md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Folder](Microsoft.SharePoint.Client.Folder.md 
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
