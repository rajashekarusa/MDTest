# TemplateProviderBase
  
**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class TemplateProviderBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [TemplateProviderBase()](TemplateProviderBaseconstructor1details.md) | 
| [TemplateProviderBase(OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase)](TemplateProviderBaseconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Parameters](TemplateProviderBase.Parameters.md) | 
| [SupportsSave](TemplateProviderBase.SupportsSave.md) | 
| [SupportsDelete](TemplateProviderBase.SupportsDelete.md) | 
| [Connector](TemplateProviderBase.Connector.md) | 
| [Uri](TemplateProviderBase.Uri.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetTemplates()](TemplateProviderBaseGetTemplates.md) | 
| [GetTemplates(ITemplateFormatter)](TemplateProviderBaseGetTemplatesITemplateFormatter.md) | 
| [GetTemplate(String)](TemplateProviderBaseGetTemplateString.md) | 
| [GetTemplate(String, ITemplateProviderExtension[])](TemplateProviderBaseGetTemplateStringITemplateProviderExtension[].md) | 
| [GetTemplate(String, String)](TemplateProviderBaseGetTemplateStringString.md) | 
| [GetTemplate(String, ITemplateFormatter)](TemplateProviderBaseGetTemplateStringITemplateFormatter.md) | 
| [GetTemplate(String, String, ITemplateFormatter)](TemplateProviderBaseGetTemplateStringStringITemplateFormatter.md) | 
| [GetTemplate(String, String, ITemplateFormatter, ITemplateProviderExtension[])](TemplateProviderBaseGetTemplateStringStringITemplateFormatterITemplateProviderExtension[].md) | 
| [Save(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](TemplateProviderBaseSaveOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | 
| [Save(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, ITemplateProviderExtension[])](TemplateProviderBaseSaveOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateITemplateProviderExtension[].md) | 
| [Save(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, ITemplateFormatter)](TemplateProviderBaseSaveOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateITemplateFormatter.md) | 
| [Save(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, ITemplateFormatter, ITemplateProviderExtension[])](TemplateProviderBaseSaveOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateITemplateFormatterITemplateProviderExtension[].md) | 
| [SaveAs(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String)](TemplateProviderBaseSaveAsOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateString.md) | 
| [SaveAs(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String, ITemplateProviderExtension[])](TemplateProviderBaseSaveAsOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateStringITemplateProviderExtension[].md) | 
| [SaveAs(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String, ITemplateFormatter)](TemplateProviderBaseSaveAsOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateStringITemplateFormatter.md) | 
| [SaveAs(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String, ITemplateFormatter, ITemplateProviderExtension[])](TemplateProviderBaseSaveAsOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateStringITemplateFormatterITemplateProviderExtension[].md) | 
| [Delete(String)](TemplateProviderBaseDeleteString.md) | 
| [SaveToConnector(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String, ITemplateFormatter, ITemplateProviderExtension[])](TemplateProviderBaseSaveToConnectorOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateStringITemplateFormatterITemplateProviderExtension[].md) | 
| [PreProcessSaveTemplateExtensions(ITemplateProviderExtension[], OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](TemplateProviderBasePreProcessSaveTemplateExtensionsITemplateProviderExtension[]OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | This method is invoked before calling the formatter to serialize the template
| [PostProcessSaveTemplateExtensions(ITemplateProviderExtension[], IO.Stream)](TemplateProviderBasePostProcessSaveTemplateExtensionsITemplateProviderExtension[]IO.Stream.md) | 
| [PreProcessGetTemplateExtensions(ITemplateProviderExtension[], IO.Stream)](TemplateProviderBasePreProcessGetTemplateExtensionsITemplateProviderExtension[]IO.Stream.md) | 
| [PostProcessGetTemplateExtensions(ITemplateProviderExtension[], OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](TemplateProviderBasePostProcessGetTemplateExtensionsITemplateProviderExtension[]OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)
