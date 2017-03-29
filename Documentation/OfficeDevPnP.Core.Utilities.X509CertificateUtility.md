# X509CertificateUtility
Supporting class for certificate based operations  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class X509CertificateUtility
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [LoadCertificate(Security.Cryptography.X509Certificates.StoreName, Security.Cryptography.X509Certificates.StoreLocation, String)](OfficeDevPnP.Core.Utilities.X509CertificateUtility.LoadCertificateSecurity.Cryptography.X509Certificates.StoreNameSecurity.Cryptography.X509Certificates.StoreLocationString.md) | Loads a certificate from a given certificate store
| [Encrypt(Byte[], Boolean, Security.Cryptography.X509Certificates.X509Certificate2)](OfficeDevPnP.Core.Utilities.X509CertificateUtility.EncryptByte[]BooleanSecurity.Cryptography.X509Certificates.X509Certificate2.md) | Encrypts data based on the RSACryptoServiceProvider
| [Decrypt(Byte[], Boolean, Security.Cryptography.X509Certificates.X509Certificate2)](OfficeDevPnP.Core.Utilities.X509CertificateUtility.DecryptByte[]BooleanSecurity.Cryptography.X509Certificates.X509Certificate2.md) | Decrypts data based on the RSACryptoServiceProvider
| [GetPublicKey(Security.Cryptography.X509Certificates.X509Certificate2)](OfficeDevPnP.Core.Utilities.X509CertificateUtility.GetPublicKeySecurity.Cryptography.X509Certificates.X509Certificate2.md) | Returns the certificate public key
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
