ClientContext, ExtensibilityHandler, ProvisioningTemplate# ExtensibilityManager.ExecuteExtensibilityCallOut members
Method to Invoke Custom Provisioning Providers. 
            Ensure the ClientContext is not disposed in the custom provider.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public void ExecuteExtensibilityCallOut(ClientContext, ExtensibilityHandler, ProvisioningTemplate)
```
### Parameters
#### ctx
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md) 
#### 
#### handler
Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler](OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler.md) 
#### 
#### template
Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate](OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) 
#### 
### Return Value
Type: [System.Void](System.Void.md)## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
