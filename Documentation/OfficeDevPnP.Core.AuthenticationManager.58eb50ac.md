# AuthenticationManager.GetAppOnlyAuthenticatedContext Method  
Returns an app only ClientContext object  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetAppOnlyAuthenticatedContext(String siteUrl,String appId,String appSecret,AzureEnvironment environment)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*appId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*appSecret*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) environment*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.AzureEnvironment](OfficeDevPnP.Core.AzureEnvironment.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md  
)ClientContext to be used by CSOM code

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
