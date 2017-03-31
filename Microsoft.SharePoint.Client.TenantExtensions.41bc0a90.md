# TenantExtensions.SetSiteProperties Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetSiteProperties(Tenant tenant,String siteFullUrl,String title,Nullable<Boolean> allowSelfServiceUpgrade,Nullable<SharingCapabilities> sharingCapability,Nullable<Int64> storageMaximumLevel,Nullable<Int64> storageWarningLevel,Nullable<Double> userCodeMaximumLevel,Nullable<Double> userCodeWarningLevel,Nullable<Boolean> noScriptSite,Boolean wait,Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
&emsp;&emsp;  
  
*siteFullUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) title*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) allowSelfServiceUpgrade*  
&emsp;&emsp;Type: [System.Nullable<System.Boolean>](System.Nullable<System.Boolean>.md) 
&emsp;&emsp;  
  
*(optional) sharingCapability*  
&emsp;&emsp;Type: [System.Nullable<Microsoft.Online.SharePoint.TenantManagement.SharingCapabilities>](System.Nullable<Microsoft.Online.SharePoint.TenantManagement.SharingCapabilities>.md) 
&emsp;&emsp;  
  
*(optional) storageMaximumLevel*  
&emsp;&emsp;Type: [System.Nullable<System.Int64>](System.Nullable<System.Int64>.md) 
&emsp;&emsp;  
  
*(optional) storageWarningLevel*  
&emsp;&emsp;Type: [System.Nullable<System.Int64>](System.Nullable<System.Int64>.md) 
&emsp;&emsp;  
  
*(optional) userCodeMaximumLevel*  
&emsp;&emsp;Type: [System.Nullable<System.Double>](System.Nullable<System.Double>.md) 
&emsp;&emsp;  
  
*(optional) userCodeWarningLevel*  
&emsp;&emsp;Type: [System.Nullable<System.Double>](System.Nullable<System.Double>.md) 
&emsp;&emsp;  
  
*(optional) noScriptSite*  
&emsp;&emsp;Type: [System.Nullable<System.Boolean>](System.Nullable<System.Boolean>.md) 
&emsp;&emsp;  
  
*(optional) wait*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) timeoutFunction*  
&emsp;&emsp;Type: [System.Func<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>](System.Func<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md 
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)