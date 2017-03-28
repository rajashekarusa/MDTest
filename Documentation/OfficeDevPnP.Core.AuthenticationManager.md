# AuthenticationManager
This manager class can be used to obtain a SharePointContext object
**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class AuthenticationManager
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [AuthenticationManager()](AuthenticationManagerconstructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetSharePointOnlineAuthenticatedContextTenant(String, String, String)](AuthenticationManagerGetSharePointOnlineAuthenticatedContextTenantStringStringString.md) | Returns a SharePointOnline ClientContext object
| [GetSharePointOnlineAuthenticatedContextTenant(String, String, Security.SecureString)](AuthenticationManagerGetSharePointOnlineAuthenticatedContextTenantStringStringSecurity.SecureString.md) | Returns a SharePointOnline ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String)](AuthenticationManagerGetAppOnlyAuthenticatedContextStringStringString.md) | Returns an app only ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String, AzureEnvironment)](AuthenticationManagerGetAppOnlyAuthenticatedContextStringStringStringAzureEnvironment.md) | Returns an app only ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String, String, String, String)](AuthenticationManagerGetAppOnlyAuthenticatedContextStringStringStringStringStringString.md) | Returns an app only ClientContext object
| [GetAzureADACSEndPoint(AzureEnvironment)](AuthenticationManagerGetAzureADACSEndPointAzureEnvironment.md) | Get's the Azure ASC login end point for the given environment
| [GetAzureADACSEndPointPrefix(AzureEnvironment)](AuthenticationManagerGetAzureADACSEndPointPrefixAzureEnvironment.md) | Get's the Azure ACS login end point prefix for the given environment
| [EnsureToken(String, String, String, String, String, String)](AuthenticationManagerEnsureTokenStringStringStringStringStringString.md) | Ensure that AppAccessToken is filled with a valid string representation of the OAuth AccessToken. This method will launch handle with token cleanup after the token expires
| [GetAccessTokenLease(DateTime)](AuthenticationManagerGetAccessTokenLeaseDateTime.md) | Get the access token lease time span.
| [GetWebLoginClientContext(String, Drawing.Icon)](AuthenticationManagerGetWebLoginClientContextStringDrawing.Icon.md) | Returns a SharePoint on-premises / SharePoint Online ClientContext object. Requires claims based authentication with FedAuth cookie.
| [GetNetworkCredentialAuthenticatedContext(String, String, String, String)](AuthenticationManagerGetNetworkCredentialAuthenticatedContextStringStringStringString.md) | Returns a SharePoint on-premises / SharePoint Online Dedicated ClientContext object
| [GetNetworkCredentialAuthenticatedContext(String, String, Security.SecureString, String)](AuthenticationManagerGetNetworkCredentialAuthenticatedContextStringStringSecurity.SecureStringString.md) | Returns a SharePoint on-premises / SharePoint Online Dedicated ClientContext object
| [GetAzureADNativeApplicationAuthenticatedContext(String, String, String, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache, AzureEnvironment)](AuthenticationManagerGetAzureADNativeApplicationAuthenticatedContextStringStringStringMicrosoft.IdentityModel.Clients.ActiveDirectory.TokenCacheAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Native Application registered. The user will be prompted for authentication.
| [GetAzureADNativeApplicationAuthenticatedContext(String, String, Uri, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache, AzureEnvironment)](AuthenticationManagerGetAzureADNativeApplicationAuthenticatedContextStringStringUriMicrosoft.IdentityModel.Clients.ActiveDirectory.TokenCacheAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Native Application registered. The user will be prompted for authentication.
| [GetAzureADWebApplicationAuthenticatedContext(String, Func2<String,String>)](AuthenticationManagerGetAzureADWebApplicationAuthenticatedContextStringFunc2<String,String>.md) | 
| [GetAzureADAccessTokenAuthenticatedContext(String, String)](AuthenticationManagerGetAzureADAccessTokenAuthenticatedContextStringString.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Web Application registered. The user will not be prompted for authentication, the current user's authentication context will be used by leveraging an explicit OAuth 2.0 Access Token value.
| [clientContext_NativeApplicationExecutingWebRequest(Object, Microsoft.SharePoint.Client.WebRequestEventArgs)](AuthenticationManagerclientContext_NativeApplicationExecutingWebRequestObjectMicrosoft.SharePoint.Client.WebRequestEventArgs.md) | 
| [AcquireNativeApplicationTokenAsync(String, String)](AuthenticationManagerAcquireNativeApplicationTokenAsyncStringString.md) | 
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, Security.Cryptography.X509Certificates.StoreName, Security.Cryptography.X509Certificates.StoreLocation, String, AzureEnvironment)](AuthenticationManagerGetAzureADAppOnlyAuthenticatedContextStringStringStringSecurity.Cryptography.X509Certificates.StoreNameSecurity.Cryptography.X509Certificates.StoreLocationStringAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, String, String, AzureEnvironment)](AuthenticationManagerGetAzureADAppOnlyAuthenticatedContextStringStringStringStringStringAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, String, Security.SecureString, AzureEnvironment)](AuthenticationManagerGetAzureADAppOnlyAuthenticatedContextStringStringStringStringSecurity.SecureStringAzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, Security.Cryptography.X509Certificates.X509Certificate2, AzureEnvironment)](AuthenticationManagerGetAzureADAppOnlyAuthenticatedContextStringStringStringSecurity.Cryptography.X509Certificates.X509Certificate2AzureEnvironment.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADLoginEndPoint(AzureEnvironment)](AuthenticationManagerGetAzureADLoginEndPointAzureEnvironment.md) | Get's the Azure AD login end point for the given environment
| [GetADFSUserNameMixedAuthenticatedContext(String, String, String, String, String, String, Int32)](AuthenticationManagerGetADFSUserNameMixedAuthenticatedContextStringStringStringStringStringStringInt32.md) | Returns a SharePoint on-premises ClientContext for sites secured via ADFS
| [RefreshADFSUserNameMixedAuthenticatedContext(String, String, String, String, String, String, Int32)](AuthenticationManagerRefreshADFSUserNameMixedAuthenticatedContextStringStringStringStringStringStringInt32.md) | Refreshes the SharePoint FedAuth cookie
| [GetADFSCertificateMixedAuthenticationContext(String, String, String, String, Int32)](AuthenticationManagerGetADFSCertificateMixedAuthenticationContextStringStringStringStringInt32.md) | Returns a SharePoint on-premises ClientContext for sites secured via ADFS
| [RefreshADFSCertificateMixedAuthenticationContext(String, String, String, String, Int32)](AuthenticationManagerRefreshADFSCertificateMixedAuthenticationContextStringStringStringStringInt32.md) | Refreshes the SharePoint FedAuth cookie
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
