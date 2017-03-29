# BaseProvider
Base class for active SAML based authentication  

**Namespace:** [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public class BaseProvider
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [BaseProvider()](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.Constructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [TransformSamlTokenToFedAuth(String, String, String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.TransformSamlTokenToFedAuthStringStringString.md) | Transforms the retrieved SAML token into a FedAuth cookie value by calling into the SharePoint STS
| [WrapInSoapMessage(String, String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.WrapInSoapMessageStringString.md) | Wrap SAML token in RequestSecurityTokenResponse soap message
| [SamlTokenExpiresOn(String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.SamlTokenExpiresOnString.md) | Returns the DateTime when then received saml token will expire
| [SamlTokenlifeTime(String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.SamlTokenlifeTimeString.md) | Returns the SAML token life time
## See also
- [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)
