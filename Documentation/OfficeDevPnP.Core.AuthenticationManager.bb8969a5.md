# AuthenticationManager.GetAzureADAppOnlyAuthenticatedContext Method  
Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetAzureADAppOnlyAuthenticatedContext(String siteUrl,String clientId,String tenant,String certificatePath,String certificatePassword,AzureEnvironment environment)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Site for which the ClientContext object will be instantiated  
  
*clientId*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The Azure AD Application Client ID  
  
*tenant*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The Azure AD Tenant, e.g. mycompany.onmicrosoft.com  
  
*certificatePath*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The path to the certificate (*.pfx) file on the file system  
  
*certificatePassword*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Password to the certificate  
  
*(optional) environment*  
&emsp;&emsp;Type: OfficeDevPnP.Core.AzureEnvironment  
&emsp;&emsp;SharePoint environment being used  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext]  
Client context object

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)