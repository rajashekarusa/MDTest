Tenant, String, String, String, Boolean, Boolean# TenantExtensions.DeployApplicationPackageToAppCatalog members
Adds a package to the tenants app catalog and by default deploys it if the package is a client side package (sppkg)  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  DeployApplicationPackageToAppCatalog(Tenant, String, String, String, Boolean, Boolean)
```
### Parameters
#### tenant
Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
#### 
#### appCatalogSiteUrl
Type: [System.String](System.String.md) 
#### 
#### spPkgName
Type: [System.String](System.String.md) 
#### 
#### spPkgPath
Type: [System.String](System.String.md) 
#### 
#### (optional) autoDeploy
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) overwrite
Type: [System.Boolean](System.Boolean.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ListItem](Microsoft.SharePoint.Client.ListItem.md)The ListItem of the added package row
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
