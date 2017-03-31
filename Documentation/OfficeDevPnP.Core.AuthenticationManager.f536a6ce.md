# AuthenticationManager.GetAzureADNativeApplicationAuthenticatedContext Method  
Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Native Application registered. The user will be prompted for authentication.  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetAzureADNativeApplicationAuthenticatedContext(String siteUrl,String clientId,Uri redirectUri,TokenCache tokenCache,AzureEnvironment environment)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*clientId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*redirectUri*  
&emsp;&emsp;Type: [System.Uri](System.Uri.md) 
&emsp;&emsp;  
  
*(optional) tokenCache*  
&emsp;&emsp;Type: [Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache](Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.md) 
&emsp;&emsp;  
  
*(optional) environment*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.AzureEnvironment](OfficeDevPnP.Core.AzureEnvironment.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md 
)Client context object

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
