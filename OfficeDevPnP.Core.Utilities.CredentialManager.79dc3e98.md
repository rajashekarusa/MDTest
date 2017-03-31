# CredentialManager.GetSharePointOnlineCredential Method  
Returns a SharePoint Online Credential given a certain name. Add the credential in the Windows Credential Manager and create a new Windows Credential. Then add a new GENERIC Credential. The name parameter in the method maps to the Internet or network address field.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  GetSharePointOnlineCredential(String name)
```
### Parameters
*name*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.SharePointOnlineCredentials](Microsoft.SharePoint.Client.SharePointOnlineCredentials.md 
)Microsoft.SharePoint.Client.SharePointOnlineCredentials

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
