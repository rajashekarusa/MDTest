# TimerJob.UseAzureADAppOnlyAuthentication Method  
Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType 
            to AuthenticationType.AzureADAppOnly  

**Namespace:** [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public void UseAzureADAppOnlyAuthentication(String clientId,String azureTenant,String certificatePath,String certificatePassword)
```
### Parameters
*clientId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*azureTenant*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*certificatePath*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*certificatePassword*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md  
)
## See also
- [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)
