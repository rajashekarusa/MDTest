# FileFolderExtensions.FindFiles Method  
Finds files in the web. Can be slow.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.list<microsoft.sharepoint.client.file> FindFiles(Web web,String match)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web] 
&emsp;&emsp;The web to process  
  
*match*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;a wildcard pattern to match  
  
### Return Value
Type: [System.Collections.Generic.List<Microsoft.SharePoint.Client.File>]  
A list with the found  objects

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
