# IProvisioningExtensibilityHandler
Defines an interface which allows to plugin custom Provisioning Extensibility Handlers to the template extraction/provisioning pipeline  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public interface IProvisioningExtensibilityHandler
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Provision(ClientContext, ProvisioningTemplate, ProvisioningTemplateApplyingInformation, TokenParser, PnPMonitoredScope, String)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.IProvisioningExtensibilityHandler.ProvisionClientContextProvisioningTemplateProvisioningTemplateApplyingInformationTokenParserPnPMonitoredScopeString.md) | Execute custom actions during provisioning of a template
| [Extract(ClientContext, ProvisioningTemplate, ProvisioningTemplateCreationInformation, PnPMonitoredScope, String)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.IProvisioningExtensibilityHandler.ExtractClientContextProvisioningTemplateProvisioningTemplateCreationInformationPnPMonitoredScopeString.md) | Execute custom actions during extraction of a template
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
