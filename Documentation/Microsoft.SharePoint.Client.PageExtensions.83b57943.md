# PageExtensions.AddWebPartToWikiPage Method  
Add web part to a wiki style page  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  AddWebPartToWikiPage(Web web,String serverRelativePageUrl,WebPartEntity webPart,Int32 row,Int32 col,Boolean addSpace)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*serverRelativePageUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*webPart*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Entities.WebPartEntity](OfficeDevPnP.Core.Entities.WebPartEntity.md) 
&emsp;&emsp;  
  
*row*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*col*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*addSpace*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.WebParts.WebPartDefinition](Microsoft.SharePoint.Client.WebParts.WebPartDefinition.md)  
Returns the added  object

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
