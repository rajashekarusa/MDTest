# EncryptionUtility
Utility class that support certificate based encryption/decryption  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class EncryptionUtility
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Encrypt(String, String)](OfficeDevPnP.Core.Utilities.EncryptionUtility.EncryptStringString.md) | Encrypt a piece of text based on a given certificate
| [Decrypt(String, String)](OfficeDevPnP.Core.Utilities.EncryptionUtility.DecryptStringString.md) | Decrypt a piece of text based on a given certificate
| [EncryptStringWithDPAPI(Security.SecureString)](OfficeDevPnP.Core.Utilities.EncryptionUtility.EncryptStringWithDPAPISecurity.SecureString.md) | Encrypts a string using the machine's DPAPI
| [DecryptStringWithDPAPI(String)](OfficeDevPnP.Core.Utilities.EncryptionUtility.DecryptStringWithDPAPIString.md) | Decrypts a DPAPI encryped string
| [ToSecureString(String)](OfficeDevPnP.Core.Utilities.EncryptionUtility.ToSecureStringString.md) | Converts a string to a SecureString
| [ToInsecureString(Security.SecureString)](OfficeDevPnP.Core.Utilities.EncryptionUtility.ToInsecureStringSecurity.SecureString.md) | Converts a SecureString to a "regular" string
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
