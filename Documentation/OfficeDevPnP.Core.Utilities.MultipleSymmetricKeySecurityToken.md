# MultipleSymmetricKeySecurityToken
Represents a security token which contains multiple security keys that are generated using symmetric algorithms.
**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
-- [System.IdentityModel.Tokens.SecurityToken](System.IdentityModel.Tokens.SecurityToken.md)
## Syntax
```C#
public class MultipleSymmetricKeySecurityToken: SecurityToken
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [MultipleSymmetricKeySecurityToken(Collections.Generic.IEnumerable1<Byte[]>)](MultipleSymmetricKeySecurityTokenconstructor1details.md) | 
| [MultipleSymmetricKeySecurityToken(String, Collections.Generic.IEnumerable1<Byte[]>)](MultipleSymmetricKeySecurityTokenconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Id](MultipleSymmetricKeySecurityToken.Id.md) | Gets the unique identifier of the security token.
| [SecurityKeys](MultipleSymmetricKeySecurityToken.SecurityKeys.md) | Gets the cryptographic keys associated with the security token.
| [ValidFrom](MultipleSymmetricKeySecurityToken.ValidFrom.md) | Gets the first instant in time at which this security token is valid.
| [ValidTo](MultipleSymmetricKeySecurityToken.ValidTo.md) | Gets the last instant in time at which this security token is valid.
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [MatchesKeyIdentifierClause(IdentityModel.Tokens.SecurityKeyIdentifierClause)](MultipleSymmetricKeySecurityTokenMatchesKeyIdentifierClauseIdentityModel.Tokens.SecurityKeyIdentifierClause.md) | Returns a value that indicates whether the key identifier for this instance can be resolved to the specified key identifier.
| [CreateSymmetricSecurityKeys(Collections.Generic.IEnumerable1<Byte[]>)](MultipleSymmetricKeySecurityTokenCreateSymmetricSecurityKeysCollections.Generic.IEnumerable1<Byte[]>.md) | 
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
