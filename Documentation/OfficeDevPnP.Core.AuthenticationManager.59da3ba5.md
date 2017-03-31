# AuthenticationManager.GetADFSCertificateMixedAuthenticationContext Method  
Returns a SharePoint on-premises ClientContext for sites secured via ADFS  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetADFSCertificateMixedAuthenticationContext(String siteUrl,String serialNumber,String sts,String idpId,Int32 logonTokenCacheExpirationWindow)
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
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md 
)ClientContext to be used by CSOM code

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
