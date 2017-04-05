# SharePointContextToken.SharePointContextToken members 
  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public SharePointContextToken(String issuer, String audience, DateTime validFrom, DateTime validTo, IEnumerable<JsonWebTokenClaim> claims, SecurityToken issuerToken, JsonWebSecurityToken actorToken)
```
### Parameters
#### issuer  
&emsp;&emsp;Type: System.String  
#### audience  
&emsp;&emsp;Type: System.String  
#### validFrom  
&emsp;&emsp;Type: System.DateTime  
#### validTo  
&emsp;&emsp;Type: System.DateTime  
#### claims  
&emsp;&emsp;Type: System.Collections.Generic.IEnumerable<SharePointPnP.IdentityModel.Extensions.S2S.Tokens.JsonWebTokenClaim>  
#### issuerToken  
&emsp;&emsp;Type: System.IdentityModel.Tokens.SecurityToken  
#### actorToken  
&emsp;&emsp;Type: SharePointPnP.IdentityModel.Extensions.S2S.Tokens.JsonWebSecurityToken  
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
