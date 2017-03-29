# TemplateProviderBase
  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public class TemplateProviderBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [TemplateProviderBase()](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.Constructor1details.md) | 
| [TemplateProviderBase(FileConnectorBase)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.Constructor2details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Parameters](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.Parameters.md) | 
| [SupportsSave](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SupportsSave.md) | 
| [SupportsDelete](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SupportsDelete.md) | 
| [Connector](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.Connector.md) | 
| [Uri](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.Uri.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetTemplates()](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.GetTemplates.md) | 
| [GetTemplates(ITemplateFormatter)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.GetTemplatesITemplateFormatter.md) | 
| [GetTemplate(String)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.GetTemplateString.md) | 
| [GetTemplate(String, ITemplateProviderExtension[])](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.GetTemplateStringITemplateProviderExtension[].md) | 
| [GetTemplate(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.GetTemplateStringString.md) | 
| [GetTemplate(String, ITemplateFormatter)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.GetTemplateStringITemplateFormatter.md) | 
| [GetTemplate(String, String, ITemplateFormatter)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.GetTemplateStringStringITemplateFormatter.md) | 
| [GetTemplate(String, String, ITemplateFormatter, ITemplateProviderExtension[])](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.GetTemplateStringStringITemplateFormatterITemplateProviderExtension[].md) | 
| [Save(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | 
| [Save(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, ITemplateProviderExtension[])](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateITemplateProviderExtension[].md) | 
| [Save(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, ITemplateFormatter)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateITemplateFormatter.md) | 
| [Save(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, ITemplateFormatter, ITemplateProviderExtension[])](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateITemplateFormatterITemplateProviderExtension[].md) | 
| [SaveAs(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveAsOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateString.md) | 
| [SaveAs(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String, ITemplateProviderExtension[])](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveAsOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateStringITemplateProviderExtension[].md) | 
| [SaveAs(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String, ITemplateFormatter)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveAsOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateStringITemplateFormatter.md) | 
| [SaveAs(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String, ITemplateFormatter, ITemplateProviderExtension[])](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveAsOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateStringITemplateFormatterITemplateProviderExtension[].md) | 
| [Delete(String)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.DeleteString.md) | 
| [SaveToConnector(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, String, ITemplateFormatter, ITemplateProviderExtension[])](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.SaveToConnectorOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateStringITemplateFormatterITemplateProviderExtension[].md) | 
| [PreProcessSaveTemplateExtensions(ITemplateProviderExtension[], OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.PreProcessSaveTemplateExtensionsITemplateProviderExtension[]OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | This method is invoked before calling the formatter to serialize the template
| [PostProcessSaveTemplateExtensions(ITemplateProviderExtension[], IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.PostProcessSaveTemplateExtensionsITemplateProviderExtension[]IO.Stream.md) | 
| [PreProcessGetTemplateExtensions(ITemplateProviderExtension[], IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.PreProcessGetTemplateExtensionsITemplateProviderExtension[]IO.Stream.md) | 
| [PostProcessGetTemplateExtensions(ITemplateProviderExtension[], OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Providers.TemplateProviderBase.PostProcessGetTemplateExtensionsITemplateProviderExtension[]OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)
