# ListExtensions.CreateView Method  
Create view to existing list  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateView(List list,String viewName,ViewType viewType,String[] viewFields,UInt32 rowLimit,Boolean setAsDefault,String query,Boolean personal,Boolean paged)
```
### Parameters
*list*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md) 
&emsp;&emsp;  
  
*viewName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*viewType*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ViewType](Microsoft.SharePoint.Client.ViewType.md) 
&emsp;&emsp;  
  
*viewFields*  
&emsp;&emsp;Type: [System.String[]](System.String[].md) 
&emsp;&emsp;  
  
*rowLimit*  
&emsp;&emsp;Type: [System.UInt32](System.UInt32.md) 
&emsp;&emsp;  
  
*setAsDefault*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) query*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) personal*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) paged*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.View](Microsoft.SharePoint.Client.View.md)  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
