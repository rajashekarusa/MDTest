# ExtensibilityManager.ExecuteExtensibilityProvisionCallOut Method  
Method to Invoke Custom Provisioning Handlers.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public void ExecuteExtensibilityProvisionCallOut(ClientContext ctx,ExtensibilityHandler handler,ProvisioningTemplate template,ProvisioningTemplateApplyingInformation applyingInformation,TokenParser tokenParser,PnPMonitoredScope scope)
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
  
*applyingInformation*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.md) 
&emsp;&emsp;  
  
*tokenParser*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParser](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.TokenParser.md) 
&emsp;&emsp;  
  
*scope*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope](OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md 
)
## Remarks 

            Ensure the ClientContext is not disposed in the custom provider.
            
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
