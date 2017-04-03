# X509CertificateUtility.Decrypt Method  
Decrypts data based on the RSACryptoServiceProvider  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static byte[] Decrypt(Byte[] encryptedData,Boolean fOAEP,X509Certificate2 certificate)
```
### Parameters
*encryptedData*  
&emsp;&emsp;Type: System.Byte[]  
&emsp;&emsp;Bytes to decrypt  
  
*fOAEP*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp; true to perform direct System.Security.Cryptography.RSA decryption using OAEP padding  
  
*certificate*  
&emsp;&emsp;Type: System.Security.Cryptography.X509Certificates.X509Certificate2  
&emsp;&emsp;Certificate to use  
  
### Return Value
Type: [System.Byte[]]  
Decrypted bytes

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
