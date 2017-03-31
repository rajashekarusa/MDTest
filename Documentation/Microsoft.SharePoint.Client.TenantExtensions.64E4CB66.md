# TenantExtensions.GetSiteGuidByUrl Method  
Gets the ID of site collection with specified URL  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static guid GetSiteGuidByUrl(Tenant tenant,Uri siteFullUrl)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
&emsp;&emsp;  
  
*siteFullUrl*  
&emsp;&emsp;Type: [System.Uri](System.Uri.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Guid](System.Guid.md 
)The Guid of a site collection or an Guid.Empty if the Site does not exist

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
