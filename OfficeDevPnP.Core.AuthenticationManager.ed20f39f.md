# AuthenticationManager.RefreshADFSCertificateMixedAuthenticationContext Method  
Refreshes the SharePoint FedAuth cookie  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public void RefreshADFSCertificateMixedAuthenticationContext(String siteUrl,String serialNumber,String sts,String idpId,Int32 logonTokenCacheExpirationWindow)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*serialNumber*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*sts*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*idpId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) logonTokenCacheExpirationWindow*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md 
)ClientContext to be used by CSOM code

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
