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
| [AuthenticationManager()](OfficeDevPnP.Core.AuthenticationManager.ctor1.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetSharePointOnlineAuthenticatedContextTenant(String, String, String)](OfficeDevPnP.Core.AuthenticationManager.E8FA5BC2.md) | Returns a SharePointOnline ClientContext object
| [GetSharePointOnlineAuthenticatedContextTenant(String, String, SecureString)](OfficeDevPnP.Core.AuthenticationManager.25CC8181.md) | Returns a SharePointOnline ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String)](OfficeDevPnP.Core.AuthenticationManager.D811A03E.md) | Returns an app only ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.58EB50AC.md) | Returns an app only ClientContext object
| [GetAppOnlyAuthenticatedContext(String, String, String, String, String, String)](OfficeDevPnP.Core.AuthenticationManager.72A4A663.md) | Returns an app only ClientContext object
| [GetAzureADACSEndPoint(AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.6F718DBE.md) | Get's the Azure ASC login end point for the given environment
| [GetAzureADACSEndPointPrefix(AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.7B94031F.md) | Get's the Azure ACS login end point prefix for the given environment
| [EnsureToken(String, String, String, String, String, String)](OfficeDevPnP.Core.AuthenticationManager.DBDB3229.md) | Ensure that AppAccessToken is filled with a valid string representation of the OAuth AccessToken. This method will launch handle with token cleanup after the token expires
| [GetAccessTokenLease(DateTime)](OfficeDevPnP.Core.AuthenticationManager.DA4DBA28.md) | Get the access token lease time span.
| [GetWebLoginClientContext(String, Icon)](OfficeDevPnP.Core.AuthenticationManager.99809936.md) | Returns a SharePoint on-premises / SharePoint Online ClientContext object. Requires claims based authentication with FedAuth cookie.
| [GetNetworkCredentialAuthenticatedContext(String, String, String, String)](OfficeDevPnP.Core.AuthenticationManager.D3AEB52F.md) | Returns a SharePoint on-premises / SharePoint Online Dedicated ClientContext object
| [GetNetworkCredentialAuthenticatedContext(String, String, SecureString, String)](OfficeDevPnP.Core.AuthenticationManager.34C7CC73.md) | Returns a SharePoint on-premises / SharePoint Online Dedicated ClientContext object
| [GetAzureADNativeApplicationAuthenticatedContext(String, String, String, TokenCache, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.4F3FFDAA.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Native Application registered. The user will be prompted for authentication.
| [GetAzureADNativeApplicationAuthenticatedContext(String, String, Uri, TokenCache, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.F536A6CE.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Native Application registered. The user will be prompted for authentication.
| [GetAzureADWebApplicationAuthenticatedContext(String, Func<String, String>)](OfficeDevPnP.Core.AuthenticationManager.5F304637.md) | 
| [GetAzureADAccessTokenAuthenticatedContext(String, String)](OfficeDevPnP.Core.AuthenticationManager.16EFABF6.md) | Returns a SharePoint ClientContext using Azure Active Directory authentication. This requires that you have a Azure AD Web Application registered. The user will not be prompted for authentication, the current user's authentication context will be used by leveraging an explicit OAuth 2.0 Access Token value.
| [clientContext_NativeApplicationExecutingWebRequest(Object, WebRequestEventArgs)](OfficeDevPnP.Core.AuthenticationManager.418E2A2.md) | 
| [AcquireNativeApplicationTokenAsync(String, String)](OfficeDevPnP.Core.AuthenticationManager.8A948D07.md) | 
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, StoreName, StoreLocation, String, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.9589D33.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, String, String, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.BB8969A5.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, String, SecureString, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.67FBA39E.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADAppOnlyAuthenticatedContext(String, String, String, X509Certificate2, AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.AB64AE22.md) | Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.
| [GetAzureADLoginEndPoint(AzureEnvironment)](OfficeDevPnP.Core.AuthenticationManager.13A3DC47.md) | Get's the Azure AD login end point for the given environment
| [GetADFSUserNameMixedAuthenticatedContext(String, String, String, String, String, String, Int32)](OfficeDevPnP.Core.AuthenticationManager.375FA96B.md) | Returns a SharePoint on-premises ClientContext for sites secured via ADFS
| [RefreshADFSUserNameMixedAuthenticatedContext(String, String, String, String, String, String, Int32)](OfficeDevPnP.Core.AuthenticationManager.23B7C2D8.md) | Refreshes the SharePoint FedAuth cookie
| [GetADFSCertificateMixedAuthenticationContext(String, String, String, String, Int32)](OfficeDevPnP.Core.AuthenticationManager.59DA3BA5.md) | Returns a SharePoint on-premises ClientContext for sites secured via ADFS
| [RefreshADFSCertificateMixedAuthenticationContext(String, String, String, String, Int32)](OfficeDevPnP.Core.AuthenticationManager.ED20F39F.md) | Refreshes the SharePoint FedAuth cookie
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
