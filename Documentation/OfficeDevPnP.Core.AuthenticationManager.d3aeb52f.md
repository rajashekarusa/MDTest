# AuthenticationManager.GetNetworkCredentialAuthenticatedContext Method  
Returns a SharePoint on-premises / SharePoint Online Dedicated ClientContext object  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetNetworkCredentialAuthenticatedContext(String siteUrl,String user,String password,String domain)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*user*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*password*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*domain*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)  
ClientContext to be used by CSOM code

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
