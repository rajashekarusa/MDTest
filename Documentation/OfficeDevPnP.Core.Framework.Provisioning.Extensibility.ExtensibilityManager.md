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
| [ExtensibilityManager()](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.Constructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ExecuteExtensibilityCallOut(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.ExecuteExtensibilityCallOutMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandlerOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | Method to Invoke Custom Provisioning Providers. Ensure the ClientContext is not disposed in the custom provider.
| [ExecuteTokenProviderCallOut(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.ExecuteTokenProviderCallOutMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandlerOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | Method to Invoke Custom Provisioning Token Providers which implement the IProvisioningExtensibilityTokenProvider interface. Ensure the ClientContext is not disposed in the custom provider.
| [ExecuteExtensibilityProvisionCallOut(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParser, OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.ExecuteExtensibilityProvisionCallOutMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandlerOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformationOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParserOfficeDevPnP.Core.Diagnostics.PnPMonitoredScope.md) | Method to Invoke Custom Provisioning Handlers.
| [ExecuteExtensibilityExtractionCallOut(Microsoft.SharePoint.Client.ClientContext, OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation, OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.ExecuteExtensibilityExtractionCallOutMicrosoft.SharePoint.Client.ClientContextOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandlerOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformationOfficeDevPnP.Core.Diagnostics.PnPMonitoredScope.md) | Method to Invoke Custom Extraction Handlers.
| [GetProviderInstance(OfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler)](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.ExtensibilityManager.GetProviderInstanceOfficeDevPnP.Core.Framework.Provisioning.Model.ExtensibilityHandler.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
