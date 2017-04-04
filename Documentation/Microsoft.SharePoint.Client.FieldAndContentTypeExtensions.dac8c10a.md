# FieldAndContentTypeExtensions.GetContentTypeByName Method  
Return content type by name  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static Microsoft.SharePoint.Client.ContentType GetContentTypeByName(Web web, String contentTypeName, Boolean searchInSiteHierarchy)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web to be processed  
  
*contentTypeName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Name of the content type  
  
*(optional) searchInSiteHierarchy*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Searches accross all content types in the site up to the root site  
  
### Return Value
Type: Microsoft.SharePoint.Client.ContentType  
Content type object or null if was not found

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
