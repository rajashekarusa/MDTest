# AuthenticationManager.GetAzureADAppOnlyAuthenticatedContext Method  
Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetAzureADAppOnlyAuthenticatedContext(String siteUrl,String clientId,String tenant,String certificatePath,SecureString certificatePassword,AzureEnvironment environment)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*clientId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*tenant*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*certificatePath*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*certificatePassword*  
&emsp;&emsp;Type: [System.Security.SecureString](System.Security.SecureString.md) 
&emsp;&emsp;  
  
*(optional) environment*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.AzureEnvironment](OfficeDevPnP.Core.AzureEnvironment.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md  
)Client context object

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
