# WebExtensions.SiteSearch Method  
Returns all site collections that are indexed. In MT the search center, mysite host and contenttype hub are defined as non indexable by default and thus 
            are not returned  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.list`1<officedevpnp.core.entities.siteentity> SiteSearch(Web web)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.SiteEntity>](System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.SiteEntity>.md  
)All site collections

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
