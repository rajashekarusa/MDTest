# TenantExtensions.DeleteSiteCollection Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean DeleteSiteCollection(Tenant tenant, String siteFullUrl, Boolean useRecycleBin, Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  
*siteFullUrl*  
&emsp;&emsp;Type: System.String  
*useRecycleBin*  
&emsp;&emsp;Type: System.Boolean  
*(optional) timeoutFunction*  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage, System.Boolean>  
### Return Value
Type: System.Boolean  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
