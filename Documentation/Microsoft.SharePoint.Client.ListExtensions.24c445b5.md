# ListExtensions.UpdateTaxonomyFieldDefaultValue Method  
Sets the default value for a managed metadata column in the specified list. This operation will not change existing items in the list  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void UpdateTaxonomyFieldDefaultValue(Web web,String termName,String listName,String fieldInternalName,Guid groupGuid,Guid termSetGuid)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*termName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*listName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*fieldInternalName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*groupGuid*  
&emsp;&emsp;Type: [System.Guid](System.Guid.md) 
&emsp;&emsp;  
  
*termSetGuid*  
&emsp;&emsp;Type: [System.Guid](System.Guid.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md  
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
