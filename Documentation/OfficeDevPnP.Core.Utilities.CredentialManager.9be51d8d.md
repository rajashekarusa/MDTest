# CredentialManager.GetCredential Method  
Returns a NetworkCredential given a certain name. Add the credential in the Windows Credential Manager and create a new Windows Credential. Then add a new GENERIC Credential. The name parameter in the method maps to the Internet or network address field.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static NetworkCredential GetCredential(String name)
```
### Parameters
*name*  
&emsp;&emsp;Type: System.String  

### Return Value
Type: NetworkCredential  
System.Net.NetworkCredential

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
