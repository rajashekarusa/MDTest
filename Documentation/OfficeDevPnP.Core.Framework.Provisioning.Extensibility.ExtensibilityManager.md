# ExtensibilityManager
Provisioning Framework Component that is used for invoking custom providers during the provisioning process.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public class ExtensibilityManager
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [ExtensibilityManager()](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.ctor1.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ExecuteExtensibilityCallOut(ClientContext, ExtensibilityHandler, ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.36A5E1B4.md) | Method to Invoke Custom Provisioning Providers. Ensure the ClientContext is not disposed in the custom provider.
| [ExecuteTokenProviderCallOut(ClientContext, ExtensibilityHandler, ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.2865F124.md) | Method to Invoke Custom Provisioning Token Providers which implement the IProvisioningExtensibilityTokenProvider interface. Ensure the ClientContext is not disposed in the custom provider.
| [ExecuteExtensibilityProvisionCallOut(ClientContext, ExtensibilityHandler, ProvisioningTemplate, ProvisioningTemplateApplyingInformation, TokenParser, PnPMonitoredScope)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.2DB05B82.md) | Method to Invoke Custom Provisioning Handlers.
| [ExecuteExtensibilityExtractionCallOut(ClientContext, ExtensibilityHandler, ProvisioningTemplate, ProvisioningTemplateCreationInformation, PnPMonitoredScope)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.44BD95C4.md) | Method to Invoke Custom Extraction Handlers.
| [GetProviderInstance(ExtensibilityHandler)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.C6867F92.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
