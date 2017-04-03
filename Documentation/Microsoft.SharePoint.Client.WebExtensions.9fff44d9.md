# WebExtensions.SiteSearchScopedByTitle Method  
Returns all site collection that match with the provided title  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.list<officedevpnp.core.entities.siteentity> SiteSearchScopedByTitle(Web web,String siteTitle)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  
  
*siteTitle*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Title of the site to search for  
  
### Return Value
Type: System.Collections.Generic.List<OfficeDevPnP.Core.Entities.SiteEntity>  
All found site collections

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
