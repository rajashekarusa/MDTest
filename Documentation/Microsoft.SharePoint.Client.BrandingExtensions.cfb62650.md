# BrandingExtensions.SetComposedLookByUrl Method  
Retrieves the named composed look, overrides with specified palette, font, background and master page, and then recursively sets the specified values.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetComposedLookByUrl(Web web,String lookName,String paletteServerRelativeUrl,String fontServerRelativeUrl,String backgroundServerRelativeUrl,String masterServerRelativeUrl,Boolean resetSubsitesToInherit,Boolean updateRootOnly)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*lookName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) paletteServerRelativeUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) fontServerRelativeUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) backgroundServerRelativeUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) masterServerRelativeUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) resetSubsitesToInherit*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) updateRootOnly*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md)  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
