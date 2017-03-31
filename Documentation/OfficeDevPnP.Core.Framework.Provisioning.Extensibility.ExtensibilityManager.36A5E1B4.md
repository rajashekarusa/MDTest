# ExtensibilityManager.ExecuteExtensibilityCallOut Method  
Method to Invoke Custom Provisioning Providers. 
            Ensure the ClientContext is not disposed in the custom provider.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public void ExecuteExtensibilityCallOut(ClientContext ctx,ExtensibilityHandler handler,ProvisioningTemplate template)
```
### Parameters
*ctx*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md) 
&emsp;&emsp;  
  
*handler*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler](OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler.md) 
&emsp;&emsp;  
  
*template*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate](OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md 
)
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
