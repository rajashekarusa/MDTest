# TenantExtensions.SiteExists Method  
Checks if a site collection exists, relies on tenant admin API. Sites that are recycled also return as existing sites  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean SiteExists(Tenant tenant,String siteFullUrl)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
&emsp;&emsp;  
  
*siteFullUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md  
)True if existing, false if not

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
