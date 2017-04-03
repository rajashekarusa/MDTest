# FieldAndContentTypeExtensions.CreateField Method  
Adds a field to a list  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateField(List list,String fieldAsXml,Boolean executeQuery)
```
### Parameters
*list*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.List  
&emsp;&emsp;List to process  
  
*fieldAsXml*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The XML declaration of SiteColumn definition  
  
*(optional) executeQuery*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Optionally skip the executeQuery action  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Field]  
The newly created field or existing field.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)