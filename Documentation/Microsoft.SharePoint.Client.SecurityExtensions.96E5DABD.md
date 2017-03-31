# SecurityExtensions.GetExternalUsersForSiteTenant Method  
Returns a list all external users for a given site that have at least the viewpages permission  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.list`1<officedevpnp.core.entities.externaluserentity> GetExternalUsersForSiteTenant(Web web,Uri siteUrl)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*siteUrl*  
&emsp;&emsp;Type: [System.Uri](System.Uri.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.ExternalUserEntity>](System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.ExternalUserEntity>.md 
)A list of  objects

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
