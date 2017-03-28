# BaseProvider
Base class for active SAML based authentication  
**Namespace:** [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class BaseProvider
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [BaseProvider()](BaseProviderconstructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [TransformSamlTokenToFedAuth(String, String, String)](BaseProviderTransformSamlTokenToFedAuthStringStringString.md) | Transforms the retrieved SAML token into a FedAuth cookie value by calling into the SharePoint STS
| [WrapInSoapMessage(String, String)](BaseProviderWrapInSoapMessageStringString.md) | Wrap SAML token in RequestSecurityTokenResponse soap message
| [SamlTokenExpiresOn(String)](BaseProviderSamlTokenExpiresOnString.md) | Returns the DateTime when then received saml token will expire
| [SamlTokenlifeTime(String)](BaseProviderSamlTokenlifeTimeString.md) | Returns the SAML token life time
## See also
- [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)
