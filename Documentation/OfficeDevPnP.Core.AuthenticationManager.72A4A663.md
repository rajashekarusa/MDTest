String, String, String, String, String, String# AuthenticationManager.GetAppOnlyAuthenticatedContext members
Returns an app only ClientContext object  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetAppOnlyAuthenticatedContext(String, String, String, String, String, String)
```
### Parameters
#### siteUrl
Type: [System.String](System.String.md) 
#### 
#### realm
Type: [System.String](System.String.md) 
#### 
#### appId
Type: [System.String](System.String.md) 
#### 
#### appSecret
Type: [System.String](System.String.md) 
#### 
#### (optional) acsHostUrl
Type: [System.String](System.String.md) 
#### 
#### (optional) globalEndPointPrefix
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)ClientContext to be used by CSOM code
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
