# TenantExtensions.SetSiteProperties Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetSiteProperties(Tenant tenant, String siteFullUrl, String title, Nullable<Boolean> allowSelfServiceUpgrade, Nullable<SharingCapabilities> sharingCapability, Nullable<Int64> storageMaximumLevel, Nullable<Int64> storageWarningLevel, Nullable<Double> userCodeMaximumLevel, Nullable<Double> userCodeWarningLevel, Nullable<Boolean> noScriptSite, Boolean wait, Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
#### tenant  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  

#### siteFullUrl  
&emsp;&emsp;Type: System.String  

#### (optional) title  
&emsp;&emsp;Type: System.String  

#### (optional) allowSelfServiceUpgrade  
&emsp;&emsp;Type: System.Nullable<System.Boolean>  

#### (optional) sharingCapability  
&emsp;&emsp;Type: System.Nullable<Microsoft.Online.SharePoint.TenantManagement.SharingCapabilities>  

#### (optional) storageMaximumLevel  
&emsp;&emsp;Type: System.Nullable<System.Int64>  

#### (optional) storageWarningLevel  
&emsp;&emsp;Type: System.Nullable<System.Int64>  

#### (optional) userCodeMaximumLevel  
&emsp;&emsp;Type: System.Nullable<System.Double>  

#### (optional) userCodeWarningLevel  
&emsp;&emsp;Type: System.Nullable<System.Double>  

#### (optional) noScriptSite  
&emsp;&emsp;Type: System.Nullable<System.Boolean>  

#### (optional) wait  
&emsp;&emsp;Type: System.Boolean  

#### (optional) timeoutFunction  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage, System.Boolean>  

### Return Value
Type: void  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
