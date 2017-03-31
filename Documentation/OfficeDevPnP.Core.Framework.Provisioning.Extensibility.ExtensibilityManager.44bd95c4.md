# ExtensibilityManager.ExecuteExtensibilityExtractionCallOut Method  
Method to Invoke Custom Extraction Handlers.  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public  ExecuteExtensibilityExtractionCallOut(ClientContext ctx,ExtensibilityHandler handler,ProvisioningTemplate template,ProvisioningTemplateCreationInformation creationInformation,PnPMonitoredScope scope)
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
  
*creationInformation*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation.md) 
&emsp;&emsp;  
  
*scope*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope](OfficeDevPnP.Core.Diagnostics.PnPMonitoredScope.md) 
&emsp;&emsp;  
  
### Return Value
Type: [OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate](OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md)  

## Remarks 

            Ensure the ClientContext is not disposed in the custom provider.
            
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Extensibility](OfficeDevPnP.Core.Framework.Provisioning.Extensibility.md)
