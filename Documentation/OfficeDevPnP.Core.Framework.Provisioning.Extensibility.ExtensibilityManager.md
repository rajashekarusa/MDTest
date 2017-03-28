# ExtensibilityManager
Provisioning Framework Component that is used for invoking custom providers during the provisioning process.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class ExtensibilityManager
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [ExtensibilityManager()](ExtensibilityManagerconstructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ExecuteExtensibilityCallOut(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](ExtensibilityManagerExecuteExtensibilityCallOutMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandlerOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | Method to Invoke Custom Provisioning Providers. Ensure the ClientContext is not disposed in the custom provider.
| [ExecuteTokenProviderCallOut(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](ExtensibilityManagerExecuteTokenProviderCallOutMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandlerOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | Method to Invoke Custom Provisioning Token Providers which implement the IProvisioningExtensibilityTokenProvider interface. Ensure the ClientContext is not disposed in the custom provider.
| [ExecuteExtensibilityProvisionCallOut(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParser, OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope)](ExtensibilityManagerExecuteExtensibilityProvisionCallOutMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandlerOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformationOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParserOfficeDevPnP.Core.Diagnostics.PnPMonitoredScope.md) | Method to Invoke Custom Provisioning Handlers.
| [ExecuteExtensibilityExtractionCallOut(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation, OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope)](ExtensibilityManagerExecuteExtensibilityExtractionCallOutMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandlerOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformationOfficeDevPnP.Core.Diagnostics.PnPMonitoredScope.md) | Method to Invoke Custom Extraction Handlers.
| [GetProviderInstance(OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler)](ExtensibilityManagerGetProviderInstanceOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
