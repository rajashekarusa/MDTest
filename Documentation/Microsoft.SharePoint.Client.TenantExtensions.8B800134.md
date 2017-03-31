# TenantExtensions.DeployApplicationPackageToAppCatalog Method  
Adds a package to the tenants app catalog and by default deploys it if the package is a client side package (sppkg)  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  DeployApplicationPackageToAppCatalog(Tenant tenant,String appCatalogSiteUrl,String spPkgName,String spPkgPath,Boolean autoDeploy,Boolean overwrite)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
&emsp;&emsp;  
  
*appCatalogSiteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*spPkgName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*spPkgPath*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) autoDeploy*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) overwrite*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ListItem](Microsoft.SharePoint.Client.ListItem.md 
)The ListItem of the added package row

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
