# TenantExtensions.CreateSiteCollection Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static Guid CreateSiteCollection(Tenant tenant, SiteEntity properties, Boolean removeFromRecycleBin, Boolean wait, Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  

*properties*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Entities.SiteEntity](OfficeDevPnP.Core.Entities.SiteEntity.md)  

*(optional) removeFromRecycleBin*  
&emsp;&emsp;Type: System.Boolean  

*(optional) wait*  
&emsp;&emsp;Type: System.Boolean  

*(optional) timeoutFunction*  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage, System.Boolean>  

### Return Value
Type: Guid  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
