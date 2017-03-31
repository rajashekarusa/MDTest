Tenant, String, String, String, String, Int32, Int32, Int32, Int32, Int32, UInt32, Boolean, Boolean, Func<TenantOperationMessage, Boolean># TenantExtensions.CreateSiteCollection members
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static guid CreateSiteCollection(Tenant, String, String, String, String, Int32, Int32, Int32, Int32, Int32, UInt32, Boolean, Boolean, Func<TenantOperationMessage, Boolean>)
```
### Parameters
#### tenant
Type: [Microsoft.Online.SharePoint.TenantAdministration.Tenant](Microsoft.Online.SharePoint.TenantAdministration.Tenant.md) 
#### 
#### siteFullUrl
Type: [System.String](System.String.md) 
#### 
#### title
Type: [System.String](System.String.md) 
#### 
#### siteOwnerLogin
Type: [System.String](System.String.md) 
#### 
#### template
Type: [System.String](System.String.md) 
#### 
#### storageMaximumLevel
Type: [System.Int32](System.Int32.md) 
#### 
#### storageWarningLevel
Type: [System.Int32](System.Int32.md) 
#### 
#### timeZoneId
Type: [System.Int32](System.Int32.md) 
#### 
#### userCodeMaximumLevel
Type: [System.Int32](System.Int32.md) 
#### 
#### userCodeWarningLevel
Type: [System.Int32](System.Int32.md) 
#### 
#### lcid
Type: [System.UInt32](System.UInt32.md) 
#### 
#### (optional) removeFromRecycleBin
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) wait
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) timeoutFunction
Type: [System.Func`2<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>](System.Func`2<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>.md) 
#### 
### Return Value
Type: [System.Guid](System.Guid.md)## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
