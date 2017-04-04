# SecurityExtensions.GetExternalUsersForSiteTenant Method  
Returns a list all external users for a given site that have at least the viewpages permission  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static list<externaluserentity> GetExternalUsersForSiteTenant(Web web, Uri siteUrl)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Tenant administration web  
  
*siteUrl*  
&emsp;&emsp;Type: System.Uri  
&emsp;&emsp;Url of the site fetch the external users for  
  
### Return Value
Type: System.Collections.Generic.List<OfficeDevPnP.Core.Entities.ExternalUserEntity>  
A list of  objects

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
