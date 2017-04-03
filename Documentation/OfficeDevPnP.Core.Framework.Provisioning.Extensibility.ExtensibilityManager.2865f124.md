# ExtensibilityManager.ExecuteTokenProviderCallOut Method  
Method to Invoke Custom Provisioning Token Providers which implement the IProvisioningExtensibilityTokenProvider interface.
            Ensure the ClientContext is not disposed in the custom provider.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public collections.generic.ienumerable<officedevpnp.core.framework.provisioning.objecthandlers.tokendefinitions.tokendefinition> ExecuteTokenProviderCallOut(ClientContext ctx,ExtensibilityHandler provider,ProvisioningTemplate template)
```
### Parameters
*ctx*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.ClientContext  
&emsp;&emsp;Authenticated ClientContext that is passed to the custom provider.  
  
*provider*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler](OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler.md)  
&emsp;&emsp;A custom Extensibility Provisioning Provider  
  
*template*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate](OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md)  
&emsp;&emsp;ProvisioningTemplate that is passed to the custom provider  
  
### Return Value
Type: System.Collections.Generic.IEnumerable<OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenDefinitions.TokenDefinition>  

## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
