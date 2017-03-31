# FieldAndContentTypeExtensions.SetDefaultContentTypeToList Method  
Set's default content type list.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetDefaultContentTypeToList(Web web,String listTitle,ContentType contentType)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*listTitle*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*contentType*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ContentType](Microsoft.SharePoint.Client.ContentType.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md 
)
## Remarks 
Notice. Currently removes other content types from the list. Known issue
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
