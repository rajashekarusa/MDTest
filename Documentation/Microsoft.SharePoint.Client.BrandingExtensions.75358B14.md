# BrandingExtensions.SetCustomMasterPageByUrl Method  
Set Custom master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetCustomMasterPageByUrl(Web web,String masterPageServerRelativeUrl,Boolean resetSubsitesToInherit,Boolean updateRootOnly)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*masterPageServerRelativeUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) resetSubsitesToInherit*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) updateRootOnly*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md 
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
