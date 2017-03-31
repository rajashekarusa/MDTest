# ListExtensions.CreateList Method  
Adds a default list to a site  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateList(Web web,ListTemplateType listType,String listName,Boolean enableVersioning,Boolean updateAndExecuteQuery,String urlPath,Boolean enableContentTypes)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*listType*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ListTemplateType](Microsoft.SharePoint.Client.ListTemplateType.md) 
&emsp;&emsp;  
  
*listName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*enableVersioning*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) updateAndExecuteQuery*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) urlPath*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) enableContentTypes*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md  
)The newly created list

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
