# FileFolderExtensions.EnsureFolder Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static Folder EnsureFolder(Web web, Folder parentFolder, String folderPath, Expression<Func<Folder, Object>>[] expressions)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  

*parentFolder*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Folder  

*folderPath*  
&emsp;&emsp;Type: System.String  

*expressions*  
&emsp;&emsp;Type: System.Linq.Expressions.Expression<System.Func<Microsoft.SharePoint.Client.Folder, System.Object>>[]  

### Return Value
Type: Folder  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
