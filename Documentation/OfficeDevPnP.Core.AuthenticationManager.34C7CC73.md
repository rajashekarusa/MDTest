String, String, SecureString, String# AuthenticationManager.GetNetworkCredentialAuthenticatedContext members
Returns a SharePoint on-premises / SharePoint Online Dedicated ClientContext object  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetNetworkCredentialAuthenticatedContext(String, String, SecureString, String)
```
### Parameters
#### siteUrl
Type: [System.String](System.String.md) 
#### 
#### user
Type: [System.String](System.String.md) 
#### 
#### password
Type: [System.Security.SecureString](System.Security.SecureString.md) 
#### 
#### domain
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)ClientContext to be used by CSOM code
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
