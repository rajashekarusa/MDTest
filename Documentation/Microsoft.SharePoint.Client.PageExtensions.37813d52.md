# PageExtensions.GetWebParts Method  
List the web parts on a page  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.ienumerable<microsoft.sharepoint.client.webparts.webpartdefinition> GetWebParts(Web web,String serverRelativePageUrl)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web] 
&emsp;&emsp;Site to be processed - can be root web or sub site  
  
*serverRelativePageUrl*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;Server relative url of the page containing the webparts  
  
### Return Value
Type: [System.Collections.Generic.IEnumerable<Microsoft.SharePoint.Client.WebParts.WebPartDefinition>]  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
