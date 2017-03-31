String, String, String, String, SecureString, AzureEnvironment# AuthenticationManager.GetAzureADAppOnlyAuthenticatedContext members
Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetAzureADAppOnlyAuthenticatedContext(String, String, String, String, SecureString, AzureEnvironment)
```
### Parameters
#### siteUrl
Type: [System.String](System.String.md) 
#### 
#### clientId
Type: [System.String](System.String.md) 
#### 
#### tenant
Type: [System.String](System.String.md) 
#### 
#### certificatePath
Type: [System.String](System.String.md) 
#### 
#### certificatePassword
Type: [System.Security.SecureString](System.Security.SecureString.md) 
#### 
#### (optional) environment
Type: [OfficeDevPnP.Core.AzureEnvironment](OfficeDevPnP.Core.AzureEnvironment.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)Client context object
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
