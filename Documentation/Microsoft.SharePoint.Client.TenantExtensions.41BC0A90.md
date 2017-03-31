Tenant, String, String, Nullable<Boolean>, Nullable<SharingCapabilities>, Nullable<Int64>, Nullable<Int64>, Nullable<Double>, Nullable<Double>, Nullable<Boolean>, Boolean, Func<TenantOperationMessage, Boolean># TenantExtensions.SetSiteProperties members
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetSiteProperties(Tenant, String, String, Nullable<Boolean>, Nullable<SharingCapabilities>, Nullable<Int64>, Nullable<Int64>, Nullable<Double>, Nullable<Double>, Nullable<Boolean>, Boolean, Func<TenantOperationMessage, Boolean>)
```
### Parameters
#### tenant
Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
#### 
#### siteFullUrl
Type: [System.String](System.String.md) 
#### 
#### (optional) title
Type: [System.String](System.String.md) 
#### 
#### (optional) allowSelfServiceUpgrade
Type: [System.Nullable`1<System.Boolean>](System.Nullable`1<System.Boolean>.md) 
#### 
#### (optional) sharingCapability
Type: [System.Nullable`1<Microsoft.Online.SharePoint.TenantManagement.SharingCapabilities>](System.Nullable`1<Microsoft.Online.SharePoint.TenantManagement.SharingCapabilities>.md) 
#### 
#### (optional) storageMaximumLevel
Type: [System.Nullable`1<System.Int64>](System.Nullable`1<System.Int64>.md) 
#### 
#### (optional) storageWarningLevel
Type: [System.Nullable`1<System.Int64>](System.Nullable`1<System.Int64>.md) 
#### 
#### (optional) userCodeMaximumLevel
Type: [System.Nullable`1<System.Double>](System.Nullable`1<System.Double>.md) 
#### 
#### (optional) userCodeWarningLevel
Type: [System.Nullable`1<System.Double>](System.Nullable`1<System.Double>.md) 
#### 
#### (optional) noScriptSite
Type: [System.Nullable`1<System.Boolean>](System.Nullable`1<System.Boolean>.md) 
#### 
#### (optional) wait
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) timeoutFunction
Type: [System.Func`2<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>](System.Func`2<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>.md) 
#### 
### Return Value
Type: [System.Void](System.Void.md)## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
