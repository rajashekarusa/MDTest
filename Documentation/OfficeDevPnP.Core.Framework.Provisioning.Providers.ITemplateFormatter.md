# ITemplateFormatter
Interface for basic capabilites that any Template Formatter should provide/support  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public interface ITemplateFormatter
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Initialize(TemplateProviderBase)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.InitializeTemplateProviderBase.md) | Method to initialize the formatter with the proper TemplateProvider instance
| [IsValid(IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.IsValidIO.Stream.md) | Method to validate the content of a formatted template instace
| [ToFormattedTemplate(OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.ToFormattedTemplateOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate.md) | Method to format a ProvisioningTemplate into a formatted template
| [ToProvisioningTemplate(IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.ToProvisioningTemplateIO.Stream.md) | Method to convert a formatted template into a ProvisioningTemplate
| [ToProvisioningTemplate(IO.Stream, String)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.ToProvisioningTemplateIO.StreamString.md) | Method to convert a formatted template into a ProvisioningTemplate, based on a specific ID
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)
