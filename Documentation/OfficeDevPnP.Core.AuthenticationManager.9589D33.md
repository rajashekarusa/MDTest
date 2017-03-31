String, String, String, StoreName, StoreLocation, String, AzureEnvironment# AuthenticationManager.GetAzureADAppOnlyAuthenticatedContext members
Returns a SharePoint ClientContext using Azure Active Directory App Only Authentication. This requires that you have a certificated created, and updated the key credentials key in the application manifest in the azure AD accordingly.  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  GetAzureADAppOnlyAuthenticatedContext(String, String, String, StoreName, StoreLocation, String, AzureEnvironment)
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
#### storeName
Type: [System.Security.Cryptography.X509Certificates.StoreName](System.Security.Cryptography.X509Certificates.StoreName.md) 
#### 
#### storeLocation
Type: [System.Security.Cryptography.X509Certificates.StoreLocation](System.Security.Cryptography.X509Certificates.StoreLocation.md) 
#### 
#### thumbPrint
Type: [System.String](System.String.md) 
#### 
#### (optional) environment
Type: [OfficeDevPnP.Core.AzureEnvironment](OfficeDevPnP.Core.AzureEnvironment.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md)ClientContext being used
## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
