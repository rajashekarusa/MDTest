# X509CertificateUtility.Encrypt Method  
Encrypts data based on the RSACryptoServiceProvider  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static byte[] Encrypt(Byte[] plainData,Boolean fOAEP,X509Certificate2 certificate)
```
### Parameters
*plainData*  
&emsp;&emsp;Type: [System.Byte[]](System.Byte[].md) 
&emsp;&emsp;  
  
*fOAEP*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*certificate*  
&emsp;&emsp;Type: [System.Security.Cryptography.X509Certificates.X509Certificate2](System.Security.Cryptography.X509Certificates.X509Certificate2.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Byte[]](System.Byte[].md 
)Encrypted bytes

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
