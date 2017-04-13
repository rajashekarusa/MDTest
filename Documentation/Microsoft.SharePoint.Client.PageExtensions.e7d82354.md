# PageExtensions.AddWebPartToWebPartPage Method  
 Inserts a web part on a web part page   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static WebPartDefinition AddWebPartToWebPartPage(Web web, String serverRelativePageUrl, WebPartEntity webPart)
```
### Parameters
#### web  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  

  

#### serverRelativePageUrl  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Page to add the web part on  

  

#### webPart  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Entities.WebPartEntity](OfficeDevPnP.Core.Entities.WebPartEntity.md)  
&emsp;&emsp;Information about the web part to insert  

  

### Return Value
Type: WebPartDefinition  
Returns the added Microsoft.SharePoint.Client.WebParts.WebPartDefinition object  


## Remarks
  
## See also
- [PageExtensions](Microsoft.SharePoint.Client.PageExtensions.md) 
- Microsoft.SharePoint.Client.WebParts.WebPartDefinition
- System.ArgumentException
- System.ArgumentNullException
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
