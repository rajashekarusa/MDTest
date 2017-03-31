# CertificateMixed
ADFS Active authentication based on username + password. Uses the trust/13/usernamemixed ADFS endpoint.  

**Namespace:** [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
-- [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.md)
## Syntax
```C#
public class CertificateMixed: BaseProvider
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [CertificateMixed()](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.CertificateMixed.ctor1.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFedAuthCookie(String, String, Uri, String, Int32)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.CertificateMixed.ED2DE986.md) | Performs active authentication against ADFS using the trust/13/usernamemixed ADFS endpoint.
| [RequestToken(String, Uri, String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.CertificateMixed.199A3C96.md) | Returns Generic XML Security Token from ADFS to generated FedAuth
## See also
- [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)
