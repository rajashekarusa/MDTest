# PageExtensions.AddWikiPage Method  
 Adds a blank Wiki page to the site pages library   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string AddWikiPage(this Web web, String wikiPageLibraryName, String wikiPageName)
```
### Parameters
#### web  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  

  

#### wikiPageLibraryName  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Name of the wiki page library  

  

#### wikiPageName  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Wiki page to operate on  

  

### Return Value
Type: string  
The relative URL of the added wiki page  


## See also
- [PageExtensions](Microsoft.SharePoint.Client.PageExtensions.md) 
- System.ArgumentException
- System.ArgumentNullException
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
