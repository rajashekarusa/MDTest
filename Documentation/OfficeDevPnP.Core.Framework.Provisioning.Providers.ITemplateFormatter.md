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
| [IsValid(Stream)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.IsValidStream.md) | Method to validate the content of a formatted template instace
| [ToFormattedTemplate(ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.ToFormattedTemplateProvisioningTemplate.md) | Method to format a ProvisioningTemplate into a formatted template
| [ToProvisioningTemplate(Stream)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.ToProvisioningTemplateStream.md) | Method to convert a formatted template into a ProvisioningTemplate
| [ToProvisioningTemplate(Stream, String)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateFormatter.ToProvisioningTemplateStreamString.md) | Method to convert a formatted template into a ProvisioningTemplate, based on a specific ID
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)
