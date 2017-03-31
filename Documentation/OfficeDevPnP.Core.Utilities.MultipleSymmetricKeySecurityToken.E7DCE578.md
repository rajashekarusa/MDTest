SecurityKeyIdentifierClause# MultipleSymmetricKeySecurityToken.MatchesKeyIdentifierClause members
Returns a value that indicates whether the key identifier for this instance can be resolved to the specified key identifier.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public boolean MatchesKeyIdentifierClause(SecurityKeyIdentifierClause)
```
### Parameters
#### keyIdentifierClause
Type: [System.IdentityModel.Tokens.SecurityKeyIdentifierClause](System.IdentityModel.Tokens.SecurityKeyIdentifierClause.md) 
#### 
### Return Value
Type: [System.Boolean](System.Boolean.md)true if keyIdentifierClause is a SecurityKeyIdentifierClause and it has the same unique identifier as the Id property; otherwise, false.
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
