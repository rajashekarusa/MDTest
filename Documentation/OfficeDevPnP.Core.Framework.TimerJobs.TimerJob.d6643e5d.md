# TimerJob.UseAzureADAppOnlyAuthentication Method  
Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType 
            to AuthenticationType.AzureADAppOnly  

**Namespace:** [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public void UseAzureADAppOnlyAuthentication(String clientId,String azureTenant,X509Certificate2 certificate)
```
### Parameters
*clientId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*azureTenant*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*certificate*  
&emsp;&emsp;Type: [System.Security.Cryptography.X509Certificates.X509Certificate2](System.Security.Cryptography.X509Certificates.X509Certificate2.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md)  

## See also
- [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)
