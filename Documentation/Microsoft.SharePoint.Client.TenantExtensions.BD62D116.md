Tenant, String, String# TenantExtensions.CheckIfSiteExists members
Returns if a site collection is in a particular status. If the url contains a sub site then returns true is the sub site exists, false if not. 
            Status is irrelevant for sub sites  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean CheckIfSiteExists(Tenant, String, String)
```
### Parameters
#### tenant
Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
#### 
#### siteFullUrl
Type: [System.String](System.String.md) 
#### 
#### status
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [System.Boolean](System.Boolean.md)True if in status, false if not in status
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
