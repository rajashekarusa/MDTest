String, String, String, String, String, String, Int32# AuthenticationManager.GetADFSUserNameMixedAuthenticatedContext members
Returns a SharePoint on-premises ClientContext for sites secured via ADFS  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetADFSUserNameMixedAuthenticatedContext(String, String, String, String, String, String, Int32)
```
### Parameters
#### siteUrl
Type: [System.String](System.String.md) 
#### 
#### user
Type: [System.String](System.String.md) 
#### 
#### password
Type: [System.String](System.String.md) 
#### 
#### domain
Type: [System.String](System.String.md) 
#### 
#### sts
Type: [System.String](System.String.md) 
#### 
#### idpId
Type: [System.String](System.String.md) 
#### 
#### (optional) logonTokenCacheExpirationWindow
Type: [System.Int32](System.Int32.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)ClientContext to be used by CSOM code
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
