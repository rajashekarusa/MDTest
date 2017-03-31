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
| [BaseProvider()](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.ctor1.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [TransformSamlTokenToFedAuth(String, String, String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.EA8C7AA2.md) | Transforms the retrieved SAML token into a FedAuth cookie value by calling into the SharePoint STS
| [WrapInSoapMessage(String, String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.C23CB0F3.md) | Wrap SAML token in RequestSecurityTokenResponse soap message
| [SamlTokenExpiresOn(String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.814B1CC0.md) | Returns the DateTime when then received saml token will expire
| [SamlTokenlifeTime(String)](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.BaseProvider.5FF26A3B.md) | Returns the SAML token life time
## See also
- [OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS](OfficeDevPnP.Core.IdentityModel.TokenProviders.ADFS.md)
