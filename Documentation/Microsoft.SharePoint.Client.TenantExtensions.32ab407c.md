# TenantExtensions.DeleteSiteCollection Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static System.Boolean DeleteSiteCollection(Tenant tenant, String siteFullUrl, Boolean useRecycleBin, Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  
&emsp;&emsp;  
  
*siteFullUrl*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*useRecycleBin*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*(optional) timeoutFunction*  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>  
&emsp;&emsp;  
  
### Return Value
Type: System.Boolean  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
