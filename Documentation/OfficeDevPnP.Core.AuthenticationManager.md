# AuthenticationManager
This manager class can be used to obtain a SharePointContext object  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public class AuthenticationManager
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [AuthenticationManager()](OfficeDevPnP.Core.AuthenticationManager.Constructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetSharePointOnlineAuthenticatedContextTenant(String, String, String)](OfficeDevPnP.Core.AuthenticationManager.GetSharePointOnlineAuthenticatedContextTenantStringStringString.md) | Returns a SharePointOnline ClientContext object
| [GetSharePointOnlineAuthenticatedContextTenant(String, String, Security.SecureString)](OfficeDevPnP.Core.AuthenticationManager.GetSharePointOnlineAuthenticatedContextTenantStringStringSecurity.SecureString.md) | Returns a SharePointOnline ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String)](OfficeDevPnP.Core.AuthenticationManager.GetAppOnlyAuthenticatedContextStringStringString.md) | Returns an app only ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAppOnlyAuthenticatedContextStringStringStringAzureEnvironment.md) | Returns an app only ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String, String, String, String)](OfficeDevPnP.Core.AuthenticationManager.GetAppOnlyAuthenticatedContextStringStringStringStringStringString.md) | Returns an app only ClientContext object
| [GetAzureADACSEndPoint(AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADACSEndPointAzureEnvironment.md) | Get's the Azure ASC login end point for the given environment
| [GetAzureADACSEndPointPrefix(AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADACSEndPointPrefixAzureEnvironment.md) | Get's the Azure ACS login end point prefix for the given environment
| [EnsureToken(String, String, String, String, String, String)](OfficeDevPnP.Core.AuthenticationManager.EnsureTokenStringStringStringStringStringString.md) | Ensure that AppAccessToken is filled with a valid string representation of the OAuth AccessToken. This method will launch handle with token cleanup after the token expires
| [GetAccessTokenLease(DateTime)](OfficeDevPnP.Core.AuthenticationManager.GetAccessTokenLeaseDateTime.md) | Get the access token lease time span.
| [GetWebLoginClientContext(String, Drawing.Icon)](OfficeDevPnP.Core.AuthenticationManager.GetWebLoginClientContextStringDrawing.Icon.md) | Returns a SharePoint on-premises / SharePoint Online ClientContext object. Requires claims based authentication with FedAuth cookie.
| [GetNetworkCredentialAuthenticatedContext(String, String, String, String)](OfficeDevPnP.Core.AuthenticationManager.GetNetworkCredentialAuthenticatedContextStringStringStringString.md) | Returns a SharePoint on-premises / SharePoint Online Dedicated ClientContext object
| [GetNetworkCredentialAuthenticatedContext(String, String, Security.SecureString, String)](OfficeDevPnP.Core.AuthenticationManager.GetNetworkCredentialAuthenticatedContextStringStringSecurity.SecureStringString.md) | Returns a SharePoint on-premises / SharePoint Online Dedicated ClientContext object
| [GetAzureADNativeApplicationAuthenticatedContext(String, String, String, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADNativeApplicationAuthenticatedContextStringStringStringMicrosoft.IdentityModel.Clients.ActiveDirectory.TokenCacheAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Native Application registered. The user will be prompted for authentication.
| [GetAzureADNativeApplicationAuthenticatedContext(String, String, Uri, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADNativeApplicationAuthenticatedContextStringStringUriMicrosoft.IdentityModel.Clients.ActiveDirectory.TokenCacheAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Native Application registered. The user will be prompted for authentication.
| [GetAzureADWebApplicationAuthenticatedContext(String, Func<String,String>)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADWebApplicationAuthenticatedContextStringFunc<String,String>.md) | 
| [GetAzureADAccessTokenAuthenticatedContext(String, String)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADAccessTokenAuthenticatedContextStringString.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Web Application registered. The user will not be prompted for authentication, the current user's authentication context will be used by leveraging an explicit OAuth 2.0 Access Token value.
| [clientContext_NativeApplicationExecutingWebRequest(Object, Microsoft.SharePoint.Client.WebRequestEventArgs)](OfficeDevPnP.Core.AuthenticationManager.clientContext_NativeApplicationExecutingWebRequestObjectMicrosoft.SharePoint.Client.WebRequestEventArgs.md) | 
| [AcquireNativeApplicationTokenAsync(String, String)](OfficeDevPnP.Core.AuthenticationManager.AcquireNativeApplicationTokenAsyncStringString.md) | 
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, Security.Cryptography.X509Certificates.StoreName, Security.Cryptography.X509Certificates.StoreLocation, String, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADAppOnlyAuthenticatedContextStringStringStringSecurity.Cryptography.X509Certificates.StoreNameSecurity.Cryptography.X509Certificates.StoreLocationStringAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, String, String, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADAppOnlyAuthenticatedContextStringStringStringStringStringAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, String, Security.SecureString, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADAppOnlyAuthenticatedContextStringStringStringStringSecurity.SecureStringAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, Security.Cryptography.X509Certificates.X509Certificate2, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADAppOnlyAuthenticatedContextStringStringStringSecurity.Cryptography.X509Certificates.X509Certificate2AzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADLoginEndPoint(AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.GetAzureADLoginEndPointAzureEnvironment.md) | Get's the Azure AD login end point for the given environment
| [GetADFSUserNameMixedAuthenticatedContext(String, String, String, String, String, String, Int32)](OfficeDevPnP.Core.AuthenticationManager.GetADFSUserNameMixedAuthenticatedContextStringStringStringStringStringStringInt32.md) | Returns a SharePoint on-premises ClientContext for sites secured via ADFS
| [RefreshADFSUserNameMixedAuthenticatedContext(String, String, String, String, String, String, Int32)](OfficeDevPnP.Core.AuthenticationManager.RefreshADFSUserNameMixedAuthenticatedContextStringStringStringStringStringStringInt32.md) | Refreshes the SharePoint FedAuth cookie
| [GetADFSCertificateMixedAuthenticationContext(String, String, String, String, Int32)](OfficeDevPnP.Core.AuthenticationManager.GetADFSCertificateMixedAuthenticationContextStringStringStringStringInt32.md) | Returns a SharePoint on-premises ClientContext for sites secured via ADFS
| [RefreshADFSCertificateMixedAuthenticationContext(String, String, String, String, Int32)](OfficeDevPnP.Core.AuthenticationManager.RefreshADFSCertificateMixedAuthenticationContextStringStringStringStringInt32.md) | Refreshes the SharePoint FedAuth cookie
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
