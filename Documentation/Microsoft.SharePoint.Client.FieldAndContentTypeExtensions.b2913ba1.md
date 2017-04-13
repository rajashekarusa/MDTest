# FieldAndContentTypeExtensions.AddFieldById Method  
 Associates field to content type   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void AddFieldById(ContentType contentType, String fieldId, Boolean required, Boolean hidden)
```
### Parameters
#### contentType  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.ContentType  
&emsp;&emsp;Content Type to add the field to  

  

#### fieldId  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;String representation of the id of the field (=Guid)  

  

#### (optional) required  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;True if the field is required  

  

#### (optional) hidden  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;True if the field is hidden  

  

### Return Value
Type: void  

## Remarks
  
## See also
- [FieldAndContentTypeExtensions](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
