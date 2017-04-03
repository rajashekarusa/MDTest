# UsernameMixed.GetFedAuthCookie Method  
Performs active authentication against ADFS using the trust/13/usernamemixed ADFS endpoint.  

**Namespace:** [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public net.cookiecontainer GetFedAuthCookie(String siteUrl,String userName,String password,Uri userNameMixed,String relyingPartyIdentifier,Int32 logonTokenCacheExpirationWindow)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Url of the SharePoint site that's secured via ADFS  
  
*userName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Name of the user (e.g. domain\administrator)   
  
*password*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Password of th user  
  
*userNameMixed*  
&emsp;&emsp;Type: System.Uri  
&emsp;&emsp;Uri to the ADFS usernamemixed endpoint  
  
*relyingPartyIdentifier*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Identifier of the ADFS relying party that we're hitting  
  
*logonTokenCacheExpirationWindow*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;  
  
### Return Value
Type: [System.Net.CookieContainer]  
A cookiecontainer holding the FedAuth cookie

## See also
- [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)