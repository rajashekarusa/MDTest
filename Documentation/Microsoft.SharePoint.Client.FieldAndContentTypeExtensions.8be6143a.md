# FieldAndContentTypeExtensions.CreateField Method  
Create field to web remotely  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateField(Web web,String fieldAsXml,Boolean executeQuery)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  
  
*fieldAsXml*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The XML declaration of SiteColumn definition  
  
*(optional) executeQuery*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Field]  
The newly created field or existing field.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)