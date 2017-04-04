# TenantExtensions.CreateSiteCollection Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static guid CreateSiteCollection(Tenant tenant, SiteEntity properties, Boolean removeFromRecycleBin, Boolean wait, Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  
&emsp;&emsp;  
  
*properties*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Entities.SiteEntity](OfficeDevPnP.Core.Entities.SiteEntity.md)  
&emsp;&emsp;  
  
*(optional) removeFromRecycleBin*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*(optional) wait*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*(optional) timeoutFunction*  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>  
&emsp;&emsp;  
  
### Return Value
Type: System.Guid  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
