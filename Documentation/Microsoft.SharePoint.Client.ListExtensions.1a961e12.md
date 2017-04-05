# ListExtensions.CreateView Method  
Create view to existing list  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static View CreateView(List list, String viewName, ViewType viewType, String[] viewFields, UInt32 rowLimit, Boolean setAsDefault, String query, Boolean personal, Boolean paged)
```
### Parameters
*list*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.List  
*viewName*  
&emsp;&emsp;Type: System.String  
*viewType*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.ViewType  
*viewFields*  
&emsp;&emsp;Type: System.String[]  
*rowLimit*  
&emsp;&emsp;Type: System.UInt32  
*setAsDefault*  
&emsp;&emsp;Type: System.Boolean  
*(optional) query*  
&emsp;&emsp;Type: System.String  
*(optional) personal*  
&emsp;&emsp;Type: System.Boolean  
*(optional) paged*  
&emsp;&emsp;Type: System.Boolean  
### Return Value
Type: Microsoft.SharePoint.Client.View  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
