# BrandingExtensions.GetPageLayoutListItemByName Method  
Gets a page layout from the master page catalog. Can be called with paramter as "pagelayout.aspx" or as full path like "_catalog/masterpage/pagelayout.aspx"  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  GetPageLayoutListItemByName(Web web,String pageLayoutName)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*pageLayoutName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ListItem](Microsoft.SharePoint.Client.ListItem.md  
)ListItem holding the page layout, null if not found

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
