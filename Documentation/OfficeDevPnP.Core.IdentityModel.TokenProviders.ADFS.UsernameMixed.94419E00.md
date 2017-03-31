String, String, String, Uri, String, Int32# UsernameMixed.GetFedAuthCookie members
Performs active authentication against ADFS using the trust/13/usernamemixed ADFS endpoint.  

**Namespace:** [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public net.cookiecontainer GetFedAuthCookie(String, String, String, Uri, String, Int32)
```
### Parameters
#### siteUrl
Type: [System.String](System.String.md) 
#### 
#### userName
Type: [System.String](System.String.md) 
#### 
#### password
Type: [System.String](System.String.md) 
#### 
#### userNameMixed
Type: [System.Uri](System.Uri.md) 
#### 
#### relyingPartyIdentifier
Type: [System.String](System.String.md) 
#### 
#### logonTokenCacheExpirationWindow
Type: [System.Int32](System.Int32.md) 
#### 
### Return Value
Type: [System.Net.CookieContainer](System.Net.CookieContainer.md)A cookiecontainer holding the FedAuth cookie
## See also
- [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)
