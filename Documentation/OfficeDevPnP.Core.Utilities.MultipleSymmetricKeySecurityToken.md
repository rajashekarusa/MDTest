# MultipleSymmetricKeySecurityToken
Represents a security token which contains multiple security keys that are generated using symmetric algorithms.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
-- [System.IdentityModel.Tokens.SecurityToken](System.IdentityModel.Tokens.SecurityToken.md)
## Syntax
```C#
public class MultipleSymmetricKeySecurityToken: SecurityToken
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [MultipleSymmetricKeySecurityToken(IEnumerable<Byte[]>)](OfficeDevPnP.Core.Utilities.MultipleSymmetricKeySecurityToken.Constructor1details.md) | 
| [MultipleSymmetricKeySecurityToken(String, IEnumerable<Byte[]>)](OfficeDevPnP.Core.Utilities.MultipleSymmetricKeySecurityToken.Constructor2details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Id](OfficeDevPnP.Core.Utilities.MultipleSymmetricKeySecurityToken.Id.md) | Gets the unique identifier of the security token.
| [SecurityKeys](OfficeDevPnP.Core.Utilities.MultipleSymmetricKeySecurityToken.SecurityKeys.md) | Gets the cryptographic keys associated with the security token.
| [ValidFrom](OfficeDevPnP.Core.Utilities.MultipleSymmetricKeySecurityToken.ValidFrom.md) | Gets the first instant in time at which this security token is valid.
| [ValidTo](OfficeDevPnP.Core.Utilities.MultipleSymmetricKeySecurityToken.ValidTo.md) | Gets the last instant in time at which this security token is valid.
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [MatchesKeyIdentifierClause(IdentityModel.Tokens.SecurityKeyIdentifierClause)](OfficeDevPnP.Core.Utilities.MultipleSymmetricKeySecurityToken.MatchesKeyIdentifierClauseIdentityModel.Tokens.SecurityKeyIdentifierClause.md) | Returns a value that indicates whether the key identifier for this instance can be resolved to the specified key identifier.
| [CreateSymmetricSecurityKeys(Collections.Generic.IEnumerable<Byte[]>)](OfficeDevPnP.Core.Utilities.MultipleSymmetricKeySecurityToken.CreateSymmetricSecurityKeysCollections.Generic.IEnumerable<Byte[]>.md) | 
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
