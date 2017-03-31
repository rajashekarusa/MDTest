# CertificateMixed.GetFedAuthCookie Method  
Performs active authentication against ADFS using the trust/13/usernamemixed ADFS endpoint.  

**Namespace:** [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public net.cookiecontainer GetFedAuthCookie(String siteUrl,String serialNumber,Uri certificateMixed,String relyingPartyIdentifier,Int32 logonTokenCacheExpirationWindow)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*serialNumber*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*certificateMixed*  
&emsp;&emsp;Type: [System.Uri](System.Uri.md) 
&emsp;&emsp;  
  
*relyingPartyIdentifier*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*logonTokenCacheExpirationWindow*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Net.CookieContainer](System.Net.CookieContainer.md 
)A cookiecontainer holding the FedAuth cookie

## See also
- [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)
