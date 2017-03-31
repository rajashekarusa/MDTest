# TenantExtensions.DeleteSiteCollectionFromRecycleBin Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean DeleteSiteCollectionFromRecycleBin(Tenant tenant,String siteFullUrl,Boolean wait,Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
&emsp;&emsp;  
  
*siteFullUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) wait*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) timeoutFunction*  
&emsp;&emsp;Type: [System.Func<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>](System.Func<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md 
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
