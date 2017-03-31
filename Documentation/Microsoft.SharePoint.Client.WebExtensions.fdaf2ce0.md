# WebExtensions.SiteSearch Method  
Returns the site collections that comply with the passed keyword query  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.list`1<officedevpnp.core.entities.siteentity> SiteSearch(Web web,String keywordQueryValue,Boolean trimDuplicates)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*keywordQueryValue*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) trimDuplicates*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.SiteEntity>](System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.SiteEntity>.md  
)All found site collections

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
