# EncryptionUtility
Utility class that support certificate based encryption/decryption  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class EncryptionUtility
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Encrypt(String, String)](EncryptionUtilityEncryptStringString.md) | Encrypt a piece of text based on a given certificate
| [Decrypt(String, String)](EncryptionUtilityDecryptStringString.md) | Decrypt a piece of text based on a given certificate
| [EncryptStringWithDPAPI(Security.SecureString)](EncryptionUtilityEncryptStringWithDPAPISecurity.SecureString.md) | Encrypts a string using the machine's DPAPI
| [DecryptStringWithDPAPI(String)](EncryptionUtilityDecryptStringWithDPAPIString.md) | Decrypts a DPAPI encryped string
| [ToSecureString(String)](EncryptionUtilityToSecureStringString.md) | Converts a string to a SecureString
| [ToInsecureString(Security.SecureString)](EncryptionUtilityToInsecureStringSecurity.SecureString.md) | Converts a SecureString to a "regular" string
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
