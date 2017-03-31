# X509CertificateUtility.LoadCertificate Method  
Loads a certificate from a given certificate store  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static security.cryptography.x509certificates.x509certificate2 LoadCertificate(StoreName storeName,StoreLocation storeLocation,String thumbprint)
```
### Parameters
*storeName*  
&emsp;&emsp;Type: [System.Security.Cryptography.X509Certificates.StoreName](System.Security.Cryptography.X509Certificates.StoreName.md) 
&emsp;&emsp;  
  
*storeLocation*  
&emsp;&emsp;Type: [System.Security.Cryptography.X509Certificates.StoreLocation](System.Security.Cryptography.X509Certificates.StoreLocation.md) 
&emsp;&emsp;  
  
*thumbprint*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Security.Cryptography.X509Certificates.X509Certificate2](System.Security.Cryptography.X509Certificates.X509Certificate2.md 
)An  certificate

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
