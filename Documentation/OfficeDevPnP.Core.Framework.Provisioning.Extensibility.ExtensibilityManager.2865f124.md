# ExtensibilityManager.ExecuteTokenProviderCallOut Method  
Method to Invoke Custom Provisioning Token Providers which implement the IProvisioningExtensibilityTokenProvider interface.
            Ensure the ClientContext is not disposed in the custom provider.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public collections.generic.ienumerable`1<officedevpnp.core.framework.provisioning.objecthandlers.tokendefinitions.tokendefinition> ExecuteTokenProviderCallOut(ClientContext ctx,ExtensibilityHandler provider,ProvisioningTemplate template)
```
### Parameters
*ctx*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md) 
&emsp;&emsp;  
  
*provider*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler](OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler.md) 
&emsp;&emsp;  
  
*template*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate](OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.IEnumerable`1<OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenDefinitions.TokenDefinition>](System.Collections.Generic.IEnumerable`1<OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenDefinitions.TokenDefinition>.md)  

## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
