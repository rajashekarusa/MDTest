ClientContext, ExtensibilityHandler, ProvisioningTemplate, ProvisioningTemplateApplyingInformation, TokenParser, PnPMonitoredScope# ExtensibilityManager.ExecuteExtensibilityProvisionCallOut members
Method to Invoke Custom Provisioning Handlers.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public void ExecuteExtensibilityProvisionCallOut(ClientContext, ExtensibilityHandler, ProvisioningTemplate, ProvisioningTemplateApplyingInformation, TokenParser, PnPMonitoredScope)
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
#### applyingInformation
Type: [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.md) 
#### 
#### tokenParser
Type: [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParser](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParser.md) 
#### 
#### scope
Type: [OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope](OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope.md) 
#### 
### Return Value
Type: [System.Void](System.Void.md)## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
