String, String, String, TokenCache, AzureEnvironment# AuthenticationManager.GetAzureADNativeApplicationAuthenticatedContext members
Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Native Application registered. The user will be prompted for authentication.  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetAzureADNativeApplicationAuthenticatedContext(String, String, String, TokenCache, AzureEnvironment)
```
### Parameters
#### siteUrl
Type: [System.String](System.String.md) 
#### 
#### clientId
Type: [System.String](System.String.md) 
#### 
#### redirectUrl
Type: [System.String](System.String.md) 
#### 
#### (optional) tokenCache
Type: [Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache](Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache.md) 
#### 
#### (optional) environment
Type: [OfficeDevPnP.Core.AzureEnvironment](OfficeDevPnP.Core.AzureEnvironment.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)Client context object
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
