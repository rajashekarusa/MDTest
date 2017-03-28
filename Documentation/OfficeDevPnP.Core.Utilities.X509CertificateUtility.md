# X509CertificateUtility
Supporting class for certificate based operations  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class X509CertificateUtility
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [LoadCertificate(Security.Cryptography.X509Certificates.StoreName, Security.Cryptography.X509Certificates.StoreLocation, String)](X509CertificateUtilityLoadCertificateSecurity.Cryptography.X509Certificates.StoreNameSecurity.Cryptography.X509Certificates.StoreLocationString.md) | Loads a certificate from a given certificate store
| [Encrypt(Byte[], Boolean, Security.Cryptography.X509Certificates.X509Certificate2)](X509CertificateUtilityEncryptByte[]BooleanSecurity.Cryptography.X509Certificates.X509Certificate2.md) | Encrypts data based on the RSACryptoServiceProvider
| [Decrypt(Byte[], Boolean, Security.Cryptography.X509Certificates.X509Certificate2)](X509CertificateUtilityDecryptByte[]BooleanSecurity.Cryptography.X509Certificates.X509Certificate2.md) | Decrypts data based on the RSACryptoServiceProvider
| [GetPublicKey(Security.Cryptography.X509Certificates.X509Certificate2)](X509CertificateUtilityGetPublicKeySecurity.Cryptography.X509Certificates.X509Certificate2.md) | Returns the certificate public key
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
