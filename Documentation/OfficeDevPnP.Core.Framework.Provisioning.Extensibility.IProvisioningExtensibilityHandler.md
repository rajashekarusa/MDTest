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
| [Provision(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParser, OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope, String)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.IProvisioningExtensibilityHandler.ProvisionMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformationOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParserOfficeDevPnP.Core.Diagnostics.PnPMonitoredScopeString.md) | Execute custom actions during provisioning of a template
| [Extract(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation, OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope, String)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.IProvisioningExtensibilityHandler.ExtractMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformationOfficeDevPnP.Core.Diagnostics.PnPMonitoredScopeString.md) | Execute custom actions during extraction of a template
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
