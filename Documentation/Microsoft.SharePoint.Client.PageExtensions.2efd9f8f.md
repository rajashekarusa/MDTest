# PageExtensions.EnsureWikiPage Method  
Returns the Url for the requested wiki page, creates it if the pageis not yet available  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string EnsureWikiPage(Web web,String wikiPageLibraryName,String wikiPageName)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*wikiPageLibraryName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*wikiPageName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.String](System.String.md  
)The relative URL of the added wiki page

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
